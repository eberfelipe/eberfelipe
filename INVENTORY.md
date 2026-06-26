# Eber Felipe — Engineering Inventory

> Source of truth for the GitHub profile and professional positioning.
> The profile `README.md` is derived from this file. Keep this updated first.

## 1. Identity & positioning

- **Name:** Eber Felipe Araújo
- **Role:** Lead & Software Engineer
- **GitHub:** [@eberfelipe](https://github.com/eberfelipe)
- **Positioning:** one unified technical identity that fuses the stacks and
  knowledge from employed work and personal projects. The profile is **not**
  about any single employer. Written in English. Education is background flavor,
  not a second LinkedIn.

## 2. Capability domains

| Domain | What it means | Core stack |
|---|---|---|
| **Data platforms** | ETL/ELK ingestion, Postgres modeling, observability | Python · PostgreSQL · ELK · Docker |
| **Multi-tenant SaaS** | tenant isolation, RLS, auth, quotas | Go · Postgres/RLS · SuperTokens · React |
| **Messaging & automation** | WhatsApp at scale, inbound bots, scraping | Chatwoot · Playwright |
| **AI agents** | reason engines, message composition, tracing | OpenAI · Langfuse |

## 3. Stack matrix (evidence-based, from a 54-repo sweep)

- **Languages:** Go (primary backend), Python, TypeScript/JavaScript, C#, SQL, Shell
- **Backend:** Go services, FastAPI, Node/Express
- **Frontend:** React, Next.js
- **Data:** PostgreSQL/Supabase (RLS, multi-tenant), ELK/Elastic Stack, ETL, ML
- **Infra:** Docker, Linux VPS (Hostinger), Railway, CI/CD
- **Auth:** SuperTokens
- **Automation / scraping:** Playwright (async), uv
- **AI:** OpenAI (reason engines, message composition), Langfuse, agent design
- **Messaging:** WhatsApp (Chatwoot, multi-provider)

## 4. Work & products

> Domain: a direct-sales franchise ecosystem (Hinode). Most of this is
> **private / proprietary** — represented here as capability, not linked.

### SmartBI — data / BI platform
- ETL Nexaas/Hinode → Supabase, containerized, with observability
- Dashboard (TypeScript)
- AI reengagement agent (OpenAI reason engine, deterministic decisioning)
- Inventory ML
- Mass validation of 440k+ records via async Playwright

### SmartZap — multi-tenant WhatsApp campaign platform
- Go + SuperTokens + Postgres/RLS + React
- Dispatcher (Go) via Chatwoot — pacing, rate limiting, anti-spam, delivery reconciliation
- Inbound bot (Chatwoot → LLM)
- Tenant onboarding panel (Next.js + FastAPI)

### LiderHub — CRM + WhatsApp Business for network leaders
- FastAPI + Supabase + React

> Note: `AstraOnlineWeb/astracampaign` was studied as a **reference fork** while
> building SmartZap — not own work; excluded from the public showcase.

## 5. Public repositories (curated)

- **OSS contribution (recorded, not featured):** PR to [`rios0rios0/pipelines`](https://github.com/rios0rios0/pipelines)
  (CycloneDX BOM `metadata.component.type` fix) — the one verifiable public contribution.
  Dropped from the README's public face: a single-item section read as too thin.
- **Profile repo:** `eberfelipe/eberfelipe` (this README).
- **Study forks (not authored — do not feature):** `astracampaign`, `claude-agents`, `pipelines`.
- **Archive candidates** (bootcamp / practice, 2023–24): `RocketSeat-Projeto01`,
  `Projetos_CuboAcademy`, `practicingVariables`, `logicWithJS`, `arraysAndLoops`,
  `HackerRankChallenges`, `Objects_Manipulation`, `working_With_Functions`,
  `First_Server`, `calculatorUsingExpress`, `GamePlayerRotationAPI`,
  `propertyConsultation`, `firstApi`, `costOfShipping`, `ToDoListApi`,
  `Challenge02_RocketSeat`, `DesafioM01`, `pdv_api`, `deploy_api_pdv`.
- **Keep — decide case by case:** `ClubConnect` (TS), `PersonalFinanceApp` (C#),
  `CSSP_Niagara` (school project), `Uipath_Azure_API`.

## 6. Education & background

- **Computer Engineering** — UAB (Universidade Aberta, Portugal) — in progress
- **Computer Programming** — Niagara College (Canada)
- Bootcamps: CuboAcademy, RocketSeat

## 7. Repo housekeeping plan

- **Pinned repos (manual — GitHub has no pin API):** public originals are thin, so
  pinning has limited upside today. Best near-term lever is the README rewrite plus
  archiving the bootcamp repos so the "Popular repositories" block stops showing
  practice code. Future: open-source a sanitized slice of real work to earn a
  genuine pinned original.
- **Archive:** the §5 archive candidates, via `gh repo archive` (reversible).
- **Drop the misleading widgets:** the github-readme-stats grade card (shows
  "grade C / 9 commits" while real activity is 1,691 + 333 private) and the
  Python-98% language card — both undersell because the strong work is private.
- **Personality kept:** the "no no" GIF, LinkedIn + Instagram badges, the casual
  voice. Spotify widget removed (was broken/offline). Added a contribution-streak
  card and an activity-graph "code timeline" that reflect real activity (incl. private).
