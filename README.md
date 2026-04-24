# Luis Valencia
**Microsoft MVP AI** (2015-2025) | **Author: "Mastering Scikit-Learn and PyTorch"** | **Senior AI Engineer | Multi-Agent Systems**

<p align="left">
  <a href="https://www.linkedin.com/in/levalencia/" target="_blank"><img src="https://img.shields.io/badge/Linkedin-Follow%20levalencia-blue?logo=linkedin&style=flat" /></a>
  <a href="https://medium.com/@luisevalencia" target="_blank"><img src="https://img.shields.io/badge/Blog-medium.com%2F%40luisevalencia-blue?logo=medium&style=flat" /></a>
  <img src="https://komarev.com/ghpvc/?username=levalencia&label=Profile%20views&color=0e75b6&style=flat" alt="levalencia" />
</p>

---

## 🔥 Currently Working On

### 🧠 Production AI Systems (Professional Work)

| Project Type | Business Problem Solved | Tech Stack |
|--------------|-------------------------|------------|
| **Hybrid Redaction Engine** | Privacy compliance - automatically detect and redact PII, legal, financial entities from documents with 99%+ accuracy using combined Regex + LLM reasoning | Azure OpenAI, Regex, Docker, Azure DevOps, CI/CD |
| **Agentic RAG Orchestrator** | Enterprise knowledge access - autonomous multi-agent system that retrieves, ranks, and synthesizes answers from private knowledge bases | OpenAI Agents SDK, FastAPI, Azure AI Search, Redis, Semver |
| **Multi-Agent PDF Pipeline** | Data extraction from complex documents - transforms unstructured biotech PDFs (clinical trials, regulatory filings) into structured datasets for analysis | Azure Document Intelligence, Azure OpenAI, Databricks, Docker |
| **Editorial AI Platform** | Publishing automation - real-time document redaction for editorial teams with sub-second responsiveness | SvelteKit, FastAPI, Docker, Azure DevOps, CI/CD |

**Engineering Practices Across All Projects:**
- ✅ CI/CD Pipelines (Azure DevOps)
- ✅ Semantic Versioning with automated git tagging
- ✅ Docker containerization (ACR deployment)
- ✅ Infrastructure-as-Code
- ✅ Clean Architecture (Domain-first, SOLID principles)
- ✅ OpenTelemetry observability

### 🛠️ Personal Projects

| Project | Problem Solved | Tech |
|---------|---------------|------|
| **HarmoniqHub** | Music organization for DJs: manual playlist building is time-consuming, inconsistent track ordering, no intelligent suggestions. Solves: AI-powered playlist generation, automatic track ordering (energy/key compatibility), wave visualization, set management, duplicate detection via acoustic fingerprinting | SwiftUI, SwiftData, CoreML, Chromaprint, Azure Table Storage |
| **SuperTradingGodMode** | Trading strategy optimization is what hyperparameter tuning is to ML - manual backtesting is slow, prone to overfitting. Solves: Parameterized strategy definition, automated walk-forward optimization, anti-lookahead validation, IS/OOS regime detection | React, TypeScript, FastAPI, Redis, RQ, Parquet, Pytest, Docker |
| **apple-silicon-llm-stack** | Want to run LLaMA/Mistral locally on Mac but inference is slow, context windows are limited. Solves: Custom Metal GPU shaders for 8x speedup, Q4 quantization for 70B models in 24GB RAM, LoRA fine-tuning via MLX | Python, MLX, C++, Metal, Go, SvelteKit |
| **DidListen** | Want to track what you listen during the day but existing apps don't capture speaker context. Solves: Real-time speech-to-text, speaker identification, turn detection for meeting notes, voice activity detection | Swift 6, WhisperKit, ShazamKit, Clean Architecture |

---

### 🛠️ Tech Stack

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![MLX](https://img.shields.io/badge/-MLX-000000?style=flat&logo=apple&logoColor=white)
![LangChain](https://img.shields.io/badge/-LangChain-2ECC71?style=flat)
![HuggingFace](https://img.shields.io/badge/-HuggingFace-FDC021?style=flat&logo=huggingface&logoColor=black)
![vLLM](https://img.shields.io/badge/-vLLM-000000?style=flat)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat&logo=go&logoColor=white)
![Swift](https://img.shields.io/badge/-Swift-FA7343?style=flat&logo=swift&logoColor=white)
![CoreML](https://img.shields.io/badge/-CoreML-000000?style=flat&logo=apple&logoColor=white)
![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat&logo=redis&logoColor=white)

**Python | PyTorch | MLX | LangChain | HuggingFace | vLLM | Go | React | TypeScript | FastAPI | Swift | CoreML | Azure ML | Redis**

---

## 📂 Featured Projects

### 🏆 apple-silicon-llm-stack
> **Problem:** Cloud LLM inference is expensive ($/hour), running locally on Mac is slow, context windows are limited, and 70B models require expensive GPUs.
> **Solution:** Hardware/software co-design for Apple Silicon — runs 70B models in 24GB RAM with extreme optimization.

**Technical Implementation**
- **Custom Metal Shaders** — CUDA-equivalent GPU compute kernels for 8x inference speedup
- **Q4 Quantization** — compresses 70B model to fit in 24GB unified memory
- **LoRA/QLoRA Fine-tuning** — 99% memory reduction via MLX
- **Go API Gateway** — sub-millisecond latency with CGO zero-copy bridge
- **SvelteKit Telemetry UI** — real-time SSE streaming dashboard

---

### 🧠 HarmoniqHub (macOS App)
> **Problem:** DJs waste hours manually organizing playlists, inconsistent track ordering, no intelligent suggestions, can't visualize energy/waves for sets.
> **Solution:** AI-powered playlist generation with energy/key compatibility, automatic track ordering, and wave visualization.

**Technical Implementation**
- **AI Playlist Generation** — intelligent curation based on energy, key (Camelot wheel), and mood
- **CoreML Classification** — genre, mood, theme detection trained on 500K+ tracks
- **Wave Visualization** — real-time audio waveform display for set planning
- **ShazamKit + Chromaprint** — acoustic fingerprinting for duplicate detection
- **Meta-tagging Automation** — automatic album/artist/label cleaning
- **Azure Table Storage** — <100ms cache response times

---

### ⚡ SuperTradingGodMode
> **Problem:** Manual trading backtesting is slow, prone to overfitting, and lacks proper IS/OOS validation — exactly what hyperparameter tuning is to ML.
> **Solution:** Parameterized strategy definition with automated walk-forward optimization and anti-lookahead validation.

**Technical Implementation**
- **Frontend:** React · TypeScript · Vite · lightweight-charts · TanStack Query · Zustand
- **Backend:** FastAPI · Pydantic v2 · SQLAlchemy
- **Data:** Parquet · Redis · RQ worker
- **Infrastructure:** Docker Compose · Pytest · Vitest
- **Architecture:** Clean Architecture (Domain-first, SOLID principles)
- **Validation:** Anti-lookahead backtesting, walk-forward IS/OOS sweep mode, 36+ passing tests

---

### 🎧 DidListen (iOS App)
> **Problem:** Existing "what you listened" apps don't capture speaker context — just audio. Want to know WHO spoke, WHEN, and WHAT.
> **Solution:** Real-time speaker identification with turn detection — hybrid STT pipeline on device.

**Technical Implementation**
- **Speech-to-Text Pipeline (3 backends, switchable at runtime):**
  - Local: **Whisper** (Tiny 39MB / Base 150MB / Medium 500MB via WhisperKit)
  - Cloud: **Azure AI Speech API**
  - On-device: Apple **SFSpeechRecognizer**

- **Voice AI Features:**
  - **VAD** — RMS energy threshold with state machine
  - **Turn Detection** — SILENCE ↔ SPEAKING transition detection
  - **Speaker Recognition** — 256-dim deterministic embeddings + cosine matching
  - **Pre-roll Buffer** — 1-second circular buffer captures utterance start

- **Architecture:**
  - Swift 6 Strict Concurrency (async/await, @MainActor, Sendable)
  - Clean Architecture (Domain/Data/Presentation layers)
  - MVVM + ObservableObject pattern
  - SwiftData persistence

---

### 🧩 agent-god-mode
> **Problem:** Loading 2,300+ AI skills into an agent causes "Death by a Thousand Skills" — 30K+ tokens before you type anything, skyrocketing API costs, confusing responses.
> **Solution:** Local RAG with just-in-time skill injection — searches vault, retrieves only what it needs, saves 30K+ tokens per session.

**Technical Implementation**
- **Local Embeddings:** @xenova/transformers (CPU-only, no API keys required)
- **RAG Architecture:** Isolated skill vault hidden from agent's default prompt
- **Search:** Background Node.js worker calculates cosine similarity outside sandbox
- **Just-in-Time Injection:** Agent searches → gets top 3 matches → reads only relevant SKILL.md
- **Integration:** OpenCode and Claude Code compatible
- **Scale:** 2,300+ curated skills (Azure, ML, DevOps, etc.)

---

### 🔍 DuplicateFinder
> **Problem:** Simple filename matching misses true duplicates — renamed tracks, resized images, recompressed files are invisible.
> **Solution:** Multi-modal AI fingerprinting — acoustic + visual similarity detection beyond filenames.

**Technical Implementation**
- **Audio:** Chromaprint acoustic fingerprinting (matches even with different filenames/bitrates)
- **Images:**
  - **pHash** — perceptual hashing for near-identical images
  - **CLIP (ViT-L/14)** — vision-language model for semantic similarity ("this photo looks like that one")
- **Vector Search:** FAISS for billion-scale similarity in milliseconds
- **UI:** Streamlit interactive dashboard with side-by-side preview
- **Safety:** One-click undo, trash manager, exportable reports

---

## 📫 Contact

📝 **Blog:** [medium.com/@luisevalencia](https://medium.com/@luisevalencia)  
💼 **Career:** [linkedin.com/in/levalencia](https://www.linkedin.com/in/levalencia)

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=levalencia&count_private=true&show_icons=true&theme=react&include_all_commits=true&hide=contribs" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=levalencia&theme=gruvbox&margin-w=15&margin-h=15&column=8" />
</p>