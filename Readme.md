# Prasad Patewar

**Full-stack engineer, 3+ years, currently co-founder and CTO.** I take ownership of
whole systems rather than slices: the architecture, the delivery, the standards a
team builds to, and the results once they are live.

Based in Bengaluru, India. [LinkedIn][linkedin] · [Nexus Labs][nexuslabs] · [Email][email]

---

## What I'm building

### [Nexus Design System][nexus] &nbsp;·&nbsp; [`@nexus_ds/core`][npm] ![npm](https://img.shields.io/npm/v/@nexus_ds/core?style=flat-square&color=CB3837&logo=npm&logoColor=white)

Lead maintainer. A design system built as a **portable token engine** rather than a
component library, so one source of theme values can be adopted by any framework,
or by an app that already has its own CSS.

- The core engine imports no framework and touches no DOM. It is a pure function
  from appearance state to token values, which makes Vue, Svelte or React Native a
  binding rather than a second design system. React is the first, at 63 components.
- Every utility and variable ships behind an `nx:` namespace, so it installs beside
  an existing Tailwind config with two CSS imports and no config merge. That merge is
  usually the thing that blocks adoption outright.
- Components are vendored into the consuming app, so a team owns and edits the source
  while the token layer stays a versioned package. Ownership without four apps quietly
  drifting into four different themes.
- Changesets versioning, automated npm publishing via GitHub Actions, and an
  external-consumer bed that proves the install path on every change.

### [Context Engine][context-engine]

Lead maintainer. An MCP server that stops AI assistants hallucinating props against a
custom component library.

- Pulls component metadata straight from source with `react-docgen` and `ts-morph`,
  enriches it through an LLM pass, and serves it to Claude, Cursor and Copilot over MCP.
- Hono API on Postgres and pgvector for semantic component search, split into core,
  db and server packages.

### Examlly

Co-founder and CTO. An AI question-paper platform for NEET and JEE prep, architected
as a B2B product for institutes and a B2C app for individual teachers off one core.
Closed source.

- 700+ PRs across 8 services, 12 packages and 29 job queues in one TypeScript
  monorepo (Next.js, Hono, BullMQ).
- A scanned paper becomes a tagged, searchable question bank via Mathpix OCR, per-page
  LLM structuring and RDKit for chemistry, behind one provider layer over Anthropic,
  Gemini, OpenAI, Azure and Mistral, with cost tracking and failover.
- An 87-table multi-tenant Postgres schema (Drizzle, Supabase RLS, 210 forward-only
  migrations) carrying RBAC, billing, attendance and timetabling.
- Paper production front to back: LaTeX diagram compilation, PDF and Word export,
  jumbled sets, and OMR scanning that grades offline exams into per-student analytics.
- Set the engineering standards, then automated them: 18 repo rules, 13 skills,
  6 subagents and 10 commands running the loop from issue to implementation to review,
  plus a self-hosted MCP docs server. It is how two people shipped at this rate.

---

## Where I've worked

| Role | Company | When |
| ---- | ------- | ---- |
| Co-founder and CTO | Examlly | Nov 2025 to present |
| Founding Engineer | [Vectorshift][vectorshift] (YC) | Sept 2024 to Nov 2025 |
| Founding Engineer | [Superleap][superleap] | May 2024 to Sept 2024 |
| Software Developer | [Bytelearn][bytelearn] | Jan 2023 to May 2024 |
| Software Developer Intern | [Bytelearn][bytelearn] | Jan 2022 to Sept 2022 |

At Vectorshift I architected and shipped Agentic Chat front to back, built the design
system that became the product's frontend foundation, and led the rewrite of AI Forms,
AI Chats and No-Code off the legacy interface, lifting weekly active users by 80%.

B.Tech in Information Technology, IIIT Sonepat, 2019 to 2023.

---

## Stack

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-5FA04E?style=flat-square&logo=node.js&logoColor=white)
![Hono](https://img.shields.io/badge/-Hono-E36002?style=flat-square&logo=hono&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Drizzle](https://img.shields.io/badge/-Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Turborepo](https://img.shields.io/badge/-Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white)
![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Vitest](https://img.shields.io/badge/-Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![MCP](https://img.shields.io/badge/-MCP-000000?style=flat-square&logo=anthropic&logoColor=white)

**Also:** SQL, C++, Radix UI, shadcn/ui, TanStack Query, Zustand, React Hook Form,
Storybook, BullMQ, MongoDB, Zod, Railway, GitHub Actions, Sentry, OpenTelemetry, k6.
Anthropic, OpenAI and Gemini SDKs, MCP servers, structured outputs, prompt and schema design.

[linkedin]: https://www.linkedin.com/in/prasad-patewar-b9066b204/
[email]: mailto:prasadpatewar39@gmail.com
[nexuslabs]: https://github.com/nexuslabs-ai
[nexus]: https://github.com/nexuslabs-ai/nexus
[context-engine]: https://github.com/nexuslabs-ai/context-engine
[npm]: https://www.npmjs.com/package/@nexus_ds/core
[vectorshift]: https://vectorshift.ai/
[superleap]: https://www.superleap.com/
[bytelearn]: https://www.bytelearn.com/
