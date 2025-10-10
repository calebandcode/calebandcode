<!-- Profile Header -->
<div align="center">
  <h1>Caleb Akomaye</h1>
  <p>
    Software Engineer · Backend & Desktop<br/>
    Node/TypeScript · Postgres · Docker · React/Next.js · Tauri/Rust · Python · Go
  </p>

  <!-- Badges -->
  <p>
    <a href="mailto:calebakomaye@outlook.com">
      <img alt="Email" src="https://img.shields.io/badge/Email-calebakomaye%40outlook.com-0A66C2?style=for-the-badge&logo=microsoft-outlook&logoColor=white">
    </a>
    <a href="https://www.linkedin.com/in/caleb-akomaye-71a03329a/">
      <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-View_Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
    </a>
    <a href="https://github.com/calebandcode">
      <img alt="GitHub" src="https://img.shields.io/badge/GitHub-@calebandcode-181717?style=for-the-badge&logo=github&logoColor=white">
    </a>
  </p>
</div>

---

## 👋 About
I build small, well-instrumented systems with clear data models and predictable latency.  
Most of my work centers on **Node/TypeScript** backends with **Postgres/Redis**, **Python/Go** for services and tooling, and **Tauri/Rust** for local-first desktop apps. When needed, I ship **React/Next.js** UIs.

- Focus areas: reliability (idempotency, safe delete flows, pagination), performance, maintainable DX.
- Currently: polishing **White Space** (local-first disk cleanup) and packaging signed desktop releases.

---

## 🧰 Skills (at a glance)

<p>
  <!-- Languages -->
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white&style=flat" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000&style=flat" />
  <img src="https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white&style=flat" />
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat" />
  <img src="https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white&style=flat" />
  <img src="https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white&style=flat" />
  <!-- Platforms/Frameworks -->
  <img src="https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white&style=flat" />
  <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=000&style=flat" />
  <img src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white&style=flat" />
  <img src="https://img.shields.io/badge/Tauri-24C8DB?logo=tauri&logoColor=000&style=flat" />
  <!-- Data/Infra -->
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white&style=flat" />
  <img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white&style=flat" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white&style=flat" />
  <img src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white&style=flat" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=flat" />
</p>

**Languages:** TypeScript/JavaScript, **Python**, **Go**, Rust, SQL  
**Backend:** Node.js (Express/Nest/Fastify), REST/GraphQL, auth (JWT/OAuth), queues, caching  
**Services/Tools:** Python (FastAPI/Scripts), Go (CLI/services, concurrency), Bash  
**Databases:** PostgreSQL (indexes, EXPLAIN, migrations), Redis, MongoDB; SQLite for desktop  
**Desktop:** Tauri 2 (Rust + Vite/React), packaging, auto-updates  
**Frontend:** React, Next.js (App Router), Tailwind  
**Infra/Quality:** Docker, GitHub Actions, Jest/Playwright, logging/metrics

---

## 📌 Selected Projects

### 1) White Space — Local-first disk cleanup (Tauri/Rust)
Local-first desktop app that identifies duplicate/clutter files, stages them safely, and frees space with a **7-day cooling-off** + **Undo**.

- Pipeline: size → partial **SHA-1** (first 256KB) → full SHA-1; dry-run previews and explainable actions  
- Data: **SQLite (WAL)**, migrations, actions/audit log, weekly totals  
- UX: calm UI, buckets (screenshots, big downloads, old desktop), progress & space meter  
- Repo: **https://github.com/calebandcode/white-space**
  
<p>
  <a href="https://github.com/calebandcode/white-space/releases">
    <img src="https://img.shields.io/badge/Download-Releases-2ea44f?style=flat&logo=github" alt="Releases">
  </a>
  <a href="https://github.com/calebandcode/white-space">
    <img src="https://img.shields.io/github/stars/calebandcode/white-space?style=social" alt="Stars">
  </a>
</p>

---


## 📬 Contact
- Email: **calebakomaye@outlook.com**  
- GitHub: **@calebandcode**

<sub>Profile kept concise. Individual repos contain setup, diagrams, and screenshots.</sub>
