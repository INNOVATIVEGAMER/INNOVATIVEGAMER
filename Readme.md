# Prasad Patewar

**Full-stack engineer, 4+ years across early-stage startups, now co-creator of an
open-source design system.** I take ownership of whole systems rather than slices:
the architecture, the delivery, the standards a team builds to, and the results once
they are live. Drawn to complex problems, and to solving them across product, design
and engineering with architecture that is sound from the start and scales.

Based in Bengaluru, India. [LinkedIn][linkedin] · [Nexus Labs][nexuslabs] · [Email][email]

---

## What I'm building

### [nxds][nxds] &nbsp;·&nbsp; [`@nxds/core`][npm] ![npm](https://img.shields.io/npm/v/@nxds/core?style=flat-square&color=CB3837&logo=npm&logoColor=white)

Co-creator, at Nexus Labs. An open-source theme engine and design system: one
appearance object sets brand color, surface tone, density, corners, shadows and dark
mode across 500+ tokens, and 70+ copy-and-own React components on Radix UI follow it
with no change to component code. [Source on GitHub][nxds-repo].

- **A core with no framework in it.** The engine imports no framework and touches no
  DOM. One function derives OKLCH palettes, picks every surface shade and checks each
  text and background pair for APCA contrast in CI. It writes the default theme at
  build time and re-themes live in the browser, so dark mode cannot drift from light,
  and a new framework is a binding rather than a second design system. React and Vue
  today.
- **Adopted beside an existing stack.** Every class and variable is namespaced
  (`nx:`, `--nx-`), so nxds installs next to MUI, shadcn/ui, Chakra UI, Mantine,
  Ant Design, Bootstrap or plain Tailwind and is adopted one component at a time, with
  an integration guide and example app for each path.
- **The stories are the test suite.** 1,000+ Storybook stories with interaction,
  accessibility and contrast checks ship with every component and publish as the live
  catalog.
- **Built for AI agents.** `nxds-cli` (`init`, `add`, `--json`, `--dry-run`), every
  docs page served as Markdown with `llms.txt`, Claude Code skills, and a Claude
  Design export built on every release.
- Changesets versioning and automated npm publishing through GitHub Actions.

### [Context Engine][context-engine]

Lead maintainer. An MCP server that stops AI assistants hallucinating props against a
custom component library. In active development.

- Pulls component metadata straight from source with `react-docgen` and `ts-morph`,
  enriches it through an LLM pass, and serves it to Claude, Cursor and Copilot over MCP.
- Hono API on Postgres and pgvector for semantic component search, split into core,
  db and server packages.

---

## What I built and sold

### Examlly &nbsp;·&nbsp; Co-founder and CTO

An AI question-paper platform for NEET and JEE prep, architected as a B2B product for
institutes and a B2C app for individual teachers off one core. I built it end to end,
then the business and technology were sold in a one-time deal to a coaching center
franchise operating across Maharashtra, which now runs and maintains the platform as
its own. Closed source.

- 700+ PRs across 8 services, 12 packages and 29 job queues in one TypeScript
  monorepo (Next.js, Hono, BullMQ).
- A scanned paper becomes a tagged, searchable question bank via Mathpix OCR, per-page
  LLM structuring and RDKit for chemistry, behind one provider layer over Anthropic,
  Gemini, OpenAI, Azure and Mistral, with cost tracking and failover.
- An 87-table multi-tenant Postgres schema (Drizzle, Supabase RLS, 210 forward-only
  migrations) that RBAC, billing, attendance and timetabling are all built on.
- Paper production front to back: LaTeX diagram compilation, PDF and Word export,
  jumbled sets, and OMR scanning that grades offline exams into per-student analytics.
- Set the engineering standards, then automated them: 18 repo rules, 13 skills,
  6 subagents and 10 commands running issue to implementation to review, plus a
  self-hosted MCP docs server. Ran it in production with preprod and prod CI, Sentry,
  OpenTelemetry and k6 load tests.

---

## Where I've worked

| Role | Company | When |
| ---- | ------- | ---- |
| Co-creator | [Nexus Labs][nexuslabs] | Nov 2025 to present |
| Co-founder and CTO | Examlly | Mar 2026 to Sept 2026 |
| Founding Engineer | [Vectorshift][vectorshift] (YC) | Sept 2024 to Nov 2025 |
| Founding Engineer | [Superleap][superleap] | May 2024 to Sept 2024 |
| Software Developer | [Bytelearn][bytelearn] | Jan 2023 to May 2024 |
| Software Developer Intern | [Bytelearn][bytelearn] | Jan 2022 to Sept 2022 |

At Vectorshift I architected and shipped Agentic Chat front to back, built the design
system that became the product's frontend foundation, and led the rewrite of AI Forms,
AI Chats and No-Code off the legacy interface, lifting weekly active users by 80%.
I also designed the onboarding flow behind early B2C adoption and stood up PostHog
analytics on user dropoff.

Design systems run through every role: a react-redux component library in Storybook
at Bytelearn, the Storybook design system Superleap's whole app was assembled from,
the one that became Vectorshift's frontend foundation, and now nxds.

B.Tech in Information Technology, IIIT Sonepat, 2019 to 2023.

---

## Stack

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Radix UI](https://img.shields.io/badge/-Radix_UI-161618?style=flat-square&logo=radixui&logoColor=white)
![Storybook](https://img.shields.io/badge/-Storybook-FF4785?style=flat-square&logo=storybook&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-5FA04E?style=flat-square&logo=node.js&logoColor=white)
![Hono](https://img.shields.io/badge/-Hono-E36002?style=flat-square&logo=hono&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Drizzle](https://img.shields.io/badge/-Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Turborepo](https://img.shields.io/badge/-Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white)
![pnpm](https://img.shields.io/badge/-pnpm-F69220?style=flat-square&logo=pnpm&logoColor=white)
![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Vitest](https://img.shields.io/badge/-Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![MCP](https://img.shields.io/badge/-MCP-000000?style=flat-square&logo=anthropic&logoColor=white)
![Claude Code](https://img.shields.io/badge/-Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white)

**Design systems:** design tokens (DTCG), theming engines, OKLCH color, APCA contrast,
CVA, Storybook interaction tests.

**AI engineering:** Anthropic, OpenAI and Gemini SDKs, MCP servers, structured outputs,
prompt and schema design.

**AI tooling:** Claude Code, Codex, OpenCode, Cursor, subagents, skills, rules, hooks,
custom commands.

**Also:** SQL, C++, shadcn/ui, TanStack Query, Zustand, React Hook Form, BullMQ,
MongoDB, Zod, Railway, Changesets, GitHub Actions, Sentry, OpenTelemetry, k6.

[linkedin]: https://www.linkedin.com/in/prasad-patewar-b9066b204/
[email]: mailto:prasadpatewar39@gmail.com
[nexuslabs]: https://github.com/nexuslabs-ai
[nxds]: https://nxds.dev
[nxds-repo]: https://github.com/nexuslabs-ai/nxds
[npm]: https://www.npmjs.com/package/@nxds/core
[context-engine]: https://github.com/nexuslabs-ai/context-engine
[vectorshift]: https://vectorshift.ai/
[superleap]: https://www.superleap.com/
[bytelearn]: https://www.bytelearn.com/
