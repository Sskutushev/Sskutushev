<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,100:302b63&height=220&section=header&text=Sergey%20Kutushev&fontColor=ffffff&fontSize=45&animation=fadeIn&fontAlignY=35" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React_18/19-0f0c29?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/TypeScript-302b63?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-24243e?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-302b63?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-0f0c29?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind-0f0c29?style=for-the-badge&logo=tailwindcss&logoColor=06B6D4" />
  <img src="https://img.shields.io/badge/Zustand-302b63?style=for-the-badge&logo=react&logoColor=white" />
</p>

---

# Fullstack Developer · Frontend-focused

> Building production-grade B2B/B2C platforms — from UI architecture to backend services and data pipelines.
> React + TypeScript on the front, Node.js + PostgreSQL/BigQuery on the back.

---

### What I actually do

I work on a real-estate analytics platform for the UAE market (230k+ listings, B2B + B2C).
My scope covers the full stack: frontend architecture, backend features, DB queries, infrastructure integrations, and E2E testing.

**Selected shipped work (commercial, closed source):**

- **Search & listing performance** — replaced all-at-once render of 200k cards with virtualization + pagination. Load reduction: **~75%**
- **Photo CDN pipeline** — implemented smart CDN layer with cascading fallback (CDN → original URL → placeholder). Zero white-screen on CDN failure
- **Photo search pipeline** — built full pipeline: parser → Redis → Wasabi → embedding → Qdrant, with BigQuery for final card fetch by adId
- **Analytics migration** — moved dashboards from Looker to internal TS+SQL solution. BigQuery request reduction: **~65%**
- **Discount & promo system** — backend + frontend for time-decay discount logic (5–30%, 3–12 month periods), wired to CRM and CockroachDB
- **Impersonation system** — managers can inspect broker accounts from their own session; full auth flow, DB, and audit trail
- **Not-found UX** — classified listing states (archived / access_denied / not_found) on backend, delivered targeted CTA to frontend instead of generic 404
- **Valuation modal** — market position analytics workspace: price curve, ask/bid ladders, comparable units table, deal scoring
- **Wazzup integration checker** — Kubernetes CronJob that monitors WhatsApp integration health and pushes alerts to Telegram bot
- **E2E testing setup** — Playwright config from scratch: multi-server (frontend + backend), API auth, cross-browser, CI-ready
- **Global state migration** — refactored app-wide state from Context API to Zustand across full monorepo
- **PropertyController v2** — extracted business logic from legacy controller into clean service layer, added V2 API routes with full parity validation
- **Analytics dashboards** — fixed data discrepancies across DLD, Ejari, R&D, Top Agency, Renovation Villas dashboards vs Looker reference

---

### Stack

**Frontend**
React 18/19 · Next.js (App Router) · TypeScript (strict) · Zustand · Redux Toolkit · Tailwind CSS · Framer Motion · TanStack Virtual · Playwright

**Backend**
Node.js · PHP · PostgreSQL · CockroachDB · BigQuery · Redis · Qdrant · Wasabi S3

**Infra & tooling**
Kubernetes · CronJobs · GitHub Actions · Vite · Vitest · ESLint · Docker

---

### Open source & pet projects

#### TOT Platform
*Commercial fintech startup — built full frontend architecture from scratch*
Stack: React · TypeScript · Tailwind · UNA.CMS API

#### DexFlow / EcoChain / DexSafe
*Web3 / DeFi experiments — wallet UI, token dashboards, motion-heavy interfaces*
Stack: React · Ethers.js · Framer Motion · Zustand

#### Vanilla landing stack
*Semantic cross-browser HTML/CSS/JS layouts for traffic arbitrage — single-file, CRM-wired, PHP backend*

---

### Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Sskutushev&show_icons=true&theme=tokyonight&cache_seconds=1800" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sskutushev&layout=compact&theme=tokyonight&cache_seconds=1800" width="40%" />
</p>

---

### Background

- Ex-Senior KAM at **Coca-Cola HBC** — I think in KPIs, business logic, and user outcomes, not just code
- FinTech & trading systems experience — dashboards, real-time data, financial domain knowledge
- I document everything: architecture decisions, feature reports, migration plans

---

### Connect

<p align="left">
  <a href="https://t.me/sskutushev">
    <img src="https://img.shields.io/badge/Telegram-0088cc?style=for-the-badge&logo=telegram&logoColor=white"/>
  </a>
  <a href="mailto:sskutushev@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.sskutushev.site/">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=googlechrome&logoColor=white"/>
  </a>
</p>
```ts
const sskutushev = {
  role: "Fullstack Developer, frontend-focused",
  stack: ["React", "TypeScript", "Next.js", "Node.js", "PostgreSQL", "BigQuery"],
  infra: ["Kubernetes", "Redis", "Qdrant", "Wasabi", "CDN"],
  approach: "Ship fast, document well, optimize with numbers",
  motto: "If you can't measure it, you didn't improve it"
};
```
