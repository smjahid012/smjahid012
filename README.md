<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=1000&color=6366F1&center=true&vCenter=true&width=700&lines=AI+Systems+Architect;Building+Cognitive+Runtimes+%26+Agentic+OS;Edge+AI+%7C+Multi-Agent+Orchestration;Full+Stack+SaaS+Builder)](https://github.com/smjahid012)

<img src="https://komarev.com/ghpvc/?username=smjahid012&color=6366f1&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile views" />

**Founder & Lead Architect @ [SMLabs AI](https://smlabsai.com) · Building AI systems that run anywhere — cloud, edge, or offline**

</div>

---

## 🧠 Systems I Have Built

I'm an **AI Systems Architect** focused on the orchestration primitives, cognitive state machines, and inter-agent protocols that make agentic systems reliable at runtime.

Each project below is an independent production system built under **[SMLabs AI](https://smlabsai.com)**:

### 🧠 Agent Orchestration System
**[smagent / Cognitive Runtime](https://github.com/smjahid012)** *(private)*
Agentic OS with real orchestration primitives, cognitive state management, and inter-agent communication protocols. Built from scratch for full production control — no framework lock-in.

### 🌐 LLM Gateway System
**[anthropic-proxy](https://github.com/smjahid012)** *(public)*
Multi-provider LLM routing layer with protocol translation — routes Claude Code CLI through Gemini, Groq, DeepSeek, and OpenRouter. Direct provider integration — minimal abstraction overhead.

### 🧬 Edge AI System
**[MedGemma FORENSIC](https://github.com/smjahid012/medgemma-forensic)**
Offline multimodal AI diagnostics on a $200 Android device. Gemma 3 1B + MedSigLIP + MedASR at 417MB peak RAM. Submitted to Google's Health AI Developer Foundations program.

### 💰 SaaS System
**[SMExpense](https://smexpense.com)** *(private)*
AI-powered expense analyzer with receipt scanning, voice input, and smart budgeting.

### 🔌 AI Tooling System
**[Serper Search MCP Server](https://github.com/smjahid012/serper-search-mcp-server)**
8-tool MCP server (web, images, videos, news, shopping, places, deep research, RAG context) used with Claude, Cursor, Windsurf, n8n, and KiloCode. Published on npm and Docker. TypeScript, full type safety, zero telemetry.

---

## 🔬 The MedGemma FORENSIC Architecture

> *Running a Multimodal Diagnostic Suite (LLM + Vision + Audio + Anomaly Detection) on a consumer Android device under 500MB peak RAM.*

A "Traffic Cop" sequential AI kernel (`ModelLifecycleManager.kt`) orchestrates ~4.3GB of model weights serially — keeping peak native heap at ~417MB on a 4GB RAM device.

```
Worker Node (Field Medic)          Anchor Node (Command Center)
├── MedSigLIP → visual capture     ├── Receives CaseFile.proto streams
├── MedASR   → verbal autopsy      ├── Full diagnostic reasoning
└── Packages → CaseFile.proto      ├── Gemma 3 1B → ForensicReport
     ↓ P2P Mesh / WiFi Direct ↓    └── AnomalyEngine → Epidemic Clusters
```

📺 [Live Gradio Demo](https://huggingface.co/spaces/smfaisal/medgemma-forensic)

---

## 🛠️ Tech Stack

**AI / ML & Agents**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LiteRT](https://img.shields.io/badge/LiteRT_(TFLite)-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=white)
![MCP](https://img.shields.io/badge/MCP_Protocol-6366F1?style=flat-square&logoColor=white)

**LLM Providers & APIs**

![Claude](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini_API-4285F4?style=flat-square&logo=google&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek-0A0A0A?style=flat-square&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6366F1?style=flat-square&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)

**Full Stack SaaS**

![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript_Strict-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma_7-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Better Auth](https://img.shields.io/badge/Better_Auth-000000?style=flat-square&logoColor=white)

**Edge & Mobile**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Coroutines](https://img.shields.io/badge/Coroutines-18D4A5?style=flat-square&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android_Native-3DDC84?style=flat-square&logo=android&logoColor=white)
![Protobuf](https://img.shields.io/badge/Protobuf-4285F4?style=flat-square&logo=google&logoColor=white)
![WiFi Direct](https://img.shields.io/badge/WiFi_Direct_P2P-0078D4?style=flat-square&logoColor=white)
![ARM](https://img.shields.io/badge/ARM64-0091BD?style=flat-square&logo=arm&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![REST](https://img.shields.io/badge/REST_API-FF6C37?style=flat-square&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Upstash](https://img.shields.io/badge/Upstash_Redis-00E9A3?style=flat-square&logoColor=white)

**Infrastructure & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=flat-square&logo=traefikproxy&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu_24.04_LTS-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Coolify](https://img.shields.io/badge/Coolify-6D28D9?style=flat-square&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

## 🖥️ Self-Hosted Infrastructure

> *Self-hosted on bare-metal Linux — no managed platform abstraction layer.*

```
netcup VPS 1000 ARM G11  ·  Manassas, USA
├── 🔲 6-core ARM64  ·  8GB RAM  ·  256GB NVMe SSD
├── 🐧 Ubuntu 24.04 LTS
├── 🐳 Docker  ·  Nginx  ·  Traefik reverse proxy  ·  SSL
├── 🚀 Coolify — self-hosted deployment orchestration
└── 🧠 Hosts: smagent Cognitive Runtime · future SMLabs AI services
```

Provisioning, securing, and operating Linux servers without a managed platform layer.

---

## 📌 Pinned Systems

| System | What It Is | Stack |
|---|---|---|
| [medgemma-forensic](https://github.com/smjahid012/medgemma-forensic) *(public)* | Edge AI pathologist — multimodal diagnostics on Android | Kotlin, LiteRT, ONNX, Protobuf, P2P |
| [serper-search-mcp-server](https://github.com/smjahid012/serper-search-mcp-server) *(public)* | Enterprise MCP server for agent web search | TypeScript, MCP, Node.js, Serper API |
| [smagent](https://github.com/smjahid012/smagent) *(private)* | Cognitive Runtime — agentic OS, orchestration primitives | Python, LangGraph, Redis, MCP |
| [anthropic-proxy](https://github.com/smjahid012) *(public)* | LLM gateway routing Claude Code through Gemini, Groq, DeepSeek | Python, Claude API, Gemini, Groq, DeepSeek |
| [smexpense](https://smexpense.com) *(private)* | Live AI expense SaaS — receipt OCR, voice input, smart budgeting | Next.js, Supabase, Prisma, Tailwind, PostgreSQL, Redis |


---

## 📊 GitHub Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/smjahid012/smjahid012/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/smjahid012/smjahid012/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/smjahid012/smjahid012/output/github-contribution-grid-snake-dark.svg" />
</picture>

<img width="49%" src="https://github-readme-streak-stats.herokuapp.com?user=smjahid012&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=smjahid012&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&count_private=true&hide=html,css" />

<br/>

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=smjahid012&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" />

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=smjahid012&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Activity" />

</div>

---

## 📫 Connect

[![SMLabs AI](https://img.shields.io/badge/smlabsai.com-6366F1?style=for-the-badge&logo=rocket&logoColor=white)](https://smlabsai.com)
[![SMExpense](https://img.shields.io/badge/smexpense.com-10B981?style=for-the-badge&logo=vercel&logoColor=white)](https://smexpense.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourhandle)
[![GitHub](https://img.shields.io/badge/smjahid012-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/smjahid012)
[![HuggingFace](https://img.shields.io/badge/HuggingFace_Demo-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/smfaisal/medgemma-forensic)

<div align="center">

> *"The difference between an AI enthusiast and an AI architect is orchestration."*

</div>
