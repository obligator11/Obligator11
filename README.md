<div align="center">

# 👋 Hi, I'm Sayyam Shahbaz

<a href="https://github.com/obligator11">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=2500&pause=800&color=00F5FF&center=true&vCenter=true&width=650&lines=Founding+Developer+%40+NOUNFORM;Building+Local-First+Agentic+AI+Systems;Multi-Agent+Pipelines+%7C+Zero+Paid+APIs;Local+LLMs+%2B+RAG+%2B+Human-in-the-Loop;Microsoft+%26+IBM+Certified+AI+Engineer" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sayyam-shahbaz-dev)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://www.instagram.com/obligator11/)
[![GitHub](https://img.shields.io/badge/Vision--Core--Projects-181717?logo=github&logoColor=white)](https://github.com/obligator11/Vision-Core-Projects)

</div>

<br/>

## ⚡ About Me

```yaml
AI engineer:
  name: "Sayyam Shahbaz"
  location: "Abbottabad, Pakistan"
  role: "Founding Developer & Software Engineer, AI & Automation Systems @ NOUNFORM"
  certifications: ["Microsoft Certified AI Engineer", "IBM Certified AI Engineer"]
  specialization: ["Software Architecture", "System Design", "Agentic AI Engineering"]
  currently_building: "AI & automation systems at NOUNFORM + Multi-Agent Digital Ops Team"
  philosophy: "Local-first, zero-paid-API, human-in-the-loop by design"
  learning: ["Agentic architectures", "MCP integrations", "Applied spatial math for CV"]
  brand: "@obligator11 — content on TikTok / Instagram / LinkedIn / YouTube"
```

I design and ship **multi-agent AI systems that run entirely on local infrastructure** — orchestrating models like Qwen2.5-Coder, DeepSeek-R1, Llama 3.1, and Gemma through Ollama and LM Studio, with PostgreSQL, ChromaDB, and Redis handling state, memory, and concurrency. Every system I build follows the same four-layer discipline: **Presentation → Application → Domain → Infrastructure.**

Before this, I spent months building real-time computer vision and AR systems (pose estimation, gesture control, YOLO-based tracking) — that CV depth now shows up in how I think about latency, threading, and perception pipelines inside agent systems.

<br/>

## 💼 Experience

**NOUNFORM — Founding Developer & Software Engineer, AI & Automation Systems** · *Feb 2025 – Jun 2026*
- Architected a modular Python gym-automation desktop platform (CustomTkinter) covering client intake, AI-generated diet plans, and PDF creation, with a hybrid inference engine (local Llama 3.1 + automatic Grok API failover) for uninterrupted plan generation
- Built a serverless WhatsApp workout-plan bot on Google Apps Script + Meta WhatsApp Business API, generating constraint-based weekly splits from Google Form intake
- Designed and shipped [nounform.com](https://nounform.com/) and client sites [tripleeyes.pk](https://tripleeyes.pk/) and [studioonearch.com](https://studioonearch.com/) in React/TypeScript

**Solid Gym — Software Engineer** · *Jul 2024 – Sep 2024*
- Engineered a modular, multithreaded PySide6 desktop app with RBAC, financial transaction logging, and a hardware abstraction layer for webcam/biometric integration
- Integrated Google Drive API (OAuth 2.0) for automated cloud disaster recovery and built local analytics for daily executive briefings

<br/>

## 🧠 Currently Architecting

<table>
<tr>
<td width="33%" valign="top">

**🎫 Multi-Agent Digital Ops Team**
IT Helpdesk MVP · v3 architecture
Redis/RQ concurrency, Prometheus + Grafana observability

</td>
<td width="33%" valign="top">

**🧾 Invoice/AP Automation Agent**
4-model pipeline: extraction → anomaly reasoning → explanation → routing, with a human-in-the-loop approval gate

</td>
<td width="33%" valign="top">

**🧠 Local Dual-LLM RAG Workspace**
NotebookLM-style research tool — DeepSeek-R1 (reasoning) + Qwen2.5-Coder (implementation) via LM Studio, isolated per-notebook ChromaDB vaults

</td>
</tr>
</table>

<br/>

## 🏗️ How I Build — Four-Layer Architecture

Every agentic system I ship follows this pattern:

```mermaid
graph TD
    A["🎨 Presentation Layer<br/>Streamlit"] --> B["⚙️ Application Layer<br/>Agent Pipeline / Orchestration"]
    B --> C["📐 Domain Layer<br/>Pydantic Schemas"]
    B --> D["🗄️ Infrastructure Layer<br/>Local LLMs · PostgreSQL · ChromaDB · Redis"]
    D --> E["🧠 Qwen2.5-Coder<br/>Extraction"]
    D --> F["🔍 DeepSeek R1<br/>Reasoning"]
    D --> G["💬 Llama 3.1<br/>Explanation"]
    D --> H["🧭 Gemma<br/>Routing"]

    style A fill:#0d1117,stroke:#00f5ff,color:#00f5ff
    style B fill:#0d1117,stroke:#bd00ff,color:#bd00ff
    style C fill:#0d1117,stroke:#00f5ff,color:#00f5ff
    style D fill:#0d1117,stroke:#bd00ff,color:#bd00ff
    style E fill:#1a1a3e,stroke:#00f5ff,color:#e0e0e0
    style F fill:#1a1a3e,stroke:#00f5ff,color:#e0e0e0
    style G fill:#1a1a3e,stroke:#00f5ff,color:#e0e0e0
    style H fill:#1a1a3e,stroke:#00f5ff,color:#e0e0e0
```

<br/>

## 📌 Top Repositories

### 🤖 Agentic AI & Automation

<div align="center">

[![Digital Ops Team](https://github-readme-stats.shion.dev/api/pin/?username=obligator11&repo=multi-agent-it-helpdesk&theme=dark)](https://github.com/obligator11/multi-agent-it-helpdesk)
[![Invoice/AP Automation Agent](https://github-readme-stats.shion.dev/api/pin/?username=obligator11&repo=invoice-ap-agent&theme=dark)](https://github.com/obligator11/invoice-ap-agent)
[![Local Dual-LLM RAG Workspace](https://github-readme-stats.shion.dev/api/pin/?username=obligator11&repo=AI_Duo_LLM&theme=dark)](https://github.com/obligator11/AI_Duo_LLM)

</div>

- **Digital Ops Team (Multi-Agent IT Helpdesk)** — six-agent local pipeline (Triage → RAG-grounded Resolver → independent Auditor → HITL gate → Dispatcher) across two model backends, with a deterministic HITL gate, full observability stack, and a 15-ticket eval harness that lifted Triage accuracy 42%→50%
- **Invoice/AP Automation Agent** — 4-model local pipeline (Qwen2.5-Coder → DeepSeek R1 → Llama 3.1 → Gemma) with PostgreSQL + ChromaDB and a human-in-the-loop approval gate
- **Local Dual-LLM RAG Workspace** — NotebookLM-style research tool combining DeepSeek-R1 + Qwen2.5-Coder via LM Studio, with per-notebook ChromaDB vaults

### 👁️ Computer Vision & AR Suite

<div align="center">

[![Vision-Core-Projects](https://github-readme-stats.shion.dev/api/pin/?username=obligator11&repo=Vision-Core-Projects&theme=dark)](https://github.com/obligator11/Vision-Core-Projects)
[![CrowdAI](https://github-readme-stats.shion.dev/api/pin/?username=obligator11&repo=CrowdAI&theme=dark)](https://github.com/obligator11/CrowdAI)

[![DriverFatigueSystem](https://github-readme-stats.shion.dev/api/pin/?username=obligator11&repo=DriverFatigueSystem&theme=dark)](https://github.com/obligator11/DriverFatigueSystem)
[![InterviewAnalyzer](https://github-readme-stats.shion.dev/api/pin/?username=obligator11&repo=InterviewAnalyzer&theme=dark)](https://github.com/obligator11/InterviewAnalyzer)

</div>

- **Vision-Core-Projects** — 60+ real-time CV/AR experiments: pose-driven games, gesture control, AR overlays, all single-file with procedural audio
- **CrowdAI** — real-time crowd density & flow analytics using YOLOv8 + DBSCAN clustering
- **DriverFatigueSystem** — MediaPipe Face Mesh–based fatigue/attention monitor using EAR/MAR metrics
- **InterviewAnalyzer** — multi-modal interview confidence analyzer (MediaPipe Face Mesh + Pose + Whisper)

### 🏢 Client & Product Work

<div align="center">

[![gym-management-system](https://github-readme-stats.shion.dev/api/pin/?username=obligator11&repo=gym-management-system&theme=dark)](https://github.com/obligator11/gym-management-system)

</div>

- **Solid Gym Management System** — modular PySide6 desktop app with RBAC, financial transaction logging, and Google Sheets–backed state
- **NOUNFORM** — company site plus client sites for [Triple Eyes Real Estate & Marketing](https://tripleeyes.pk/) and [Studio One Architecture](https://studioonearch.com/), React/TypeScript

<br/>

## 🛠️ Tech Stack by Layer

<table>
<tr><td><b>🎨 Presentation</b></td><td>

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![React](https://img.shields.io/badge/React-%2320232a.svg?logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-%233178C6.svg?logo=typescript&logoColor=white)

</td></tr>
<tr><td><b>⚙️ Application</b></td><td>

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-%23339933.svg?logo=node.js&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?logo=Pydantic&logoColor=white)

</td></tr>
<tr><td><b>🗄️ Infrastructure</b></td><td>

![Ollama](https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%234169E1.svg?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DC382D.svg?logo=redis&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?logo=docker&logoColor=white)

</td></tr>
<tr><td><b>👁️ Computer Vision</b></td><td>

![OpenCV](https://img.shields.io/badge/OpenCV-%235C3EE8.svg?logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?logo=tensorflow&logoColor=white)

</td></tr>
</table>

<br/>

## 🎓 Certifications

![Microsoft](https://img.shields.io/badge/Microsoft-AI%20%26%20ML%20Engineering-00A4EF?logo=microsoft&logoColor=white)
![IBM](https://img.shields.io/badge/IBM-Generative%20AI%20Engineering-052FAD?logo=ibm&logoColor=white)
![IBM](https://img.shields.io/badge/IBM-AI%20Developer%20Professional-052FAD?logo=ibm&logoColor=white)
![Imperial College London](https://img.shields.io/badge/Imperial%20College%20London-Advanced%20Android%20Dev-003E74)
![Google](https://img.shields.io/badge/Google-IT%20Support-4285F4?logo=google&logoColor=white)

<br/>

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.shion.dev/api?username=obligator11&theme=dark&hide_border=false&include_all_commits=false&count_private=false" />
<img height="165" src="https://github-readme-stats.shion.dev/api/top-langs/?username=obligator11&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact" />

<br/>

<img src="https://streak-stats.demolab.com/?user=obligator11&theme=dark&hide_border=false" />

</div>

<br/>

## ✍️ Random Dev Quote

<div align="center">

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=gruvbox" />

</div>

<br/>

## 🌐 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sayyam-shahbaz-dev)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://www.instagram.com/obligator11/)

</div>
