<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=1000&color=6366F1&center=true&vCenter=true&width=700&lines=AI+Systems+Architect;Building+Cognitive+Runtimes+%26+Agentic+OS;Edge+AI+%7C+Multi-Agent+Orchestration;Full+Stack+SaaS+Builder)](https://github.com/smjahid012)

<img src="https://komarev.com/ghpvc/?username=smjahid012&color=6366f1&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile views" />

**Founder & Lead Architect @ [SMLabs AI](https://smlabsai.com) · Building AI systems that run anywhere — cloud, edge, or offline**

</div>

---

## 🧠 What I Build

I'm an **AI Systems Architect** focused on the layer *beneath* the AI hype — the orchestration primitives, cognitive state machines, and inter-agent protocols that make agentic systems actually work at runtime.

Currently building under **[SMLabs AI](https://smlabsai.com)**:

- **[smagent / Cognitive Runtime](https://github.com/smjahid012/smagent)** — Agentic OS focused on real orchestration primitives, cognitive state management, and inter-agent communication protocols. Not another LangChain wrapper.
- **[MedGemma FORENSIC](https://github.com/smjahid012/medgemma-forensic)** — Offline AI pathologist for zero-connectivity environments. Runs Gemma 3 1B + MedSigLIP + MedASR on a $200 Android device at 417MB peak RAM. Submitted to Google's Health AI Developer Foundations program.
- **[SMExpense](https://smexpense.com)** — Production SaaS: AI-powered expense tracker with receipt scanning, voice input, and smart budgeting. First product of SMLabs AI.
- **[Serper Search MCP Server](https://github.com/smjahid012/serper-search-mcp-server)** — Enterprise-grade MCP server exposing Serper web search to Claude Code, Cursor, and any MCP-compatible agent runtime.

---

## 🔬 The MedGemma FORENSIC Architecture

> *Running a Multimodal Diagnostic Suite (LLM + Vision + Audio + Anomaly Detection) on a consumer Android device was considered impossible. I solved the Memory Paradox.*

A "Traffic Cop" sequential AI kernel (`ModelLifecycleManager.kt`) orchestrates ~4.3GB of model weights serially — keeping peak native heap at ~417MB on a 4GB RAM device.

```
Worker Node (Field Medic)          Anchor Node (Command Center)
├── MedSigLIP → visual capture     ├── Receives CaseFile.proto streams
├── MedASR   → verbal autopsy      ├── Full diagnostic reasoning
└── Packages → CaseFile.proto      ├── Gemma 3 1B → ForensicReport
     ↓ P2P Mesh / WiFi Direct ↓    └── AnomalyEngine → Epidemic Clusters
```

📺 [1-min overview](https://www.youtube.com/watch?v=70MFbYzqVho) · [2-min worker node](https://www.youtube.com/watch?v=qNRboKAnfrs) · [3-min mesh pipeline](https://www.youtube.com/watch?v=GGymf9JfSEI) · [Live Gradio Demo](https://huggingface.co/spaces/smfaisal/medgemma-forensic)

---

## 🛠️ Tech Stack

**AI & Agents**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LiteRT](https://img.shields.io/badge/LiteRT_(TFLite)-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_Protocol-6366F1?style=flat-square&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_2.5_Flash-4285F4?style=flat-square&logo=google&logoColor=white)

**Full Stack SaaS**

![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript_Strict-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma_7-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Edge & Mobile**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android_Native-3DDC84?style=flat-square&logo=android&logoColor=white)
![ARM](https://img.shields.io/badge/ARM64_VPS-0091BD?style=flat-square&logo=arm&logoColor=white)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu_24.04_LTS-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Coolify](https://img.shields.io/badge/Coolify-6D28D9?style=flat-square&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

## 🖥️ Self-Hosted Infrastructure

> *No PaaS dependency. No managed infra tax. Real Linux, real ownership.*

```
netcup VPS 1000 ARM G11  ·  Manassas, USA
├── 🔲 6-core ARM64  ·  8GB RAM  ·  256GB NVMe SSD
├── 🐧 Ubuntu 24.04 LTS
├── 🐳 Docker  ·  Nginx  ·  Traefik reverse proxy  ·  SSL
├── 🚀 Coolify — self-hosted deployment orchestration
└── 🧠 Hosts: smagent Cognitive Runtime · future SMLabs AI services
```

Running production-grade infrastructure on bare metal means understanding what most "AI developers" skip — kernel tuning, container networking, reverse proxy config, SSL cert management, and zero-downtime deployments without a $500/mo Heroku bill.

---

## 📌 Pinned Work

| Project | What It Is | Stack |
|---|---|---|
| [medgemma-forensic](https://github.com/smjahid012/medgemma-forensic) | Offline AI pathologist — multimodal diagnostics on edge Android | Kotlin, LiteRT, ONNX |
| [serper-search-mcp-server](https://github.com/smjahid012/serper-search-mcp-server) | Enterprise MCP server for Serper web search | TypeScript, MCP |
| [smagent](https://github.com/smjahid012/smagent) *(private)* | Cognitive Runtime — agentic OS with real orchestration primitives | Python |
| [smexpense](https://smexpense.com) *(private)* | Live AI expense SaaS — first product of SMLabs AI | Next.js, Supabase, Prisma |
| [smportfolio](https://github.com/smjahid012/smportfolio) | Personal portfolio | TypeScript |

---

## 📊 GitHub Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/smjahid012/smjahid012/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/smjahid012/smjahid012/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/smjahid012/smjahid012/output/github-contribution-grid-snake-dark.svg" />
</picture>

<img width="49%" src="https://github-readme-streak-stats.herokuapp.com?user=smjahid012&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=smjahid012&layout=compact&theme=tokyonight&hide_border=true&langs_count=6&count_private=true" />

<br/>

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=smjahid012&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" />

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=smjahid012&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Activity" />

</div>

---

## 🔭 What's Next

- **Cognitive Runtime v1** — Public release of the smagent orchestration layer with cognitive state management primitives
- **SMExpense Pro** — Expanding to family finance with military-tier subscription tiers (RECON / COMMAND / SOVEREIGN)
- **Model Fine-tuning** — Domain-specific fine-tuning pipeline for edge-deployable models under SMLabs AI
- **anthropic_proxy** — Multi-provider LLM proxy (Gemini, Groq, DeepSeek, OpenRouter) routing through Claude Code CLI — publishing soon

---

## 📫 Connect

[![SMLabs AI](https://img.shields.io/badge/smlabsai.com-6366F1?style=for-the-badge&logo=rocket&logoColor=white)](https://smlabsai.com)
[![SMExpense](https://img.shields.io/badge/smexpense.com-10B981?style=for-the-badge&logo=vercel&logoColor=white)](https://smexpense.com)
[![GitHub](https://img.shields.io/badge/smjahid012-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/smjahid012)
[![HuggingFace](https://img.shields.io/badge/HuggingFace_Demo-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/smfaisal/medgemma-forensic)

<div align="center">

> *"The gap between 'AI enthusiast' and 'AI architect' is orchestration. Anyone can call an API. Few understand what happens between the calls."*

</div>
