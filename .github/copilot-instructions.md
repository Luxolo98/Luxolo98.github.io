## Project Stack
- Java 17+
- Spring Boot 3.x
- Spring Data JPA / Jakarta Persistence
- REST API

  ## Architecture: Domain Driven Design (DDD)
- Separate Factory class per aggregate (e.g. `EmployeeFactory`)
- Factories are the **only** place where entities are instantiated
- No direct `new Entity()` calls outside of factories
- Rich domain model — logic lives in the domain layer, not services
- Entities are immutable after construction (Builder pattern, no setters)

## Package Structure (DDD)
- domain/
  - entity/
  - valueobject/
  - factory/
  - repository/        ← interfaces only (no impl)
- infrastructure/
  - repository/        ← JPA implementations
- application/
  - service/
- interfaces/
  - controller/
  - dto/

## Entity Pattern
- Entities use the **Builder pattern** (static inner `Builder` class)
- Private constructor that accepts a Builder: `private Entity(Builder builder)`
- Protected no-arg constructor for JPA: `protected Entity() {}`
- **No setters** — entities are immutable after construction
- Getters only, no Lombok
- `@Entity` on class, `@Id` + `@GeneratedValue(strategy = GenerationType.IDENTITY)` on id
- Use `jakarta.persistence.*` imports (not javax)
- Fields: id (Long), domain-specific fields, use `LocalDate` for dates

## Abstract Base Entity (if applicable)
- Common fields (id, createdAt, etc.) live in an `@MappedSuperclass` abstract base
- Child entities extend it and only define their own fields
- Value objects are immutable, implement `equals()` and `hashCode()`

## Builder Pattern Convention
- Setters on Builder return `this` for chaining
- Include a `copy(Entity e)` method on Builder for update operations
- `build()` returns a new entity instance



## Testing
- Unit tests for value objects and builders
- Integration tests for repositories
