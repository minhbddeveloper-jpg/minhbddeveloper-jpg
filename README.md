<div align="center">

# Hi, I'm Gild

### I build backend systems, developer tools, and tiny automation machines

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2400&pause=700&center=true&vCenter=true&width=760&lines=Clean+Architecture+fan;Backend+and+DevTools+builder;Turning+repetitive+setup+into+CLI+magic;Currently+building+arxgen)

![Profile Views](https://komarev.com/ghpvc/?username=minhbddeveloper-jpg&style=for-the-badge&color=blueviolet)
![GitHub followers](https://img.shields.io/github/followers/minhbddeveloper-jpg?style=for-the-badge&logo=github)
![npm](https://img.shields.io/npm/v/arxgen?style=for-the-badge&logo=npm&label=arxgen)

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

---

## About Me

I'm a software developer focused on practical backend engineering, Clean Architecture, and developer productivity tools.

I like building things that remove boring setup work. If something has to be repeated many times, I usually want to turn it into a CLI, generator, template system, or automation workflow.

```text
My developer loop:

idea -> architecture -> code -> test -> automate -> repeat
```

My favorite kind of project is a tool that helps other developers start faster, stay organized, and avoid messy boilerplate.

---

## Featured Project: arxgen

`arxgen` is a multi-language CLI project generator for creating Clean Architecture-style starters.

It is designed to generate real project structure, not just a few demo files.

```bash
npm install -g arxgen
```

```bash
arxgen doctor
arxgen list plugins
```

### Quick Demo

```bash
arxgen create \
  --name student-api \
  --language typescript \
  --framework express \
  --entity student \
  --field name:string \
  --field email:string \
  --out ./generated
```

Generated API shape:

```text
student-api/
  src/
    domain/
    application/
      ports/
      use-cases/
      dtos/
    infrastructure/
      repositories/
    presentation/
      controllers/
      routes/
```

---

## What arxgen Can Do

| Feature | Status |
| --- | --- |
| Generate new projects | Available |
| Generate frontend/backend/fullstack starters | Available |
| Generate entities and CRUD modules | Available |
| Generate repositories, controllers, routes, use cases | Available |
| Generate DTOs and validation schemas | Available for supported stacks |
| Generate pagination helpers | Available for Express and NestJS output |
| Generate JWT auth scaffolding | Available for TypeScript Express |
| Generate ORM artifacts | Available for selected stacks |
| Generate Docker, Nginx, Redis setup | Available |
| Extend existing generated projects | Available for TypeScript Express |
| AST-based route merge | Available for `arxgen add entity` |
| Snapshot tests for generated output | Available |
| GitHub Actions CI | Available |

---

## Supported Stacks

| Language | Framework |
| --- | --- |
| TypeScript | React |
| TypeScript | Express |
| TypeScript | NestJS |
| Python | FastAPI |
| Python | Django |
| Java | Spring Boot |
| C# | ASP.NET Core |
| PHP | Laravel |
| Go | Gin |
| Ruby | Rails |
| Kotlin | Ktor |

---

## arxgen Commands I Care About

### Create a NestJS API

```bash
arxgen create \
  --name nest-school \
  --language typescript \
  --framework nestjs \
  --entity student \
  --field name:string \
  --out ./generated
```

### Create an Express API with Prisma, validation, JWT auth, and relations

```bash
arxgen create \
  --name course-api \
  --language typescript \
  --framework express \
  --entity student \
  --entity course \
  --field student.name:string \
  --field course.title:string \
  --database postgres \
  --orm prisma \
  --relation course.student:many-to-one \
  --validation zod \
  --auth jwt \
  --out ./generated
```

### Extend an Existing Project

```bash
arxgen add entity course \
  --field title:string \
  --field credits:number \
  --merge
```

This is the direction I like most: making `arxgen` not only a starter generator, but an architecture evolution tool.

---

## Quality Setup

`arxgen` is tested with:

- TypeScript typecheck
- Node.js test runner
- Snapshot tests for generated files
- GitHub Actions CI
- Package dry-run before publishing

```bash
npm run typecheck
npm test
npm pack --dry-run
```

---

## Tech Stack

### Languages

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C%23](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

### Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)

### Frontend

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

### Infrastructure and Tools

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

---

## Current Focus

I'm currently improving `arxgen` in these areas:

- Stronger NestJS generation
- Better `arxgen add entity` project evolution
- Cleaner plugin contracts
- More reliable generated output through snapshot tests
- More production-ready DTO, validation, pagination, auth, and ORM scaffolding

```text
Project starter
      |
      v
Architecture evolution tool
      |
      v
Developer productivity platform
```

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=minhbddeveloper-jpg&show_icons=true&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=minhbddeveloper-jpg&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=minhbddeveloper-jpg&theme=tokyonight&hide_border=true)

</div>

---

## Tiny Playground

```text
        [ idea ]
           |
           v
   +----------------+
   |     arxgen     |
   +----------------+
     /      |      \
    v       v       v
 Backend  Web   Infrastructure
    |       |       |
    v       v       v
  Clean   Fast   Repeatable
```

Small idea. Clean structure. Less boilerplate. More shipping.

---

## Connect

- GitHub: [@minhbddeveloper-jpg](https://github.com/minhbddeveloper-jpg)
- npm: [`arxgen`](https://www.npmjs.com/package/arxgen)
- Main project: [`arxgen`](https://github.com/minhbddeveloper-jpg/archgen_architecture)

---

<div align="center">

### Build tools that remove repetitive work.

`simple code` + `clear architecture` + `useful automation`

</div>
