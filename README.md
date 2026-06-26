# Ashutosh Tripathi

Building tools that give AI agents memory — and the infrastructure that serious teams run on.

## What I Work On

### Smriti
A persistent memory layer for AI coding sessions. Smriti captures what happens during a session — decisions made, patterns discovered, context built — compresses it semantically, and surfaces the right pieces back in future sessions. The goal: an AI coding assistant that actually remembers your codebase, your preferences, and your reasoning over time.

Thinking a lot about identity resolution, knowledge graph structure, and what it means for a tool to "know" a codebase across sessions rather than starting cold every time.

### Avkash — Open-Core HRMS
Open-source HR management platform covering leave, attendance, people directory, org management, policy engine, and Slack integration. Built on Bun, Hono, Drizzle ORM, and Turborepo — designed as a type-safe monorepo where the API contract is the source of truth for both server and client.

Multi-tenant architecture, open core model. The kind of software most companies pay a lot of money for and rarely love.

### Language Server in Rust
Experimenting with building a language server from scratch — LSP internals, incremental parsing, and what responsive developer tooling feels like when you're not fighting latency.

## Previously

Built developer tooling at Godspeed Systems — plugin architectures for auto-generating type-safe endpoints from OpenAPI specs, pluggable data source systems across 15+ integrations, and a YAML-based dynamic form generator. Also built a live collaborative web IDE and a WebRTC/HLS video streaming platform.

## Philosophy

- **Systems over features** — platforms that let others build faster compound over time
- **Type safety at compile time** — catch errors before runtime, always
- **Open source as design discipline** — building in public forces clarity
- **Memory matters** — context that disappears after a session is context lost

## Tech

**Current**
```
Runtime:    Bun · Node.js
HTTP:       Hono
ORM:        Drizzle + PostgreSQL
Auth:       Better Auth
Validation: Zod 4
Infra:      Turborepo, pnpm workspaces, Docker
Systems:    Rust (LSP, parsing)
```

**Previously Deep In**
```
React, Next.js, WebRTC, HLS, Webpack/Vite/ESBuild,
Distributed Tracing, GraphQL, Nx monorepos
```

## Connect

- **LinkedIn:** [linkedin.com/in/itszero8](https://linkedin.com/in/itszero8)
- **Email:** hello@zero8.dev

---

> "The best measure of a developer tool isn't how powerful it is — it's how quickly someone can forget it exists while getting work done."
