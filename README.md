# Anuraag Tripathy

CS and Math senior at the University of Maryland, graduating December 2026. I build full-stack products, the ML that sits inside them, and the infra that keeps them up. [anuraag.site](https://anuraag.site) · [LinkedIn](https://www.linkedin.com/in/anuraagtripathy/)

## What I'm building now

**Stemline** is version control for unreleased music. Stems are committed individually, diffs are audible rather than textual (A/B crossfade and phase cancellation), and forks reuse chunks by content hash instead of re-uploading. HT-Demucs runs in the browser via onnxruntime-web, so a mixdown is split into stems without the audio leaving the machine, and every chunk is AES-GCM encrypted client-side before upload. [Live](https://stemline-six.vercel.app) · [Code](https://github.com/AnuraagTripathy/Stemline)

**Parliavent** is a debate forum where an AI judge reviews a draft before it posts, flagging unsupported claims, likely fallacies, and vague wording. The writer resolves each flag by hand; anything left unresolved publishes as a visible caveat attached to the post. The model never rewrites or posts on the writer's behalf. Evidence retrieval runs as staged jobs on a FastAPI and Redis queue with a synchronous fallback. [Live](https://parliavent.vercel.app) · [Code](https://github.com/AnuraagTripathy/Parliavent)

**Faultline** keeps long ML training runs recoverable across crashes and preemptions. A Python SDK on PyPI, a FastAPI cloud API, a Next.js dashboard, and a Rust persistence runtime with a bounded async checkpoint queue exposed over gRPC. [Live](https://faultline-eight.vercel.app) · [Code](https://github.com/AnuraagTripathy/faultline) · [PyPI](https://pypi.org/project/faultline-sdk/)

**A real-time harmonizer.** Pitch tracking on a live input signal, generated chord accompaniment that follows the detected line, and notation that scrolls as you play. No public repo yet.

## Repos

| Repo | What it is | Live | Stack |
|---|---|---|---|
| [Stemline](https://github.com/AnuraagTripathy/Stemline) | Stem-level version control for unreleased music, encrypted client-side | [stemline-six.vercel.app](https://stemline-six.vercel.app) | Next.js, TypeScript, Supabase, Web Audio, Web Crypto, onnxruntime-web |
| [Parliavent](https://github.com/AnuraagTripathy/Parliavent) | Debate forum where claims are checked before they post | [parliavent.vercel.app](https://parliavent.vercel.app) | Next.js, TypeScript, Prisma, Postgres, Groq, Tavily, FastAPI, Redis |
| [faultline](https://github.com/AnuraagTripathy/faultline) | Checkpoint and crash-to-resume platform for ML training | [faultline-eight.vercel.app](https://faultline-eight.vercel.app) | Rust, Python, gRPC, FastAPI, Next.js, Postgres, Cloudflare R2 |
| [outbreak](https://github.com/AnuraagTripathy/outbreak) | Traces a viral claim back through the public corpus to its earliest match | [outbreak.butterbase.dev](https://outbreak.butterbase.dev) | Next.js, Neo4j, Tavily, edge functions |
| [autoql](https://github.com/AnuraagTripathy/autoql) | Rewrites brittle CSS and XPath locators into semantic AgentQL queries | [autoql-demo.vercel.app](https://autoql-demo.vercel.app) | Python AST, Playwright, Selenium, AgentQL, Next.js |
| [Trace](https://github.com/AnuraagTripathy/Trace) | Reconstructs cross-tool workflows from GitHub and Slack activity into a knowledge graph | [trace-three-cyan.vercel.app](https://trace-three-cyan.vercel.app) | FastAPI, Postgres, NetworkX, Next.js, Docker |
| [Foodie](https://github.com/AnuraagTripathy/Foodie) | Telegram cooking assistant with a kitchen inventory that stays correct | | Cloudflare Workers, D1, R2, Hono, TypeScript, OpenAI |
| [schedy](https://github.com/AnuraagTripathy/schedy) | Desktop calendar agent with a deterministic feasibility engine behind the LLM | | Rust, Tauri v2, React, TypeScript, SQLite |
| [Portfolio](https://github.com/AnuraagTripathy/Portfolio) | Source for anuraag.site | [anuraag.site](https://anuraag.site) | Next.js, TypeScript, Tailwind, Framer Motion |

## Where I've worked

- **GenciseAI**, Fullstack and Applied AI Engineer (Sep 2025 to Jan 2026). Extracted structured data from 500,000+ insurance documents across 1,000+ types with an LLM agent pipeline, and used labeled eval sets and eval diffs to trace failures to specific parsing stages, raising field-level accuracy from 92% to 98%.
- **Mesh**, Applied ML and Automation Engineer (Aug 2025 to Sep 2025). Built agents that discover and score 10k+ TikTok videos a month to surface underground artists 3 to 6 months earlier than traditional scouting.
- **Claryfy**, Full Stack Developer (Jun 2025 to Aug 2025). Built a Canvas LMS assistant to 20+ active users on Next.js, Express, Supabase, and WeaviateDB RAG, shipping against feedback from 50+ students and teachers.
- **University of Maryland**, Research Assistant (Apr 2025 to Jul 2025). Parallelized the R2T2 radiative transfer model for Europa surface composition work, and wrote a modified gradient descent loop that fits model output to Hubble observations.
- **AI Northstar Tech**, Full-stack Developer (Sep 2024 to Nov 2024). Built a React Native chat app running a fine-tuned small language model on-device, so it works with no network.
- **Nokia**, Intern (Aug 2022 to Sep 2022). Studied the broadband network architecture NBNco runs for Australia's national network, across GPON, DOCSIS, and DSL.

## Contact

anuraagt@terpmail.umd.edu · [anuraag.site](https://anuraag.site) · [LinkedIn](https://www.linkedin.com/in/anuraagtripathy/)
