# Sergey Kutushev

## Senior Fullstack Developer · Backend-leaning Product Engineer

**TypeScript · Node.js · React · Next.js · PostgreSQL · ClickHouse · Redis · Kubernetes**

I build production systems end to end — from domain models, APIs, and data flows to frontend, testing, infrastructure, and rollout.

[Portfolio](https://sskutushev.github.io/sskutushev-site/) · [Portfolio source](https://github.com/Sskutushev/sskutushev-site) · [Architecture](https://github.com/Sskutushev/sskutushev-site/blob/main/docs/architecture/overview.md) · [Telegram](https://t.me/sskutushev) · [Email](mailto:sskutushev@gmail.com)

## Profile

Senior Fullstack Developer with a backend-leaning focus and 5+ years of commercial software development.

I work across the full product lifecycle: architecture, backend services, APIs, databases, frontend, testing, infrastructure, production rollout, and post-deploy validation.

I currently build B2B and B2C products for a UAE real-estate platform with **230,000+ active listings**. The product surface includes paid access, property analytics, owner workflows, search, valuation, and data-intensive interfaces.

My strongest areas are system design, backend architecture, performance, application security, data-intensive products, and end-to-end product ownership.

## Selected production work

Most of my current commercial work is closed source. Selected systems and outcomes:

- **B2B access and monetization** — designed backend architecture for plans, entitlements, access control, charging and refunds, including server-side masking of sensitive data.
- **Building View** — delivered an investor-facing product end to end: backend, ClickHouse analytics, API, tariff model, frontend and UI, PDF generation, migrations, CronJob, and production validation.
- **My Home** — built an owner journey from property search and valuation to ownership verification, Stripe checkout, entitlements, and a protected per-unit workspace.
- **Analytics** — moved part of the analytics layer from Looker to TypeScript and SQL, reducing BigQuery requests by approximately **65%** in internal measurements.
- **Image search** — built a property-search pipeline with Redis, Wasabi/S3, CLIP embeddings, Qdrant, and BigQuery.
- **Frontend performance** — resolved an iPhone production crash by reducing the initial render from roughly **994 cards / 119,000 DOM nodes** to **45–50 cards** through virtualization and dynamic measurement.
- **Resilience and delivery** — implemented Redis stale-while-revalidate caching, in-flight deduplication, controlled fallbacks, and Playwright E2E infrastructure; participate in Kubernetes-based rollout and post-deploy validation.

## Engineering stack

| Area | Technologies |
| --- | --- |
| Backend | TypeScript, Node.js, Express, REST API, Python, FastAPI |
| Frontend | React 18/19, Next.js, TypeScript |
| Data | PostgreSQL, CockroachDB, ClickHouse, BigQuery, Redis |
| Search and storage | Qdrant, CLIP, Wasabi/S3 |
| Infrastructure | Docker, Kubernetes, CI/CD, CronJobs |
| Testing | Playwright, Vitest |
| Additional | Go, Rust, MQL, WebSocket |

## Portfolio and public work

### [sskutushev-site](https://github.com/Sskutushev/sskutushev-site) — production-shaped engineering portfolio

A working vertical slice rather than a static mock:

```text
React / React Three Fiber
        ↓ GraphQL
NestJS → Prisma → CockroachDB
        ↘ Redis
        ↘ S3-compatible storage
```

The repository includes explicit architecture decisions, a versioned design system, risk-based testing, performance budgets, security boundaries, resilient fallback behavior, and an ordered CI verification chain.

[Live demo](https://sskutushev.github.io/sskutushev-site/) · [Source](https://github.com/Sskutushev/sskutushev-site) · [Architecture overview](https://github.com/Sskutushev/sskutushev-site/blob/main/docs/architecture/overview.md)

## Engineering background

Previously built algorithmic trading systems for crypto, FX, metals, and commodities using Go, Rust, Python, and MQL. The work included real-time and historical data processing, WebSocket integrations, codebases of up to one million lines, and investor-facing TypeScript/React interfaces.

Before software engineering, I spent almost six years at **Coca-Cola HBC** in key-account management and team leadership. That background strongly influences how I connect engineering decisions with business rules, operational constraints, and measurable outcomes.

## Contact

- Portfolio: [sskutushev.github.io/sskutushev-site](https://sskutushev.github.io/sskutushev-site/)
- GitHub: [github.com/Sskutushev](https://github.com/Sskutushev)
- Telegram: [@sskutushev](https://t.me/sskutushev)
- Email: [sskutushev@gmail.com](mailto:sskutushev@gmail.com)
