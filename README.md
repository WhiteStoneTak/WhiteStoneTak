<h1 align="center">Takumi Shiraishi</h1>

<p align="center">
  Founder and engineer at <a href="https://wovol.com">Wovol</a>.<br>
  Local-first AI products, evidence-linked developer tooling, and the unglamorous safety work that makes them shippable.
</p>

<p align="center">
  <b>English</b> &nbsp;·&nbsp; <a href="README.ja.md">日本語</a>
</p>

<p align="center">
  <a href="https://wovol.com"><img alt="wovol.com" src="https://img.shields.io/badge/wovol.com-000000?style=flat-square&logo=vercel&logoColor=white"></a>
  <a href="mailto:takumi@wovol.com"><img alt="Email" src="https://img.shields.io/badge/takumi@wovol.com-24292F?style=flat-square&logo=gmail&logoColor=white"></a>
  <img alt="Based in" src="https://img.shields.io/badge/Japan%20%2F%20Vancouver%2C%20BC-3B7DD8?style=flat-square&logo=googlemaps&logoColor=white">
</p>

---

## Now

- **vajco ai** (private) — an anticipatory workspace layer for macOS. Press a hotkey and the thing you were about to resume is already prepared: repo, branch, tabs, cwd, and an on-device summary. Swift 6 / SwiftUI, ~240 sources, notarized `0.1.0` builds. [Landing page →](https://wovol.com/lp/vajco-ai)
- **Sonae** (private) — one personalized disaster-response agent per citizen, 8,000 of them reasoning in parallel on a single AMD Instinct MI300X. [Live demo →](https://sonae-visitor-lp.vercel.app/) · [Write-up →](https://lablab.ai/ai-hackathons/amd-developer/sonae/sonae-personal-disaster-ai-agent-for-each-citizen)
- **LegacyLens** (private) — self-hosted Java/Spring legacy comprehension that emits evidence-linked HTML/PDF reports plus a machine-readable `evidence.json`. No managed backend, runs entirely on the customer's machine.
- At **iOSDC Japan 2026** this week. Say hi if you are there.

## Selected work

| Project | What it is | Stack | Repo | Links |
| --- | --- | --- | --- | --- |
| **vajco ai** | Anticipatory macOS workspace layer. On-device only, nothing leaves the machine. | Swift 6, SwiftUI, GRDB/SQLite, Apple FoundationModels, Accessibility API | 🔒 Private | [Landing page](https://wovol.com/lp/vajco-ai) |
| **Sonae** | Per-citizen disaster-response agents. Cascades tracked as a chain (typhoon → flood → outage → comms failure), not isolated events. Built for AMD Developer Cloud Hackathon 2026, Track 3. | Next.js, FastAPI, vLLM, ROCm, Qwen3.5-122B-A10B-FP8, Leaflet | 🔒 Private | [Demo](https://sonae-visitor-lp.vercel.app/) · [lablab.ai](https://lablab.ai/ai-hackathons/amd-developer/sonae/sonae-personal-disaster-ai-agent-for-each-citizen) |
| **LegacyLens** | Legacy Java/Spring audit tool for Japanese SIer firms. Every claim in the report links back to the source line that justifies it. | TypeScript, Node, pnpm, Docker, JSON Schema | 🔒 Private | — |
| **Axiom** | Joy-first, privacy-first AI study coach. No third-party telemetry by default. | React 19, Vite, Tailwind v4, shadcn/ui, Three.js, KaTeX, Zod | 🔒 Private (Wovol monorepo) | [axiom.wovol.com](https://axiom.wovol.com) |
| **Lumen** | Empirical study of whether code *representation* changes frontier-LLM code reasoning, with an information-parity control (C1+). Preregistered, nine-cell confirmatory family, Holm-corrected. Result: non-rejection on all nine cells. | Python, LaTeX | 🌐 **Public** | [Repo](https://github.com/WhiteStoneTak/Lumen) · [preprint-v1](https://github.com/WhiteStoneTak/Lumen/releases/tag/preprint-v1) · [/research](https://wovol.com/research) |
| **SEO** | A working SEO method for people who have commit access to the site. Prose, checklists, and agent playbooks. No crawler, no scoring engine. | Markdown, agent skills | 🌐 **Public** | [Repo](https://github.com/WhiteStoneTak/SEO) |
| **4-bit Binary Calculator** | Mechanical 4-bit calculator built from marble logic gates (XOR / AND / OR + a custom Y-split), laser-cut 2D MDF. Ships a truth-table evidence pack and the failed iterations. | CAD (DWG), HTML demo | 🌐 **Public** | [Repo](https://github.com/WhiteStoneTak/4-bit-Binary-Calculator) |
| **wovol-lab** | Local-first Claude Code ops lab: a neuroscience-inspired memory layer (mnemos), 4-profile browser isolation, and a bilingual EN+JA safety net that scans every write against 30+ PII/secret patterns. Never auto-sends. | Python, shell hooks | 🔒 Private | — |

> 🔒 Private repositories are listed because they are where most of the work happens. The links above are the parts that are genuinely public: demos, landing pages, and write-ups.

## Open source and upstream

- [**home-assistant/core#181366**](https://github.com/home-assistant/core/pull/181366) — proposed a read-only, least-privilege OAuth scope profile for the `tesla_fleet` integration (+632 / −60 across 9 files). Closed after discussion with the integration code owner, who pointed out the existing consent flow already lets users deselect command scopes. Public, and the review thread is worth more than the merge would have been.
- **EasyDialog / homepage** (private client repository) — 8 PRs merged into production between Aug and Sep 2026: HTTP→HTTPS redirect with a baseline CSP, canonical responses for routes / `robots.txt` / `sitemap.xml`, localized metadata and document languages, a main landmark + skip link + accessible navigation, a referrer-policy fix that stopped withholding search credit from linked sites, and baseline security/CI hardening.
- Public work lives in **Lumen**, **SEO**, and **4-bit-Binary-Calculator** above. All three are written evidence-first: methods, data, and the iterations that failed.

## Highlights

- **paiza S rank (Python).** The top algorithmic tier on paiza's coding-skill check.
- **Lumen preprint frozen and tagged.** Preregistrations written before the confirmatory runs, Holm correction across nine cells, and a documented null reported as a null.
- **Security as a default, not a phase.** Repo-wide secret scanning (including git history), CSP hash generation in the build, a dedicated security CI workflow, and PII pattern matching that covers Japanese identifiers (マイナンバー / 保険証 / 戸籍) alongside Western ones.
- **Bilingual by construction.** Japanese native, fluent in English. Product copy, security tooling, and customer documents all ship in both.

## Tech

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-437291?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Web**

![React](https://img.shields.io/badge/React%2019-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind%20v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)

**Apple platforms**

![Swift 6](https://img.shields.io/badge/Swift%206-F05138?style=flat-square&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0071E3?style=flat-square&logo=swift&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=flat-square&logo=xcode&logoColor=white)
![SwiftPM](https://img.shields.io/badge/SwiftPM-FA7343?style=flat-square&logo=swift&logoColor=white)
![macOS](https://img.shields.io/badge/macOS%2026+-000000?style=flat-square&logo=apple&logoColor=white)

**Backend and data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js%2022-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite%20%2F%20GRDB-003B57?style=flat-square&logo=sqlite&logoColor=white)

**AI and inference**

![Anthropic](https://img.shields.io/badge/Claude%20%2F%20MCP-D97757?style=flat-square&logo=anthropic&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-FDB515?style=flat-square&logo=huggingface&logoColor=black)
![ROCm](https://img.shields.io/badge/AMD%20ROCm-ED1C24?style=flat-square&logo=amd&logoColor=white)
![Qwen](https://img.shields.io/badge/Qwen3.5-615CED?style=flat-square&logo=huggingface&logoColor=white)
![FoundationModels](https://img.shields.io/badge/Apple%20FoundationModels-000000?style=flat-square&logo=apple&logoColor=white)

**Build and ops**

![pnpm](https://img.shields.io/badge/pnpm-F69220?style=flat-square&logo=pnpm&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white)

## GitHub

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=WhiteStoneTak&theme=github_dark">
    <img height="200" alt="GitHub profile summary for WhiteStoneTak" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=WhiteStoneTak&theme=github">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=WhiteStoneTak&theme=dark&hide_border=true&card_width=700&card_height=200">
    <img height="200" alt="Contribution streak" src="https://streak-stats.demolab.com?user=WhiteStoneTak&theme=default&hide_border=true&card_width=700&card_height=200">
  </picture>
</p>

<p align="center"><sub>Most commits land in private repositories, so public-only language breakdowns understate the actual mix. The table above is the honest version.</sub></p>

## Contact

**Email:** [white.stone.tak@gmail.com](mailto:white.stone.tak@gmail.com) &nbsp;·&nbsp; **Web:** [wovol.com](https://wovol.com)

Open to conversations about local-first AI, Apple-platform work, developer tooling for legacy systems, and anything involving evidence you can actually check.
