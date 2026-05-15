# Hi, I'm Minh

I'm a software developer focused on building practical tools, clean backend systems, and scalable application architectures.

I enjoy turning repeated development work into reusable systems, generators, and automation tools that help developers move faster without losing code quality.

## What I'm Working On

### arxgen

`arxgen` is a CLI project generator for creating Clean Architecture-style applications across multiple languages and frameworks.

It supports:

- TypeScript Express
- TypeScript NestJS
- React
- Python FastAPI
- Java Spring Boot
- C# ASP.NET Core
- Go Gin
- PHP Laravel
- Ruby Rails
- Kotlin Ktor

Key features:

- Generate project starters
- Generate entities, CRUD, DTOs, repositories, controllers, routes, and use cases
- Support Docker, Nginx, Redis, database, ORM, JWT auth, validation, and pagination scaffolding
- Extend existing generated projects with `arxgen add entity`
- Snapshot-tested generated output
- GitHub Actions CI with typecheck and tests

Install:

```bash
npm install -g arxgen
```

Example:

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

## Interests

- Clean Architecture
- Backend engineering
- Developer tools
- Code generators
- TypeScript
- NestJS
- Express
- ASP.NET Core
- Spring Boot
- Automation
- System design

## Tech Stack

### Languages

- TypeScript
- JavaScript
- C#
- Java
- Python
- Go
- PHP
- SQL

### Backend

- Node.js
- Express
- NestJS
- ASP.NET Core
- Spring Boot
- FastAPI
- Laravel
- Gin

### Frontend

- React
- Vite
- HTML
- CSS

### Database and Infrastructure

- PostgreSQL
- MySQL
- MongoDB
- Redis
- Docker
- Nginx
- GitHub Actions

## Current Focus

I'm currently improving `arxgen` into a stronger architecture evolution tool.

The goal is to make it more than a project starter. I want it to help developers grow existing projects by adding entities, CRUD modules, DTOs, validation, auth, and framework-specific architecture patterns safely and consistently.

## Connect

- GitHub: [@minhbddeveloper-jpg](https://github.com/minhbddeveloper-jpg)
- npm: [`arxgen`](https://www.npmjs.com/package/arxgen)

## Philosophy

Build tools that remove repetitive work.

Write code that is easy to understand, easy to extend, and useful in real projects.
