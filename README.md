<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Ritik%20Garg&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full%20Stack%20Developer%20%7C%20Go%20%E2%80%A2%20Next.js%20%E2%80%A2%20Distributed%20Systems&descAlignY=60&descSize=18" width="100%" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&width=700&lines=Building+scalable+backends+in+Go+%F0%9F%9A%80;Double-entry+ledgers%2C+RBAC%2C+multi-tenancy;Clean+architecture+%7C+Event-driven+design;B.Tech+CSE+(AI+%26+ML)+%E2%80%94+Class+of+2026" alt="Typing SVG" />
</a>

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Ritik-x&label=Profile%20Views&color=2c5364&style=flat-square)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/u/HO4/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ritik-garg-604979282/)
[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/gargPriyanshuu)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:garghrithik24x7@gmail.com)

</div>

---

## 👋 About Me

I'm a **Full Stack Developer** who loves building reliable, production-grade backends and clean, fast frontends. I focus on **correctness under concurrency**, **clean layered architecture**, and **systems that are observable and easy to operate**.

- 🔭 Currently building fintech and SaaS-style backends in **Go**
- 🧠 Deep interest in **double-entry accounting, multi-tenancy, ACID transactions and event-driven design**
- 🎨 Comfortable end to end: Go REST APIs ➜ PostgreSQL ➜ Next.js / TypeScript UI
- 🌱 Currently learning **Redux Toolkit** and going deeper into distributed systems
- 🎓 B.Tech in Computer Science & Engineering (AI & ML), AKTU, completed July 2026

---

## 🛠️ Tech Stack

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend**

![Gin](https://img.shields.io/badge/Gin-008ECF?style=for-the-badge&logo=gin&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

**Data, Cloud & DevOps**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_S3_%26_SES-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white)

---

## 🚀 Featured Projects

### 💸 [LedgerX: Digital Wallet & Ledger Engine](https://github.com/Ritik-x/LEDGERX_REPO) · [Live Demo](https://YOUR_LEDGERX_DEMO_URL)
`Go` `PostgreSQL` `Redis` `RabbitMQ` `AWS SES` `OpenTelemetry` `Prometheus`

A fintech backend built on **double-entry accounting**. Every transfer posts balanced debit and credit entries, and balances are **derived from the ledger** instead of a mutable balance column.

- ⚛️ Atomic transfers, deposits and reversals via PostgreSQL transactions; reversals post **compensating entries** to preserve audit history
- 🔁 **Idempotency keys** prevent duplicate transactions on client retries
- 🔐 Mock payment provider with **signature-verified webhooks**; async emails via the **transactional outbox pattern**, RabbitMQ and AWS SES
- 🛡️ 14 REST endpoints secured with **JWT** and **Redis rate limiting** (10 auth / 100 API requests per minute)
- 📈 Instrumented with **OpenTelemetry + Prometheus**, shipped with **GitHub Actions CI** on Render

---

### 🏢 [Multi-Tenant Access Control API](https://github.com/Ritik-x/ACCESS_CONTROL_REPO) · [Live Demo](https://YOUR_ACCESS_CONTROL_DEMO_URL)
`Go` `Gin` `PostgreSQL` `Redis` `Docker`

A SaaS-style authentication and authorization backend with **organization-level data isolation** and **permission-based RBAC** enforced through middleware.

- 🔄 **Refresh-token rotation** with hashed tokens and PostgreSQL `FOR UPDATE` row locking to block concurrent token reuse
- 👥 Team invitations with role assignment and hashed, expiring tokens
- 🧾 Organization-scoped, paginated **audit logs** (user, action, resource, IP) across 11 documented endpoints
- ⚡ **Redis cache-aside** layer for fast permission checks; rate-limited login, register and refresh endpoints
- 🐳 Multi-stage Docker build, deployed on Render

---

### ☁️ DriveX: Cloud File Storage · [Backend](https://github.com/Ritik-x/DRIVEX_BACKEND_REPO) · [Frontend](https://github.com/Ritik-x/DRIVEX_FRONTEND_REPO)
`Go` `Next.js` `TypeScript` `PostgreSQL` `AWS S3` `RabbitMQ`

A Google Drive-style full-stack app with folders, upload and download, search, sharing, and 6 views (My Drive, Recent, Shared, Starred, Search, Trash).

- 📤 **S3 presigned URLs** keep large payloads off the API server; only metadata lives in PostgreSQL
- 🖼️ Thumbnail generation decoupled into a **RabbitMQ worker** so uploads return instantly
- 🗄️ Schema managed through **7 versioned SQL migrations**
- 🧱 Go backend structured into handlers, services and repositories, with Redis middleware and Docker Compose for local development

---

## 💼 Experience

| Role | Company | Period |
|------|---------|--------|
| **Full Stack Developer** | Techy Web Solutions (Remote) | Nov 2025 – Aug 2026 |
| **Frontend Intern** | MAKUNAI Global Technologies (Noida) | Mar 2025 – Apr 2025 |

<details>
<summary><b>Full Stack Developer: Techy Web Solutions</b></summary>
<br/>

- Engineered scalable backend APIs in **Go (Gin)** with a clean layered architecture, using **RabbitMQ** for async messaging and **Redis** for caching
- Architected the frontend of a new SaaS product and built an **AI-powered Playwright automation suite** for continuous accessibility testing
- Revamped the hero section to match Figma designs, enforced cookie-consent compliance, and improved **Core Web Vitals** (LCP and TBT)
- Connected Next.js features to Go REST endpoints end to end, with request validation, consistent error handling and reliable database-backed workflows

</details>

<details>
<summary><b>Frontend Intern: MAKUNAI Global Technologies</b></summary>
<br/>

- Converted Figma designs into responsive, pixel-accurate pages with **Next.js and Tailwind CSS**
- Managed shared state with React state and Context; began learning **Redux Toolkit**
- Built an interactive dashboard with data tables and charts using **Next.js and TypeScript**
- Collaborated with designers and QA in Agile sprints, contributing to bi-weekly releases

</details>

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Ritik-x&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ritik-x&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Ritik-x&theme=tokyonight&hide_border=true" />

</div>

---

## 🤝 Let's Connect

I'm open to **backend / full-stack roles** and interesting engineering collaborations. If you're building something that needs reliable APIs and clean architecture, I'd love to chat.

📫 **Email:** [garghrithik24x7@gmail.com](mailto:garghrithik24x7@gmail.com)
💼 **LinkedIn:** [linkedin.com/in/ritik-garg-604979282](https://www.linkedin.com/in/ritik-garg-604979282/)
🧩 **LeetCode:** [leetcode.com/u/HO4](https://leetcode.com/u/HO4/)
🐦 **X (Twitter):** [x.com/gargPriyanshuu](https://x.com/gargPriyanshuu)

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%" />

</div>
