<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FDFBF7,35:F5EBE1,70:EADBC8,100:DAC0A3&height=180&section=header&text=Projects%20%26%20Engineering%20Compendium&fontSize=36&fontColor=2D241E" alt="Projects Header" />
</p>

<p align="center">
  <a href="../README.md"><b>[ 🏠 Home Profile ]</b></a> •
  <a href="./PROJECTS.md"><b>[ 🧪 Projects Compendium ]</b></a> •
  <a href="./AI_DOMAIN.md"><b>[ 🧠 AI Domains ]</b></a> •
  <a href="./COLLAB.md"><b>[ 🤝 Collaboration ]</b></a> •
  <a href="https://himanshu.social" target="_blank"><b>[ 🌐 Portfolio ]</b></a>
</p>

---

<p align="center">
  <b>Comprehensive engineering index across high-throughput distributed systems, autonomous agentic runtimes, real-time speech AI pipelines, and scientific machine learning.</b>
</p>

## 📋 Complete Project Index

| Project | Primary Focus & Domain | Tech Stack | Status | Key Engineering Metric / Impact |
| :--- | :--- | :--- | :--- | :--- |
| [**LinkOps**](https://github.com/HIMpcgithub3000/linklops) | High-throughput multi-tenant URL redirector & analytics | Python, PostgreSQL RLS, Redis, `pg_trgm` | Production-Ready | Sub-3ms redirect latency via single-flight locks; 100% tenant partition under RLS. |
| [**Nexus**](https://nexus.blostem.com) | Autonomous agent dispatcher & incident triage runtime | TypeScript, MCP over SSE, Claude Code, SigNoz | Live Platform | 1,419-line runtime; slashed triage from 3 hrs to 10 mins; 700+ regression tests. |
| [**VoiceBrew**](https://voicebrew.ai) | Acoustic speech streaming telephony engine | Python, Twilio Trunking, Sarvam AI, ElevenLabs, Gemini 2.5 Flash | Live Platform | Sub-200ms audio stream (8k to 16kHz); 100% prompt injection defense across 5k+ tests. |
| [**AI PR Assistant**](https://github.com/HIMpcgithub3000/Ai_pr_assistant) | Multi-agent autonomous code inspection platform | Python, CrewAI, LangGraph, Kafka, Docker | Active | Kafka prioritized queue (`P0-P3`); Dockerized sandbox runner; zero hallucinated comments via AST gate. |
| [**NextFlow**](https://github.com/HIMpcgithub3000/nextflow) | Visual DAG builder & multimodal workflow engine | TypeScript, React Flow, Node.js topological runner | Active | Deterministic topological graph executor chaining Gemini vision & media workers. |
| [**SciML Epidemiological Forecasting**](https://github.com/HIMpcgithub3000/influenza-forecasting-hhs-regions) | Scientific ML: SINDy sparse discovery + Seasonal SEIRS ODE | Python, SciPy, SINDy, STLSQ, joblib | Completed | 47.6% lower RMSE vs. Prophet; symbolic ODE discovery with $L_0$ sparsity. |
| [**Quantitative Stock Forecasting**](https://github.com/HIMpcgithub3000/Quantitative_analysis_of_stocks) | Econometric modeling & GBDT walk-forward backtesting | Python, scikit-learn, ARIMA, TimeSeriesSplit | Completed | 2.12% out-of-sample MAPE across 11,325 OHLCV bars without lookahead bias. |
| [**TigerSentinel**](https://github.com/HIMpcgithub3000/TigerSentinel-Agentic-Fraud-Investigation) | Graph-first agentic fraud investigation | Python, TigerGraph Savanna Cloud, Agents | Active | Multi-hop subgraph query engine resolving synthetic identities and circular flows. |
| [**Razorpay RecoverAI**](https://github.com/HIMpcgithub3000/razorpay-recoverai) | Autonomous autopay failure recovery voice engine | TypeScript, Voice Telephony, Webhooks | Active | Real-time conversational recovery of failed subscription mandates with intelligent retries. |
| [**Vernacular FD Advisor**](https://github.com/HIMpcgithub3000/Vernacular-FD-Advisor) | Multilingual voice wealth advisor (15 Indian languages) | TypeScript, Web Speech API, FAISS, Python | Awardee | Citation-grounded RAG with deterministic tabular calculation tools across 100+ schemes. |
| [**MediMind**](https://github.com/HIMpcgithub3000/medimind) | Healthcare information retrieval & hybrid RAG | TypeScript, FAISS, ChromaDB, local Gemma 3 | Active | SSE streaming QA UI with cross-encoder reranking and citation-grounded outputs. |
| [**Glaucoma Detection**](https://github.com/HIMpcgithub3000/Glaucoma_Dectection_Machine_learning) | Explainable multimodal ophthalmic vision | PyTorch, CNNs, Grad-CAM, SHAP | Completed | 80% accuracy, 0.80 AUC across 2,800+ multimodal images with saliency maps. |
| [**NHCX Claim Extraction**](https://github.com/HIMpcgithub3000/NHCx) | Unstructured hospital claim PDF to HL7 FHIR R4 JSON | Python, PyMuPDF, Pydantic, local Gemma 3 | Finalist | Zero extraction errors across 150+ claims; National Hackathon Finalist. |

---

## 🏗️ Architecture & Technical Archetypes

### 1. High-Throughput & Fault-Tolerant Distributed Backend
- **PostgreSQL Row-Level Security (RLS):** Complete multi-tenant partition using PostgreSQL session attributes (`app.current_tenant_id`) ensuring mathematical zero data leakage between client records.
- **Single-Flight Redis Locks:** Distributed deduplication locks preventing multiple identical cache fetches under concurrent spike conditions.
- **Asynchronous Rollup Pipelines:** Decoupled background workers processing streaming events into hourly and daily summary partitions with idempotent primary keys.

### 2. Real-Time Telephony & Voice AI
- **Dual-Layer Guardrail Architecture:** Pre-flight sub-10ms deterministic regex scanner checking against prompt injection and jailbreak payloads, backed by post-inference semantic policy verification.
- **Acoustic Streaming & Telephony Synchronization:** Low-latency 8kHz to 16kHz audio upsampling pipeline communicating over Twilio SIP trunks with sub-200ms round-trip latency.

### 3. Scientific ML & Deterministic Agent Workflows
- **Nonlinear Dynamics Sparse Discovery (SINDy):** Extracting physical governing equations from empirical time-series data using Sequential Thresholded Least Squares (STLSQ), preventing simulation decay.
- **Zero-Trust AST Evidence Gate:** Multi-agent review gate resolving AST parse trees directly against filesystem disk references to verify function signatures before executing comments.

---

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=HIMpcgithub3000&background=FFFBF5&border=E6D5C3&stroke=A27B5C&ring=C88A58&fire=C88A58&currStreakLabel=78350F&currStreakNum=3F2E21&sideNums=3F2E21&sideLabels=8D7B68&dates=8D7B68" alt="GitHub contribution streak" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:DAC0A3,50:EADBC8,100:FDFBF7&height=80&section=footer" alt="Footer" />
</p>
