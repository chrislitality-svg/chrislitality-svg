# Bee Zhao (赵轶峰)

**Historian × AI builder.** I study Ming dynasty political economy by day, and build multi-agent AI tools by night — for creative writing, training systems, and historical simulation.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" alt="Electron" />
  <img src="https://img.shields.io/badge/Vue-42B883?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude Code" />
</p>

---

## About

Professor & Dean, Institute of Asian Civilizations, Northeast Normal University. PhD in History, University of Alberta.

My research centers on Ming-Qing institutional history — most notably the **"Imperial Agrarian-Commercial Society"** framework for understanding Ming political economy, and a critique of the **"Great Convergence"** narrative in Chinese economic history. I serve as Executive Editor of *Journal of Ancient Civilizations* (《古代文明》) and as a special advisor to the Chinese Ming History Society.

Outside academia, I run a live-streaming e-commerce company and serve as Training Director at a tech company, where I lead AI adoption initiatives — moving teams from scattered, ad-hoc AI tool use toward end-to-end workflow redesign and codified SOPs.

## What I Build

No formal CS background — I came to programming to solve real problems in publishing, training, and business operations, and kept going. Current and past projects include:

- **NovelForge** — a multi-agent AI pipeline for historical novel writing, with a five-layer memory architecture
- **[CourtSim](https://github.com/chrislitality-svg/courtsim)** — a multi-agent simulation engine modeling Ming dynasty court politics
- **Pylo (拍乐)** — an AI-assisted short-drama creation tool for Chinese content creators
- **Haibei Video Engine** — high-volume, template-driven video generation for e-commerce
- Smaller side projects: a [CS2 tactics assistant](https://github.com/chrislitality-svg/cs2-lineups), a [Tetris mod](https://github.com/chrislitality-svg/tetris-widget), and whatever problem is in front of me that week

## Currently

- Leading a company-wide AI transformation initiative (through August 2026)
- Turning years of Ming dynasty research into a historical novel
- Based in China, currently traveling in Europe

---

## Featured Projects

Everything I keep public, grouped by theme.

### Expression-Analysis Agent Skills

Corpus-based Claude Code skills that decompose how specific Chinese speakers structure an argument — each ships a zero-dependency "AI-flavor" detector.

| Repo | What it does | Stack |
|---|---|---|
| [think-like-fandeng](https://github.com/chrislitality-svg/think-like-fandeng) | 樊登-style book-talk skill distilled from ~30 h of corpus (786 coded units) — analysis, narration, dialogue and revision modes | Markdown skill · Python · CI |
| [think-like-wangziru](https://github.com/chrislitality-svg/think-like-wangziru) | Edition 2 of the 王自如 skill, built on 32 transcripts (~860k-char corpus base); one line gets you analysis, drafting, dialogue or revision — answer first, reasons clear, survives follow-up questions | Markdown skill · Python · CI |
| [wangziru-analysis-skill-v1](https://github.com/chrislitality-svg/wangziru-analysis-skill-v1) | Edition 1 (v1.0–v1.3) — the original, more general-purpose recipe, kept as a stable archive | Markdown skill · Python |
| [wangziru-analysis-skill](https://github.com/chrislitality-svg/wangziru-analysis-skill) | The original 王自如 repo, frozen at v1.4; development moved to the two repos above | Markdown skill · Python |
| [luoyonghao-analysis-skill](https://github.com/chrislitality-svg/luoyonghao-analysis-skill) | Unofficial 罗永浩 expression analysis — logic-first decomposition and writing for speeches, benchmarked on 310k characters of corpus | Markdown skill · Python |

### Content & Reading Tools

| Repo | What it does | Stack |
|---|---|---|
| [script-to-video](https://github.com/chrislitality-svg/script-to-video) | Turns any document into a 3:4 vertical explainer short, rendered entirely by code — deterministic timeline, reproducible frame by frame | Claude skill · Python · Playwright · ffmpeg |
| [novel-insight](https://github.com/chrislitality-svg/novel-insight) | Local, bring-your-own-LLM analyzer for Chinese web novels — chapter-level mining of character conduct and dialogue tactics into a card knowledge base | FastAPI · Vue 3 · SQLite |

### Historical Simulation

| Repo | What it does | Stack |
|---|---|---|
| [courtsim](https://github.com/chrislitality-svg/courtsim) | Court-politics simulation across seven dynasties, Qin through Qing — LLM-driven debates on real agenda items, grounded in a historical-source RAG corpus; fully local, BYO-LLM | Next.js · TypeScript · Prisma |

### Desktop Widgets & Games

| Repo | What it does | Stack |
|---|---|---|
| [tetris-widget](https://github.com/chrislitality-svg/tetris-widget) | Frameless, always-on-top pixel Tetris — full SRS handling, heuristic-AI battle royale, and a boss key that disguises it as VS Code | Electron · JavaScript |
| [PixelPal](https://github.com/chrislitality-svg/PixelPal) | Pixel-art desktop pet with FSM + behavior-tree AI — 11 species, 90+ job dispatches, a collection book and weather awareness | Electron · TypeScript |
| [forced-reminder](https://github.com/chrislitality-svg/forced-reminder) | A periodic reminder that refuses to be dismissed — modal popups, absolute-timestamp catch-up after reboots, Excel export; Windows 7–11 | Python · PyQt5 |

### Web Tools

| Repo | What it does | Stack |
|---|---|---|
| [cs2-lineups](https://github.com/chrislitality-svg/cs2-lineups) | CS2 lineup sandbox — 3D grenade paths over 11 map overviews, offline PWA, plus portal/rental pages and a small self-hosted sync service | JavaScript · three.js · Python |
| [cs2-portal](https://github.com/chrislitality-svg/cs2-portal) | Single-file, zero-dependency CS2 news page fed by the public Steam API, with built-in fallback data | HTML · JavaScript |
| [engineer-buddy](https://github.com/chrislitality-svg/engineer-buddy) | Conversational requirements clarification — role-based staged interviews that turn vague ideas into OpenSpec proposal packages; ships a key-hiding proxy with rate limits and spend fuses | React · TypeScript · Vite |

### Live-Streaming E-Commerce

| Repo | What it does | Stack |
|---|---|---|
| [livestream-coach-oss](https://github.com/chrislitality-svg/livestream-coach-oss) | Sales-talk analysis agent for livestreams — unattended capture → local CPU transcription → quantified talk structure → gap-finding against category benchmarks; rule layer runs at zero model cost | Python · Playwright · sherpa-onnx |

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=chrislitality-svg&show_icons=true&hide_border=true" alt="GitHub stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chrislitality-svg&show_icons=true&hide_border=true&layout=compact" alt="Top languages" height="165" />
</p>

---

📖 History, one archive at a time · 🤖 AI, one pipeline at a time
