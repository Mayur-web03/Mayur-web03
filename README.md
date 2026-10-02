# Mayur Choudhary

**B.Tech Computer Science & Engineering (3rd Year) · AI / ML & Full-Stack Engineering**

[LinkedIn](https://www.linkedin.com/in/mayur-choudhary-69937635b/) · [GitHub](https://github.com/Mayur-web03)

> I build AI systems that turn messy real-world data (industrial documents, blockchain transactions) into explainable, decision-ready intelligence.

---

## At a Glance

| Metric | Value |
|---|---|
| Public repositories | 26 |
| Flagship projects | 3 (Industrial Nexus, CryptoTrace, FluxMind AI) |
| Hackathon / competition builds | 3 (team hackathon, SIH 2026, Frontend Battle 2026) |
| Live deployed demos | 3 |
| AI agents designed | 5 (Industrial Nexus) |
| REST API endpoints / modules | 6 endpoints + 5 modules |
| Languages / frameworks | Python, TypeScript, JavaScript, FastAPI, Next.js, React |

---

## Projects

### 1. Industrial Nexus — AI-Powered Industrial Knowledge Intelligence Platform
*Hackathon submission · Team of 2 (with Shailesh Madane) · 33 commits*

[Live Demo](https://industrial-knowledge-brain.vercel.app/) · [Repository](https://github.com/Mayur-web03/industrial-knowledge-brain-)

Unifies fragmented plant documentation (drawings, maintenance records, SOPs, inspection and compliance files) into one continuously updated knowledge graph, queried through a RAG copilot.

| Dimension | Detail |
|---|---|
| AI agents | **5** (Planner, Retriever, RCA, Compliance, Validator) plus a Lessons-Learned engine |
| Solution modules | **5** sharing one knowledge graph |
| Features | **10** (upload, email auto-sync, copilot, graph explorer, hybrid search, predictive maintenance, compliance, lessons learned, analytics, RBAC) |
| API endpoints | **6** (`/upload`, `/query`, `/graph`, `/audit`, `/maintenance/recommendations`, `/compliance/gaps`) |
| Stack layers | **12** (Next.js, FastAPI, LangChain/LangGraph, Groq Llama 3.3 70B, Tesseract, BGE-Large, ChromaDB, Neo4j, PostgreSQL, AWS S3, Docker, Kubernetes) |

**Design targets** (engineering goals, not yet measured benchmarks)

| Metric | Target |
|---|---|
| OCR accuracy | > 95% |
| Query response time | < 2 sec |
| Citation accuracy | > 98% |
| Graph link accuracy | > 92% |
| Retrieval precision | > 90% |
| Document processing | < 10 sec |

**Projected business impact:** information search 35 min → 20 sec · root-cause analysis 3 hrs → 15 min · compliance preparation 2 days → 20 min.

---

### 2. CryptoTrace — Cyber-Crime Crypto Investigation Platform
*Smart India Hackathon (SIH) 2026*

[Live Demo](https://cryptotrace-self.vercel.app) · [Frontend](https://github.com/Mayur-web03/sih) · [Backend](https://github.com/Mayur-web03/sih-backend)

A platform for investigators to trace stolen or suspicious cryptocurrency across wallets, score risk, attribute exchanges, and produce evidence-grade reports.

| Dimension | Detail |
|---|---|
| Core features | **14** (multi-hop tracing, risk scoring, VASP attribution, case management, evidence and chain of custody, report generation, freeze workflow, and more) |
| Investigation workflow | **12 steps**, from complaint received to freeze request |
| Risk indicators | **6** (transaction velocity, fan-in/fan-out, hop count, transaction errors, fund volume, suspicious patterns) |
| API modules | **5** (Cases, Transactions, Freeze Requests, Reports, Investigation) |
| Freeze workflow states | **4** (Pending, Under Review, Approved/Rejected, Executed), with a full audit trail |
| Stack | FastAPI, Supabase/PostgreSQL, Ethereum data, Pandas, ReportLab, React + TypeScript (Vite) |

---

### 3. FluxMind AI — AI Workflow Automation Landing Platform
*Frontend Battle Hackathon 2026 · 10 commits*

[Live Demo](https://fluxmind-ai-tau.vercel.app/) · [Repository](https://github.com/Mayur-web03/fluxmind-ai)

| Dimension | Detail |
|---|---|
| Hackathon objectives met | **5** (dynamic pricing matrix, context-preserving layouts, native motion, semantic architecture, type safety) |
| Pricing tiers | **3** (Starter 100, Pro 200, Enterprise 500), configuration-driven |
| Animation libraries used | **0** (CSS + Web Animations API only) |
| Stack | Next.js (App Router), React, TypeScript, CSS Modules, Vercel |

---

### 4. Other Work
- [vendor-connect](https://github.com/Mayur-web03/vendor-connect) — CSS-based vendor platform front end

---

## Research Segment

My research interest is **trustworthy, explainable AI over structured and unstructured real-world data**. Each project above is a testbed for one of the questions below.

| # | Research Question | Where I explore it | Status |
|---|---|---|---|
| 1 | Does **hybrid retrieval** (vector search + knowledge-graph traversal) beat vector-only RAG on multi-hop industrial queries? | Industrial Nexus | Architecture built; benchmark evaluation planned |
| 2 | How can LLM answers be made **verifiable** through citations, confidence scores and graph paths? | Industrial Nexus (target: citation accuracy > 98%) | Implemented; accuracy measurement planned |
| 3 | Can **explainable, behaviour-based risk scores** (6 indicators) help trace illicit fund flows across multi-hop wallet chains? | CryptoTrace | Prototype built; validation on labelled data planned |
| 4 | How should attribution be reported responsibly (**"potential/likely VASP"** instead of confirmed)? | CryptoTrace | Design principle implemented |
| 5 | Can **agentic pipelines** (Planner → Retriever → Validator) reduce hallucination in low-latency LLM inference (Groq, Llama 3.3 70B)? | Industrial Nexus | Implemented; ablation study planned |

**Research methods and skills:** RAG, knowledge graphs, vector search, CNN-based binary classification, image preprocessing, OCR/NLP pipelines, graph analytics, explainable AI, model deployment via REST APIs.

**Planned evaluation:** precision@k and latency comparison of vector-only vs hybrid retrieval, citation-accuracy audit, and risk-score validation against labelled transaction data. Targets above will be replaced with measured results as experiments complete.

**Publications / papers:** *add here, or write "in preparation"*

---

## Technical Skills

| Area | Tools |
|---|---|
| ML / AI | Python, TensorFlow, Keras, NumPy, LangChain, LangGraph, RAG |
| Backend | FastAPI, Node.js, PostgreSQL, Supabase, Neo4j, ChromaDB |
| Frontend | React, Next.js, TypeScript, JavaScript, Tailwind CSS |
| DevOps | Docker, Kubernetes, AWS S3, Vercel, Render |

---

## Contact

- GitHub: [Mayur-web03](https://github.com/Mayur-web03)
- LinkedIn: [Mayur Choudhary](https://www.linkedin.com/in/mayur-choudhary-69937635b/)
