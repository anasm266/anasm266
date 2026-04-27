# Anas

I build developer tools, security workflows, and real-time web apps that are meant to be used: CLIs, GitHub Actions, npm packages, backend systems, and live multiplayer products.

Currently focused on TypeScript tooling, supply-chain security, Rust CLIs, and production-style backend systems.

## Shipped Projects

| Project | What makes it interesting | Stack / links |
| --- | --- | --- |
| [typing-race](https://github.com/anasm266/typing-race) | Live 2-player typing race built around share-link multiplayer, low-latency WebSocket sync, reconnect handling, analytics, monitoring, and load testing. | Cloudflare Workers, Durable Objects, D1, React, k6 - [Live app](https://typing-race.pages.dev) |
| [any-map](https://github.com/anasm266/any-map) | Static flow analysis for TypeScript `any` types. Traces where type erosion starts, how it spreads through a codebase, and which fixes have the biggest blast-radius reduction. | TypeScript Compiler API, graph algorithms, CLI, npm - [npm](https://www.npmjs.com/package/any-map), 246 last-month downloads |
| [installsentry](https://github.com/anasm266/installsentry) | Supply-chain visibility for npm installs: traces lifecycle scripts, file/network access, and canary secret reads, then maps findings onto the dependency graph with HTML and SARIF reports. | TypeScript, Node.js, SARIF, CI - [npm](https://www.npmjs.com/package/installsentry), 236 last-month downloads |
| [apibump](https://github.com/anasm266/apibump) | Rust CLI and GitHub Action that checks Python public API changes in pull requests and recommends the right SemVer bump before merge. | Rust, Python, GitHub Actions, SemVer - [action](https://github.com/anasm266/apibump) |
| [sentinelflow](https://github.com/anasm266/sentinelflow) | Dependency-risk control plane for GitHub repositories with policy evaluation, audit logs, background jobs, GitHub checks, signed webhooks, and delivery replay. | Fastify, PostgreSQL, React, GitHub App - [demo](https://sentinelflow-api.onrender.com), [docs](https://sentinelflow-api.onrender.com/docs) |

## Open Source

- Merged fix in [typescript-eslint](https://github.com/typescript-eslint/typescript-eslint/pull/12278) for `no-unnecessary-type-assertion` false positives.
- Additional active PRs in [typescript-eslint](https://github.com/typescript-eslint/typescript-eslint/pulls?q=is%3Apr+author%3Aanasm266).
- Open PR in [refined-github](https://github.com/refined-github/refined-github/pull/9280) restoring `esc-to-cancel` behavior on pull requests.

## Stack

`TypeScript` `Node.js` `React` `Fastify` `PostgreSQL` `Rust` `Cloudflare Workers` `Durable Objects` `Vitest` `Playwright` `GitHub Actions`

## Current Focus

- developer tools and static analysis
- backend systems with durable jobs and real persistence
- security-oriented tooling around npm and dependency workflows
- open-source contributions in large TypeScript codebases
