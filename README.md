# Case studies

Most of my product code lives in private repositories. These write-ups show how the products are built: the architecture, the decisions behind it, the bugs that mattered, and how AI agents did the work under review. Happy to walk through the actual code on a call.

| Case | What it shows |
|---|---|
| [STDIO — AI photo studio for iOS](stdio.md) | Long-running AI jobs on Cloudflare Workers, choosing a model by cost and quality, getting through App Review |
| [Dosefy — GLP-1 therapy tracker for iOS](dosefy.md) | An offline-first app, a hardened LLM call, a 150-finding multi-agent audit turned into a release |
| [BalaSpace — platform for private kindergartens](balaspace.md) | A multi-tenant Supabase backend with row-level security, a two-agent workflow, end-to-end tests on a real device |
| [vg.kz — corporate website](vg-kz.md) | A 328-page trilingual migration, a 25-agent audit with a skeptic pass, release automation |

Open-source sample with full history: **[BusCore](https://github.com/mcdlxv/buscore)** — a FastAPI backend with 46 tests, built spec → plan → code → review.
