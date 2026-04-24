# Luis Valencia

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

| Project | Focus |
|---------|-------|
| **HarmoniqHub** | Native macOS app with AI playlist generation, CoreML classification |
| **SuperTradingGodMode** | Trading research platform with backtesting/sweeps |
| **apple-silicon-llm-stack** | MLX fine-tuning, Metal shaders, Go API gateway |
| **DidListen** | iOS app with Whisper, VAD, Speaker Recognition |

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
> **4-project monorepo** - Full-stack ML pipeline for Apple Silicon optimization

| Sub-project | Tech | HR-Friendly Description |
|-------------|------|------------------------|
| **mlx-tuner** | Python · MLX | LoRA/QLoRA fine-tuning with 99% memory reduction - distributed training optimization |
| **metal-inference-core** | C++ · Metal | Custom GPU shaders - CUDA-equivalent low-level optimization for Apple Silicon |
| **go-llm-gateway** | Go · CGO | High-performance API gateway with zero-copy CGO bridge - sub-millisecond latency |
| **hardware-telemetry-ui** | SvelteKit · SSE | Real-time streaming telemetry dashboard with SSE |

### 🧠 HarmoniqHub (macOS App)
> Native SwiftUI music library with production ML pipelines

- **AI Playlist Generation**: Intelligent playlist curation using ML models
- **TensorFlow → MLX Conversion**: Optimized for Apple Silicon inference
- **CoreML Classification**: Genre, mood, and theme detection
- **ShazamKit + Chromaprint**: Acoustic fingerprinting for duplicate detection
- **Azure Table Storage**: <100ms cache response times
- **40% CPU Reduction**: Async audio processing with asyncio.Semaphore

### ⚡ SuperTradingGodMode
> **Production trading research & backtesting platform**

| Layer | Tech |
|-------|------|
| Frontend | React · TypeScript · Vite · lightweight-charts · TanStack Query · Zustand |
| Backend | FastAPI · Pydantic v2 · SQLAlchemy |
| Data | Parquet · Redis · RQ worker |
| Infrastructure | Docker Compose · Pytest · Vitest |

- Clean Architecture (Domain-first, SOLID principles)
- Anti-lookahead backtesting validation
- Walk-forward IS/OOS sweep mode
- 36+ passing tests

### 🎧 DidListen (iOS App)
> **Production-grade audio intelligence** with hybrid speech-to-text

**Speech-to-Text Pipeline** (3 backends, switchable at runtime)
- Local: **Whisper** (Tiny 39MB / Base 150MB / Medium 500MB via WhisperKit)
- Cloud: **Azure AI Speech API**
- On-device: Apple **SFSpeechRecognizer**

**Voice AI Features**
- **VAD** (Voice Activity Detection): RMS energy threshold with state machine
- **Turn Detection**: SILENCE ↔ SPEAKING transition detection for live segments
- **Speaker Recognition**: 256-dim deterministic embeddings with cosine matching
- **Pre-roll Buffer**: 1-second circular buffer captures utterance start

**Architecture**
- Swift 6 Strict Concurrency (async/await, @MainActor, Sendable)
- Clean Architecture (Domain/Data/Presentation)
- MVVM + ObservableObject pattern
- SwiftData persistence

**Why it matters**: Real-time audio intelligence on-device - not just transcription, but understanding WHO is speaking, WHEN they speak, and WHAT they say.

### 🧩 agent-god-mode
> **2300+ skill RAG vault** for AI coding agents

- Local embeddings using @xenova/transformers (CPU-only, no API keys)
- Vector similarity search for just-in-time skill injection
- OpenCode and Claude Code integration
- Solves context bloat when loading thousands of skills

### 📊 DataScience-Portfolio
> End-to-end ML pipelines and RAG systems

- **RAG Pipelines**: LangChain, Pinecone, Azure Cognitive Search
- **Fine-tuning**: DistilBERT, CNNs (Simpsons classifier)
- **Cloud**: Azure ML, Databricks
- **HuggingFace Transformers**: NLP, text classification

### 🔍 DuplicateFinder
> **Multi-modal deduplication** using vision AI

- **CLIP**: Vision-language model for semantic image similarity (understands "this photo looks like that one")
- **FAISS**: Billion-scale vector similarity search (finds nearest neighbors in milliseconds)
- **Chromaprint**: Audio acoustic fingerprinting
- **Streamlit UI**: Interactive visualization

### 🔎 deep-searcher
> **Deep research RAG** on private data

- Open Source alternative to commercial deep research tools
- Document ingestion, chunking, embedding
- Multi-hop reasoning over private knowledge bases

---

## 📊 Production Impact

| Achievement | Metric | Project | Client |
|-------------|--------|---------|--------|
| Defect classification | **98.3%** | ResNet-50 CNN QC system | PwC |
| API cost reduction | **30%** | Databricks pipeline | Argenx |
| Forecast accuracy | **92%** | Predictive maintenance | element61 |
| Waste reduction | **15%** | Early fault detection | PwC |
| Cache response | **<100ms** | Azure Table Storage | HarmoniqHub |
| CPU optimization | **40% reduction** | Async audio processing | HarmoniqHub |

---

## 🏆 Credentials

**Microsoft MVP AI** (2015-2025) | **Author: "Mastering Scikit-Learn and PyTorch"** | **10+ years in AI/ML**

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