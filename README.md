# Vinicius Loureiro

**Full-Stack Software Engineer** (backend-strong) · Maceió, Brazil 🇧🇷 · building production SaaS at **THEP (Inovação Sustentável)**

<!-- TYPING (3 SVGs com stagger via ZWSP prefix) -->
<a href="https://git.io/typing-svg" target="_blank">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&duration=4000&pause=1200&color=2DD4BF&center=false&vCenter=true&repeat=true&width=640&height=35&lines=%E2%9A%A1+I+build+production+software%2C+end+to+end" alt="line 1" />
</a>
<br/>
<a href="https://git.io/typing-svg" target="_blank">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&duration=4000&pause=1200&color=2DD4BF&center=false&vCenter=true&repeat=true&width=640&height=35&lines=%E2%80%8B%E2%80%8B%E2%80%8B%E2%80%8B%E2%80%8B%F0%9F%8E%AF+Principal+contributor+on+a+SaaS+live+for+5+municipalities" alt="line 2" />
</a>
<br/>
<a href="https://git.io/typing-svg" target="_blank">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&duration=4000&pause=1200&color=2DD4BF&center=false&vCenter=true&repeat=true&width=640&height=35&lines=%E2%80%8B%E2%80%8B%E2%80%8B%E2%80%8B%E2%80%8B%E2%80%8B%E2%80%8B%E2%80%8B%E2%80%8B%E2%80%8B%F0%9F%A5%8B+Purple+belt+on+and+off+the+mat" alt="line 3" />
</a>

<br/>

<a href="https://www.linkedin.com/in/vsloureiro" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:viniciussloureiro@hotmail.com" target="_blank"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
<img src="https://img.shields.io/badge/Open%20to-international%20relocation%20%26%20remote-2DD4BF?style=flat-square" alt="Open to relocation"/>

---

## About

Full-Stack Software Engineer, strongest on the backend. I build multi-tenant SaaS and own it end to end: domain modeling, data layer, integrations, queues, real-time, and the UI on top. I care about correctness under concurrency (idempotent payment webhooks, atomic stock control, race-safe ledgers), security done properly (hardened Row-Level Security, least privilege), and clean architecture a team can grow into.

Career-changer. 5+ years as an administrative officer at a State Court, a semester studying in Dubai, then a full pivot to software. Two Computer Science degrees in progress (one in English, through University of the People). English: Duolingo English Test 110/160.

I work AI-augmented: I built my own toolkit of AI coding agents (Claude Code skills, subagents, MCP servers) to plan, build, review and ship at the pace of a full team, while keeping the discipline of thousands of automated tests, static analysis at max level, and peer review on every pull request.

Open to international relocation and remote roles worldwide.

## Featured Work

### [THEP EDU](https://github.com/THEP-Inovacao-Sustentavel/edu) · multi-tenant education platform (in production)
Software Developer, **principal contributor (~68% of commits)**. Live for **5 municipalities, ~54 schools and ~6,800 students**.

- Two bounded contexts (school management and adaptive learning) that communicate **only through events**: Domain-Driven Design, an **Outbox Pattern** with idempotent consumers, and **CQRS** read-models.
- Shipped enrollment, grading and official PDF report cards, real-time notifications (WebPush and Reverb), a gamified XP and rank economy, and a **3D student universe in Three.js**.
- Built an observability suite: telemetry, a customer health score, and an automated monthly PDF report per municipality.
- **Stack** Laravel 12 · PHP 8.4 · PostgreSQL (RLS) · Redis · Horizon · Octane · React 19 · Inertia · Three.js. ~7,000 automated tests, PHPStan at max level.

### [Nexus](https://github.com/THEP-Inovacao-Sustentavel/nexus) · internal ERP with a production MCP server
Principal contributor (~69% of commits). Kanban, service desk, sprints, finance with a **double-entry ledger**, and fiscal, in one multi-tenant app.

- Includes a **production MCP server over OAuth2** that exposes the platform to AI agents, reusing the same domain services as the UI with full parity of side effects.
- **Stack** Laravel 12 · Inertia · React 19 · Passport (OAuth2) · Reverb · Octane · PostgreSQL

### [X Loop Store](https://xloop-eyewear-store.vercel.app) · live e-commerce (selling)
Next.js and Supabase. Idempotent payment webhooks via atomic compare-and-swap, server-authoritative checkout, hardened Row-Level Security, atomic stock control.

### [draftcs](https://draftcs.vercel.app) · viral Counter-Strike game, authored solo (live)
Next.js and Supabase. Deterministic match engine calibrated with Monte-Carlo simulation, server-side anti-cheat, tri-lingual (EN/PT/RU), ~170 automated tests.

### [Hilton Loureiro](https://hiltonloureiro.com.br) · official site for a Moto1000GP driver (live)
Next.js and Tailwind. Motion design, computational geometry, technical SEO with JSON-LD.

## Stack

**Backend** Laravel 12 · PHP · PostgreSQL (RLS, PL/pgSQL) · Domain-Driven Design · Outbox Pattern · CQRS · Redis · Horizon · Octane · Reverb · OAuth2 · REST APIs  
**Frontend** React 19 · TypeScript · Next.js · Inertia.js · Tailwind v4 · shadcn/ui · Radix · TanStack Query · Zustand · Jotai · Three.js / React Three Fiber  
**Data & Infra** Supabase · AWS (S3) · Docker · CI/CD (GitHub Actions) · Vercel  
**Quality & AI** Pest · Vitest · Playwright · PHPStan (max) · AI agent orchestration · MCP servers

<details>
<summary><b>Full stack list</b></summary>
<br/>

| Category | Technologies |
|:---------|:-------------|
| **Backend** | Laravel 12, PHP 8.4, Octane, Horizon, Reverb |
| **Architecture** | Domain-Driven Design, Bounded Contexts, Outbox Pattern, CQRS, multi-tenancy |
| **Database** | PostgreSQL, Row-Level Security, PL/pgSQL, Supabase |
| **Frontend Core** | React 19, TypeScript, Tailwind CSS v4, Vite, Next.js |
| **UI Components** | shadcn/ui, Radix UI, Ant Design, Headless UI |
| **State & Data** | Jotai, Zustand, TanStack Query, TanStack Table |
| **Forms** | React Hook Form, Zod |
| **3D & Motion** | Three.js, React Three Fiber, Drei, Framer Motion, GSAP |
| **Real-time** | Reverb, Pusher, Laravel Echo, WebSockets |
| **Auth** | Sanctum, Passport (OAuth2) |
| **Testing** | Pest, Vitest, Playwright, Testing Library |
| **Cloud & DevOps** | AWS (S3), Docker, Vercel, GitHub Actions |
| **AI** | Claude Code (agents, skills, hooks), MCP servers |

</details>

## GitHub

<a href="https://github.com/ViniciusLoureiro67" target="_blank">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ViniciusLoureiro67&theme=tokyonight&hide_border=true&background=0D1117&ring=2DD4BF&fire=2DD4BF&currStreakLabel=2DD4BF&mode=yearly&starting_year=2026"/>
</a>

<a href="https://github.com/ViniciusLoureiro67" target="_blank">
  <img height="195" src="https://github-readme-stats-sigma-azure-31.vercel.app/api?username=ViniciusLoureiro67&show_icons=true&count_private=true&hide_rank=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=2DD4BF&icon_color=2DD4BF&text_color=c9d1d9" />
  <img height="195" src="https://github-readme-stats-sigma-azure-31.vercel.app/api/top-langs/?username=ViniciusLoureiro67&layout=compact&langs_count=8&count_private=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=2DD4BF&text_color=c9d1d9" />
</a>

## Background

|  |  |
|:--|:--|
| 🥋 | **Brazilian Jiu-Jitsu, purple belt.** The mat taught me to drill fundamentals, manage discomfort, and ship under pressure. |
| 🌍 | **Studied in Dubai.** Cross-cultural collaboration, working across timezones, adapting fast, communicating in English. |
| ⚖️ | **5+ years at a State Court.** Structured thinking, careful reading of specs, written communication that lands. |
| 📚 | **Two Computer Science degrees in progress.** Afya and University of the People (USA, online, English). |

## Open to

- **International relocation** and **remote roles worldwide**, starting immediately
- Full-stack or backend roles, full-time or contract
- Reach me on [LinkedIn](https://www.linkedin.com/in/vsloureiro) or by [email](mailto:viniciussloureiro@hotmail.com)

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"/>
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"/>
</picture>
