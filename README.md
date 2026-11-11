# Michael McShinsky

[![GitHub followers](https://img.shields.io/github/followers/michaelmcshinsky?style=flat-square&logo=github)](https://github.com/michaelmcshinsky)
[![Website](https://img.shields.io/badge/website-mcshinsky.net-0A84FF?style=flat-square&logo=google-chrome)](https://mcshinsky.net)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/michaelmcshinsky)
[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/mikemcshinsky)
[![DEV](https://img.shields.io/badge/DEV-0A0A0A?style=flat-square&logo=dev.to&logoColor=white)](https://dev.to/mikemcshinsky)

**Senior Software Engineer** — Developer tools, APIs, reliable systems, practical automation.  
University of Utah Adjunct Instructor (CS) • Former institutional crypto/fintech SDK lead.

---

## 🎯 What I'm Shipping Now

| Project | Status | Description |
|---------|--------|-------------|
| **[Slipstream UI](https://github.com/michaelmcshinsky/slipstream-ui)** | 🚧 Active | AI-first React component library with machine-readable manifests, MCP server, and shadcn-compatible registry |
| **[Utah Esports](https://github.com/michaelmcshinsky/utah-esports)** | 🚧 Active | Live tournament/community directory for Utah gamers — freshness-enforced, provenance-tracked (utahesports.net) |
| **[react-starter](https://github.com/michaelmcshinsky/react-starter)** | ✅ Stable | Production-ready Vite + React 19 + Tailwind 4 + TanStack Query + Vitest + Storybook starter |
| **[surgejs-sdk](https://github.com/michaelmcshinsky/surgejs-sdk)** | ✅ Stable | Typed, zero-runtime-dep TypeScript SDK for Surge.sh with streaming publish & upload dedupe |

---

## 🧠 Architecture Principles

> These guide every project I build. Full case studies on [mcshinsky.net/work](https://mcshinsky.net/work/).

- **Simplicity as a constraint** — Prefer simple solutions that are easy to operate and change
- **Explicit assumptions** — Make tradeoffs visible; document why, not just what
- **Reliability as product** — Security, observability, and graceful degradation are features, not afterthoughts
- **Automation with guardrails** — Automate repetitive work when the result is safer and clearer
- **Outcomes over complexity** — Optimize for useful outcomes, not unnecessary cleverness

---

## 📦 Selected Repositories

### Production-Ready Libraries & SDKs
| Repo | Stars | npm | Description |
|------|-------|-----|-------------|
| **[surgejs-sdk](https://github.com/michaelmcshinsky/surgejs-sdk)** | ![Stars](https://img.shields.io/github/stars/michaelmcshinsky/surgejs-sdk?style=social) | ![npm](https://img.shields.io/npm/v/surgejs-sdk?style=flat-square) ![dl](https://img.shields.io/npm/dm/surgejs-sdk?style=flat-square&label=dl%2Fmo) | Complete typed Surge.sh API client + streaming publisher with upload dedupe, now with a CLI and a GitHub Action |
| **[slipstream-ui](https://github.com/michaelmcshinsky/slipstream-ui)** | ![Stars](https://img.shields.io/github/stars/michaelmcshinsky/slipstream-ui?style=social) | ![npm](https://img.shields.io/npm/v/@slipstream-ui/core?style=flat-square&label=core) ![dl](https://img.shields.io/npm/dm/@slipstream-ui/core?style=flat-square&label=dl%2Fmo) | AI-native component library: 8 published packages, COMPONENT_MANIFEST specs, MCP server, shadcn registry, live docs at [slipstreamui.com](https://slipstreamui.com) |

### Starters & Reference Implementations
| Repo | Stars | Description |
|------|-------|-------------|
| **[react-starter](https://github.com/michaelmcshinsky/react-starter)** | ![Stars](https://img.shields.io/github/stars/michaelmcshinsky/react-starter?style=social) | Opinionated React 19 starter: feature folders, Zod env, lazy routes, error boundaries |
| **[express-react-passport-jwt](https://github.com/michaelmcshinsky/express-react-passport-jwt)** | ![Stars](https://img.shields.io/github/stars/michaelmcshinsky/express-react-passport-jwt?style=social) | Mature JWT auth: httpOnly cookies, refresh rotation, Zod, helmet, Supertest |
| **[adonis-react-vite](https://github.com/michaelmcshinsky/adonis-react-vite)** | ![Stars](https://img.shields.io/github/stars/michaelmcshinsky/adonis-react-vite?style=social) | Modern Adonis 6 + Vite + React 19 + Tailwind fullstack starter |

### Domain Products
| Repo | Stars | Description |
|------|-------|-------------|
| **[utah-esports](https://github.com/michaelmcshinsky/utah-esports)** | ![Stars](https://img.shields.io/github/stars/michaelmcshinsky/utah-esports?style=social) | Turborepo: Next.js 15, Discord bot, Drizzle/PostGIS, start.gg sync, freshness/provenance |

---

## 🔗 Cross-Linked Technical Writing

| Platform | Focus |
|----------|-------|
| **[mcshinsky.net/work](https://mcshinsky.net/work/)** | Architecture case studies, deep-dives, decision records |
| **[mcshinsky.net/articles](https://mcshinsky.net/articles/)** | Technical tutorials, patterns, tooling guides |
| **[DEV Community](https://dev.to/mikemcshinsky)** | Practical how-tos, library announcements, DX writeups |
| **[Stack Overflow](https://stackoverflow.com/users/2646323/michael-mcshinsky)** | 3.5k+ answers on React, TypeScript, Node, APIs |

---

## 🤝 How to Evaluate My Work

1. **Start with the case studies** → [mcshinsky.net/work](https://mcshinsky.net/work/) — real project retrospectives with metrics
2. **Clone a starter** → `react-starter` or `express-react-passport-jwt` — run `npm run dev` in 2 minutes
3. **Read the architecture decisions** — Each repo has a `DECISIONS.md` or "Architecture" section explaining *why*
4. **Check the CI** — All active repos have lint, typecheck, test, and build gates on every PR

### Signals you can check without trusting me

| Signal | Where |
|---|---|
| Published packages | 8 under `@slipstream-ui/*`, plus `surgejs-sdk` |
| Real installs | `@slipstream-ui/core` and `surgejs-sdk` each report monthly download counts on npm |
| Release discipline | `slipstream-ui` CI runs 20 gates, including manifest validation and generated-artifact drift checks |
| Live products | [utahesports.net](https://utahesports.net), [slipstreamui.com/docs](https://slipstreamui.com/docs), [react-starter.mcshinsky.net](https://react-starter.mcshinsky.net) |

---

## 🧭 What I'm Looking For

- **Collaborators** on `slipstream-ui` — component authors, docs, and anyone running it with a coding agent
- **Design partners** for developer tools: SDKs, deploy pipelines, internal platforms
- **Consulting** on developer experience, API design, and CI/CD reliability

If any of that matches what you need, [get in touch](https://mcshinsky.net/contact).

---

## 🛠 Tools & Technologies

`TypeScript` `React 19` `Node.js` `Vite` `Next.js 15` `Tailwind CSS 4` `TanStack Query` `Drizzle ORM` `PostgreSQL` `PostGIS` `Vitest` `Storybook` `ESLint 9` `Turborepo` `Docker` `GitHub Actions`

---

## 📫 Connect

- **Website**: [mcshinsky.net](https://mcshinsky.net) — portfolio, writing, case studies
- **LinkedIn**: [linkedin.com/in/michaelmcshinsky](https://www.linkedin.com/in/michaelmcshinsky)
- **X/Twitter**: [@mikemcshinsky](https://x.com/mikemcshinsky)
- **DEV**: [dev.to/mikemcshinsky](https://dev.to/mikemcshinsky)
- **Email**: See [mcshinsky.net/contact](https://mcshinsky.net/contact)

---

<!--
Maintenance notes:
- Keep this README employment-safe and focused on current technical interests.
- Do not add acquisition, financing, job-search, or employer-transition language.
- Review links, stars, and project status quarterly.
- Add projects only when public, non-confidential, and representative of current quality.
- Badge services: shields.io for stars/followers; consider adding npm download badges for published packages.
-->