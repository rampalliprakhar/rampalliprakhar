<h1 align="center">Prakhar Rampalli</h1>
<h3 align="center">Backend Engineer · Go · Python · PostgreSQL · RAG Pipelines · Vector Search</h3>

<p align="center">
  <a href="https://linkedin.com/in/prakhar-rampalli">LinkedIn</a> ·
  <a href="mailto:rampalliprakhar@gmail.com">Email</a> ·
  <a href="https://prakhar-portfolio-ysrj.vercel.app/">Portfolio</a>
</p>

---

## What I build

Backend systems where data infrastructure meets intelligent retrieval: fault-tolerant ingestion pipelines, semantic search at scale, and RAG systems built from components, not frameworks.

**By the numbers:**
- Indexed **36M+ PubMed abstracts** for semantic retrieval using FAISS IVFPQ
- Built ingestion pipeline for **7,000+ healthcare policy documents**: zero failed-load incidents
- Reduced manual processing effort **40%** through automated validation workflows
- Shipped **RBAC + multi-tenant isolation** before a compliance audit deadline

---

## Featured projects

### [PV RAG](https://github.com/rampalliprakhar/PV-RAG): Pemphigus Vulgaris Literature Q&A
`Python · FAISS · BGE Embeddings · Cross-encoder Reranking · Mistral 7B · Gradio · SQLite · NCBI API`

Local, offline RAG system for a rare autoimmune disease. Indexes 12,000+ PubMed abstracts and PMC full-text papers. Patients ask questions in plain English, log daily symptoms and foods, and see which foods correlate with flares: all cross-referenced against the medical literature automatically. Fully private: no health data leaves the machine.

---

### [Local RAG](https://github.com/rampalliprakhar/Local-RAG): Semantic Q&A Over Your Own Documents
`Python · FAISS · BGE Embeddings · Cross-encoder Reranking · Mistral 7B · Gradio`

Offline RAG pipeline over personal documents. Key decisions: auto-selects FAISS flat vs IVFPQ by dataset size (IVFPQ underperforms below ~3,900 chunks), two-stage retrieval with cross-encoder reranking after FAISS. Runs on 16GB RAM, CPU only, no API key required.

---

### [PolicyHealthAI](https://github.com/campbell-frost/policy-health-go): Healthcare Policy Search Platform
`Go · PostgreSQL · pgvector · MinIO · OpenAI · React`

Backend for an AI-powered policy search platform. Chose pgvector over a dedicated vector DB to keep retrieval and relational metadata in one PostgreSQL instance. Go services handle ingestion, embedding, and natural-language compliance queries at scale.

---

### [VR Mock Interview](https://vrmi.vercel.app/): Offline AI Interview Simulator
`Unity · C# · LLMUnity · LLaMA 3.2 · Overtone TTS · Undertone STT`

Fully offline VR interview simulator for Meta Quest. STT -> LLaMA 3.2 -> TTS voice pipeline engineered to sub-9s latency via multithreading: LLM inference moved off the audio thread to prevent avatar freeze.

---

## Core stack

| Layer | Tools |
|---|---|
| Languages | Go, Python, TypeScript, Java, C# |
| Databases | PostgreSQL, pgvector, FAISS, SQLite, MySQL |
| AI & Search | RAG, Semantic Search, Cross-encoder Reranking, LLMs, Vector DBs |
| Backend | Go (Gin), FastAPI, Node.js, Express |
| Frontend | Next.js, React, Tailwind CSS |
| Cloud & Tools | Docker, Google Cloud, MinIO, Vercel, GitHub |

---

## Available for work

Actively seeking **Backend SWE · AI Infrastructure · Data Platform** roles.
Available immediately · Open to remote or on-site across the US.

**B.S. Computer Science · Francis Marion University · GPA 3.97 · Summa Cum Laude**
