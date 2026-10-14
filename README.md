# Hi, I'm Prakhar 👋

### AI Engineer | LLM Agents • RAG • AI Automation • Backend Systems

> 🟢 **Available for freelance and contract work** - RAG systems, AI agents, n8n / AI automation, and AI code evaluation. Email: [amanpratapsingh1999@gmail.com](mailto:amanpratapsingh1999@gmail.com)

I build production-oriented AI systems that combine **LLMs, RAG, agents, APIs, and automation** to solve real engineering and business problems.

My focus is on turning AI capabilities into reliable software — with structured architectures, evaluation, observability, APIs, testing, and deployment in mind.

---

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/Qdrant-DC2626?style=for-the-badge&logo=qdrant&logoColor=white" alt="Qdrant" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

---

## 🚀 What I Build

- 🤖 **Autonomous Multi-Agent Systems** — Deterministic state-graph agents, reflection loops, and adversarial stress-testing.
- 🔎 **Enterprise RAG Architectures** — Page-bounded chunking, dense vector retrieval, and verbatim clause-level citations.
- ⚡ **High-Throughput AI Backends** — Async FastAPI microservices, Redis caching/streams, and task queues.
- 📄 **Document Intelligence Platforms** — Multi-document classification, entity extraction, and policy-driven human approval gates.
- 🛠️ **AI Automation & Orchestration** — Self-healing workflows, tool-use grounding, and operational audit telemetry.
- 📊 **Empirical Evaluation & Benchmarking** — Retrieval hit rate, answer faithfulness, citation validity, and latency scorecards.

---

## ⭐ Featured Projects

### ⚖️ [ClauseIQ RAG](https://github.com/amanpratap1999/clause-iq-rag)
**Enterprise Policy & Contract Q&A Assistant with Clause-Level Provenance**

A production-oriented RAG system for legal contracts, HR policies, and compliance manuals. Enforces strict page-bounded document chunking and pairs embedded Qdrant vector search with verification logic to guarantee verifiable clause citations without hallucinations.

- **Key Highlights:** Embedded disk-persisted Qdrant (zero external SaaS dependency), interactive chat UI, and FastAPI backend.
- **Benchmark Scorecard:** **91.7%** Retrieval Hit Rate • **83.3%** Answer Faithfulness • **100.0%** Citation Validity • **3.73 ms** Mean Query Latency.
- **Tech:** Python • FastAPI • Qdrant Embedded • SentenceTransformers • PyPDF2 • Vanilla JS UI

---

### 🧠 [Multi-Agent AI Research Platform](https://github.com/amanpratap1999/multi-agent-ai-research-platform)
**Autonomous Research Pipeline with Dual Guardrails & Adversarial Red Teaming**

An enterprise-grade multi-agent autonomous research system powered by a 4-agent LangGraph state machine (**Search → Summarize → Write → Verify**). Features dual-boundary AWS Bedrock Guardrails, sub-12ms pgvector semantic caching, and a PyRIT adversarial stress-testing harness with a live War Room dashboard.

- **Key Highlights:** Strict XPIA prompt-injection quarantine, empirical citation audits with auto-retry loops, and lossless SSE event telemetry over Redis Streams.
- **Tech:** Python • LangGraph • FastAPI • PostgreSQL (pgvector) • Redis Streams • FastEmbed • PyRIT

---

### 🎫 [TriageFlow Agent](https://github.com/amanpratap1999/triage-flow-agent)
**Autonomous Support Incident Triage & Multi-Tool Resolution Agent**

An intelligent incident triage agent that deterministically classifies customer tickets, executes actions via verified tool calling (orders, accounts, refunds), and safely routes high-risk or ambiguous requests to human supervisors with diagnostic context.

- **Key Highlights:** Deterministic graph state machine preventing runaway loops, interactive web ops console, and zero false auto-resolutions.
- **Benchmark Scorecard:** **100.0%** Routine Resolution • **100.0%** Correct Escalation • **0.0%** False Resolution Rate • **0.07 ms** Processing Latency.
- **Tech:** Python • FastAPI • SQLite • Deterministic Graph Engine • Web Ops UI

---

### 📋 [DocFlow Orchestrator](https://github.com/amanpratap1999/docflow-orchestrator)
**Intelligent Document Processing & Workflow State Machine**

An enterprise document automation platform that ingests unstructured business PDFs, classifies document types, extracts validated operational entities, enforces deterministic policy-driven human approval gates, and dispatches automated downstream integration tasks.

- **Key Highlights:** Dual runtime architecture featuring an interactive Streamlit Ops Console alongside an async FastAPI backend with SQLite audit trails.
- **Benchmark Scorecard:** **100.0%** Classification Accuracy • **100.0%** Field Extraction • **0.0%** False Auto-Approvals • **7.98 ms** Latency.
- **Tech:** Python • FastAPI • Streamlit • Finite State Machine • Pydantic • SQLite

---

### 🎙️ [MeetPulse AI](https://github.com/amanpratap1999/meetpulse-ai)
**Enterprise Meeting Intelligence & Action Item Extraction Engine**

High-throughput intelligence service that transforms unstructured multi-speaker meeting transcripts into structured action items with verified speaker attribution, explicit deadline extraction, and cross-meeting semantic search.

- **Key Highlights:** Cosine similarity vector search over transcript segments, REST API with Swagger documentation, and automated database sync.
- **Benchmark Scorecard:** **92.8%** Extraction F1 • **100.0%** Recall • **0.81s** Processing Latency.
- **Tech:** Python • FastAPI • SQLite / SQLAlchemy • Cosine Vector Search • Pydantic

---

### 🤖 [ServiceNow Autonomous QA Agent](https://github.com/amanpratap1999/UAT_poc)
**Vision-Guided Autonomous Testing Runtime for Enterprise Workflows**

An AI-first testing platform that converts natural language business goals into autonomous browser testing plans. Decouples LLM reasoning from browser execution using Playwright, perception routing, visual grounding, and automated defect accounting.

- **Key Highlights:** Dual runtime (Local Headed Browser with smooth cursor tracking vs. Docker Headless CI), automated recovery engine, and detailed diagnostic reporting.
- **Tech:** Python • FastAPI • Celery • Redis • Playwright • PostgreSQL • React/Vite Dashboard

---

## 🧰 Tech Stack

| Category | Technologies & Tools |
|---|---|
| **AI / LLM & Agents** | LangGraph, LangChain, RAG Pipelines, Prompt Engineering, Guardrails, PyRIT Red Teaming, Semantic Caching |
| **Vector & Retrieval** | Qdrant (Embedded & Server), PostgreSQL (pgvector), FastEmbed ONNX, Dense Embeddings, Hybrid Search |
| **Backend & APIs** | Python 3.11+, FastAPI, Pydantic v2, AsyncIO, Celery, RESTful API Design, SSE (Server-Sent Events) |
| **Data & Storage** | PostgreSQL, Redis, Redis Streams, SQLite, SQLAlchemy, Alembic |
| **DevOps & Testing** | Docker, Docker Compose, GitHub Actions CI/CD, Pytest, Playwright, Linux / Windows |
| **Frontend & UI** | Streamlit, React / Vite, TailwindCSS, Vanilla JS Web UIs |

---

## 📈 Engineering Philosophy

I care about more than getting an LLM to produce an answer.

I focus on building AI systems that are:

- 🛡️ **Reliable & Guarded** — Guardrails against prompt injections, deterministic fallbacks, and human-in-the-loop gating for critical actions.
- 📐 **Empirically Evaluated** — Quantified against ground-truth benchmarks for hit rate, faithfulness, citation validity, and latency.
- 🔍 **Observable & Auditable** — Comprehensive step-by-step telemetry, execution traces, structured logs, and audit logs.
- 🧪 **Test-Driven** — Strict unit, integration, and end-to-end testing with continuous integration verification on every commit.
- 🧱 **Modular & API-First** — Decoupled reasoning, storage, and presentation layers exposed via clean OpenAPI/FastAPI contracts.

---

## 🤝 Let's Connect

I'm interested in building ambitious AI products, autonomous agentic systems, and production-grade AI infrastructure.

- 📧 **Email:** [amanpratapsingh1999@gmail.com](mailto:amanpratapsingh1999@gmail.com)
- 🐙 **GitHub:** [@amanpratap1999](https://github.com/amanpratap1999)
- 📍 **Location:** India

---

## 📌 Current Focus

Building intelligent systems where **LLMs + agents + retrieval + automation** come together to solve real-world problems.
