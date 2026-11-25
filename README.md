<h1 align="center">Alexis Romero Mendoza</h1>
<h3 align="center">Computer Systems Engineer · Full-Stack Developer (React, Next.js & NestJS)</h3>

<p align="center">
  <a href="https://dejuarez.mx/"><img src="https://img.shields.io/badge/Portfolio-dejuarez.mx-111827?style=flat-square" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/alexis-romero-mendoza-4a8b03221/"><img src="https://img.shields.io/badge/LinkedIn-Alexis%20Romero-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:alexis.rm162917@gmail.com"><img src="https://img.shields.io/badge/Email-alexis.rm162917%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## 👋 About me

Computer Systems Engineer (UACJ) who builds and operates complete web systems: from the UI, through the API and database, down to the Linux servers they run on. I work across the **JavaScript/TypeScript** stack and I'm just as comfortable shipping the product as deploying, securing and maintaining it.

What I care about is solving real business problems with solid engineering: clear architecture, reproducible deployments, and software that keeps working after the demo. I like owning the whole path — I've migrated a product off a managed backend to self-hosted infrastructure, debugged native-binary crashes on legacy CPUs, and put legacy **Sybase** databases behind a modern stack.

Outside of code I read psychology and philosophy, which keeps me thinking critically about how and why I build things.

## 🎓 Education

**Computer Systems Engineer** — Universidad Autónoma de Ciudad Juárez (UACJ)

---

## 🛠️ Tech Stack

| Category | Technologies |
| --- | --- |
| **Languages** | TypeScript, JavaScript (ES6+), Python, SQL, Bash |
| **Frontend** | React 19, Next.js 16 (App Router), Tailwind CSS, shadcn/ui, PWA, HTML5/CSS3 |
| **Backend** | NestJS, Node.js, Express, REST APIs, JWT authentication (bcrypt, httpOnly cookies) |
| **Databases & ORMs** | PostgreSQL, MySQL, Sybase, SQLite/libSQL · TypeORM, Drizzle ORM · schema migrations, `pg_dump` backups |
| **Infrastructure & Ops** | Docker & Docker Compose (multi-stage builds), Coolify, Traefik, Cloudflare Tunnels, Nginx, PM2, Linux (Debian/Ubuntu), SSH |
| **Storage & Docs** | S3-compatible storage (MinIO, SeaweedFS), Carbone (document generation) |
| **Tooling** | Git (GitFlow), GitHub Actions (CI), pnpm, monorepos, Postman, Electron, Supabase |

---

## 🚀 Featured Projects

### Open source & public

#### [El Changarro — Business Management Platform](https://github.com/arm-code/elchangarro) · [live](https://elchangarro.dejuarez.mx/)
*A monorepo of tools that help small shopkeepers and entrepreneurs digitize their daily operations.*
- **Stack:** Next.js 16, NestJS, TypeORM, PostgreSQL, Docker Compose, Coolify, Cloudflare Tunnel
- **`apps/os`** — admin dashboard ([live demo of a deployment](https://eventosmendoza.dejuarez.mx/)): inventory, event scheduling, automated quoting and sales notes for event-rental businesses.
- **`apps/toolbox`** — offline-first PWA of micro-apps for shopkeepers (no backend, data stays on the device).
- **`apps/api`** — NestJS REST API with its own session auth (JWT in httpOnly cookies, bcrypt), single-business-per-instance model, and disk-backed file storage.
- **Highlights:** migrated the product from Supabase (hosted Postgres, auth and storage) to **self-hosted PostgreSQL, custom auth and file storage**, preserving the existing data; production-style deployment with Docker Compose, one-shot migrations, health checks and scripted backups/restores.

#### [Sake — Self-hosted Ebook Library & KOReader Sync](https://github.com/arm-code/sakesealv)
*A maintained fork of [Sudashiii/Sake](https://github.com/Sudashiii/Sake) (AGPL-3.0), now developed independently — full credit to the original author.*
- **Stack:** Next.js 16, React 19, TypeScript, Drizzle ORM, libSQL (sqld), SeaweedFS (S3), Docker
- Personal library with reading progress, highlights and notes synced with e-readers through KOReader, plus OPDS/WebDAV endpoints.
- **My work:** moved the build from Bun to Node + pnpm, wrote the Coolify deployment (compose stack with an `sqld` database service), set up CI with GitHub Actions, and diagnosed and worked around `Illegal instruction` crashes of native binaries (Bun, `sharp`, `libsql`) on legacy x86 CPUs without SSE4.2/AVX2.

#### [dejuarez.mx — Software Development & Web Services](https://dejuarez.mx/)
*Independent studio providing custom software and web development for local businesses and community initiatives.*
- **Stack:** Next.js, Cloudflare
- Custom websites, subdomain provisioning and digital infrastructure for small businesses.

### Professional (private repositories)

#### [SIGET — School Control System for Telebachilleratos](https://stg-siget.spaytchihuahua.gob.mx)
*Academic management system for SPAyT's Telebachillerato network — in development.*
- **Stack:** Next.js, NestJS
- End-to-end school control platform (enrollment, users, academic records) built for real institutional scale.

#### SPAyT Internal System
*Institutional management system for SPAyT Chihuahua.*
- **Stack:** Next.js, NestJS, MySQL, MinIO, Carbone, Docker, Debian, Coolify
- Integrated legacy **Sybase** databases with a modern stack; deployed on Ubuntu production servers with high-availability process management (PM2).

#### [SPAyT 2026 — Prepa Abierta Landing Page](https://spaytchihuahua.gob.mx/spayt-2026/prepa-abierta)
*Public landing page for SPAyT's Prepa Abierta program.*
- **Stack:** React (TypeScript), PHP MVC API
- Institutional site built for public outreach and student enrollment information.

---

## 📫 Let's connect

- **Portfolio / freelance:** [dejuarez.mx](https://dejuarez.mx/)
- **LinkedIn:** [Alexis Romero Mendoza](https://www.linkedin.com/in/alexis-romero-mendoza-4a8b03221/)
- **Email:** alexis.rm162917@gmail.com
