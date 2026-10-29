---
layout: default
title: Projects | Luxolo Matshikiza
---

<style>
html{scroll-behavior:smooth}
body{background:#080c14;color:#cbd5e1}
body::before{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;
background:
radial-gradient(circle at 15% 10%,rgba(0,229,255,.10),transparent 45%),
radial-gradient(circle at 90% 85%,rgba(124,77,255,.10),transparent 45%),
url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='180' height='180' viewBox='0 0 180 180' fill='none' stroke='%2300e5ff' stroke-opacity='.16' stroke-width='1.5'%3E%3Cpath d='M0 40h50l20 20h45M90 0v30l22 22h68M0 130h32l26-26h38l22 22v54M130 180v-30l20-20h30'/%3E%3Ccircle cx='50' cy='40' r='3.5' fill='%2300e5ff' fill-opacity='.35'/%3E%3Ccircle cx='115' cy='60' r='3.5' fill='%2300e5ff' fill-opacity='.35'/%3E%3Ccircle cx='96' cy='104' r='3.5' fill='%2300e5ff' fill-opacity='.35'/%3E%3Ccircle cx='150' cy='130' r='3.5' fill='%2300e5ff' fill-opacity='.35'/%3E%3Crect x='64' y='74' width='18' height='11' rx='2'/%3E%3Cpath d='M68 74v-5M73 74v-5M78 74v-5M68 85v5M73 85v5M78 85v5'/%3E%3C/svg%3E");}
.page-header{background-image:linear-gradient(135deg,#050810,#0f1b33 55%,#0a4a55)!important;border-bottom:2px solid #00e5ff;box-shadow:0 4px 30px rgba(0,229,255,.25)}
.page-header .project-name{color:#fff!important;text-shadow:0 0 18px rgba(0,229,255,.6)}
.page-header .project-tagline{color:#9be7f2!important}
.main-content{max-width:920px;color:#cbd5e1}
.main-content h1{color:#00e5ff;text-shadow:0 0 14px rgba(0,229,255,.45);font-family:'Fira Code',Consolas,monospace}
.main-content h2{margin-top:2.6em;padding:.6em .9em;background:linear-gradient(90deg,rgba(0,229,255,.14),rgba(0,229,255,0));border-left:5px solid #00e5ff;border-radius:6px;color:#fff;font-family:'Fira Code',Consolas,monospace;font-size:1.45em}
.main-content h2::before{content:"\2699\00a0";color:#00e5ff}
.main-content h3{color:#00e5ff;margin-top:1.6em;border-bottom:1px solid #1f3a4d;padding-bottom:.25em;font-family:'Fira Code',Consolas,monospace;font-size:1.05em}
.main-content h4{color:#9be7f2}
.main-content strong{color:#e6f7fa}
.main-content a{color:#4dd0e1}
.main-content em{color:#8fa3b8}
.main-content table{border-collapse:collapse;width:100%;display:block;overflow-x:auto}
.main-content th{background:#0f2a3d;color:#00e5ff;text-transform:uppercase;font-size:.8em;letter-spacing:.06em}
.main-content th,.main-content td{border:1px solid #1f3347;padding:.6em .8em;text-align:left}
.main-content td{background:#0c1422}
.main-content tr:nth-child(even) td{background:#101a2b}
.main-content img{max-width:100%;border:1px solid #00e5ff;border-radius:10px;box-shadow:0 0 22px rgba(0,229,255,.25)}
.jump{display:flex;flex-wrap:wrap;gap:.5em;margin:1.2em 0}
.jump a{border:1px solid #00e5ff;color:#00e5ff;padding:.4em .95em;border-radius:999px;text-decoration:none;font-size:.88em;font-family:'Fira Code',Consolas,monospace;background:rgba(0,229,255,.06)}
.jump a:hover{background:#00e5ff;color:#080c14}
.reflection{background:rgba(13,22,38,.92);border:1px solid #1d3a4d;border-left:5px solid #7c4dff;border-radius:12px;padding:1.2em 1.5em;margin:1.2em 0;box-shadow:0 0 18px rgba(124,77,255,.12)}
.reflection p{margin:.2em 0 1.1em;color:#d5deea}
.reflection p>strong:first-child{display:block;color:#00e5ff;text-transform:uppercase;letter-spacing:.08em;font-size:.78em;font-family:'Fira Code',Consolas,monospace}
.site-footer{color:#8fa3b8!important}
::selection{background:#00e5ff;color:#080c14}
.project{background:rgba(13,22,38,.92);border:1px solid #1d3a4d;border-left:5px solid #00e5ff;border-radius:12px;padding:1.2em 1.5em;margin:1.4em 0;box-shadow:0 0 18px rgba(0,229,255,.10)}
.project h3{margin-top:0}
.tag{display:inline-block;border:1px solid #7c4dff;color:#cbb8ff;border-radius:999px;padding:.1em .7em;font-size:.8em;margin:.15em .2em .15em 0}
</style>

# Projects

A summary of the software projects I have worked on during my Diploma in ICT (Applications Development). Each one lists what it is, my role and the technology used.

[Back to home](index) · [Agile Portfolio: PC Revival](agile)

---

## Project Portfolio {#projects}

<div class="project" markdown="1">

### HERMS: Healthcare and Education Resource Management System
<span class="tag">Individual</span> <span class="tag">Applications Development Practice</span>

**What it is:** A booking system for organisations such as hospitals and schools to book nurses and teachers respectively.

**My role:** Design the Organisational POJO and all related design pattern distribution

**Tech:** Java (with design patterns), React, Tailwind CSS

**Status:** Runs locally. Source code on GitHub: https://github.com/Siyamthanda-Mnyabiso/herms

**Design patterns used:** Factory,Singleton,Creational,Behavioural,Structural

![HERMS screenshot](images/herms.png)

</div>

<div class="project" markdown="1">

### UniMart: CPUT Community Marketplace
<span class="tag">Group project</span> <span class="tag">Project Management</span>

**What it is:** A campus marketplace where students, faculty, residents and local vendors can buy, sell and trade. It has verified campus members, browse and free-stuff pages, local vendor shops, a wanted board for requests, in-app messaging, suggested safe pickup spots and campus events.

**My role:** Business Requirements and Supabase design

**Tech:** Node.js, and React + Vite., Supabase, Vercel

**Live site:** [unimart-mu.vercel.app](https://unimart-mu.vercel.app/)

![UniMart screenshot](images/unimart.png)

</div>

<div class="project" markdown="1">

### Eben Studios: Clothing E-commerce Store
<span class="tag">Group project</span>

**What it is:** An online store for a clothing business that had no online presence for trading, so customers can browse and buy its products on the web.

**My role:** Design database Supabase

**Tech:** Supabase React, Vercel

**Live site:** [eben-studios.vercel.app](https://eben-studios.vercel.app/)

![Eben Studios screenshot](images/eben-studios.png)

</div>

<div class="project" markdown="1">

### PC Revival: Student Laptop Repair and Refurbished Laptop Platform
<span class="tag">Group project</span> <span class="tag">Entrepreneurial WIL</span>

**What it is:** An affordable laptop repair, upgrade and refurbished laptop service for CPUT students, delivered in six Agile sprints.

**My role:** Researcher in the team charter, plus backend development (Supabase, PostgreSQL schema, API and booking logic) with a teammate.

**Tech:** Supabase, PostgreSQL, Tailwind CSS, Trello for Kanban

**Live site:** [PC Revival](https://pc-revival-fj68h8xcn-gee-c9e0.vercel.app/) · **Agile evidence:** [Agile Portfolio](agile)

</div>

<div class="project" markdown="1">

### Student Residence Application
<span class="tag">Group project</span> <span class="tag">CPUT</span>

**What it is:** A Java application using Swing GUI components and pattern matching validation. It provides secure user registration, residence search, accommodation browsing with details, and housing application management with database persistence.

**My role:** Database design and Registration page design

**Tech:** Java, Swing, database persistence

</div>
