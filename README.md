<div align="center">

# Yamashita Sadao

**Backend engineer · DevOps · Full-stack TypeScript**

Building APIs and delivery pipelines that stay boring in production.

</div>

---

## About

I design and ship **server-side systems** with a DevOps bias: typed APIs, explicit auth, PostgreSQL as the source of truth, and the same image running locally as in CI.

Day to day that means NestJS modules, Prisma schemas, JWT session flows, Docker Compose stacks, and GitHub Actions that fail loudly instead of deploying guesses.

- Prefer **clear module boundaries** over clever abstractions
- Treat **auth, validation, and migrations** as product features
- Keep **local, CI, and production** as close as the Dockerfile allows

---

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,nodejs,nestjs,express,prisma,postgres,docker,linux,nginx,githubactions,git" alt="Tech stack" />
</p>

| Layer | Tools |
| :--- | :--- |
| **Languages** | TypeScript, JavaScript, SQL |
| **Runtime & APIs** | Node.js, NestJS, Express |
| **Data** | PostgreSQL, Prisma |
| **Auth** | JWT, Passport, bcrypt |
| **Quality** | Jest, ESLint, Prettier, class-validator |
| **Delivery** | Docker, Docker Compose, GitHub Actions |

---

## How I build

```mermaid
flowchart LR
  A[Client] --> B[NestJS API]
  B --> C[JWT / Guards]
  B --> D[Prisma]
  D --> E[(PostgreSQL)]
  B --> F[Docker image]
  F --> G[Compose / CI]
```

| Concern | Default |
| :--- | :--- |
| HTTP surface | NestJS modules, DTOs, `class-validator` |
| Persistence | Prisma + PostgreSQL, migrations in source control |
| Identity | Passport JWT, hashed secrets, no header-spoofed user ids |
| Runtime | Multi-stage Dockerfiles, Compose for the full stack |
| Pipeline | GitHub Actions on every push: lint, test, image build |

---

## Focus

**APIs.** Resource design, validation, error contracts, and auth that an actual client can trust.

**Data.** Schema-first models, migrations you can replay, queries that stay inside the ORM until they shouldn't.

**Delivery.** Containerized Node services, Compose for local parity, CI that builds the same artifact you ship.

---

## GitHub

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=ysadao&show_icons=true&count_private=true&hide_border=true&theme=tokyonight&include_all_commits=true" alt="GitHub stats" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ysadao&layout=compact&count_private=true&hide_border=true&theme=tokyonight&langs_count=8" alt="Top languages" />
</div>

<br/>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ysadao&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</div>

---

## Currently

- Hardening NestJS + Prisma services (auth, orgs, PostgreSQL)
- Tightening Docker and GitHub Actions so deploys are repeatable
- Writing down architecture decisions instead of keeping them in chat history

---

<div align="center">

**[github.com/ysadao](https://github.com/ysadao)**

<sub>TypeScript · NestJS · PostgreSQL · Docker</sub>

</div>
