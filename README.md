<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=220&section=header&text=Prakhar%20Rampalli&fontSize=42&fontColor=ffffff&fontAlignY=45&desc=Backend%20Engineer%20%C2%B7%20AI%20Infrastructure%20%C2%B7%20MBA%20Candidate%202027&descAlignY=68&descSize=16&animation=fadeIn"/>
</p>

<!-- Social Badges -->
<p align="center">
  <a href="https://linkedin.com/in/prakhar-rampalli">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:rampalliprakhar@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://prakhar-portfolio-ysrj.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>
  <a href="https://pypi.org/project/contradict-text">
    <img src="https://img.shields.io/badge/PyPI-contradict--text-1D9E75?style=for-the-badge&logo=pypi&logoColor=white"/>
  </a>
</p>

---

<!-- About -->
```yaml
name: Prakhar Rampalli
role: Backend Engineer · AI Infrastructure
education:
  degree: B.S. Computer Science - Summa Cum Laude
  university: Francis Marion University
  gpa: 3.97
  next: Full-Time MBA Candidate, Class of 2027
focus:
  - Fault-tolerant ingestion pipelines at scale
  - Semantic search and RAG systems built from components
  - Local LLM inference for privacy-sensitive applications
  - Healthcare AI and biomedical information retrieval
by_the_numbers:
  - 36M PubMed abstracts indexed with FAISS IVFPQ
  - 7000+ healthcare policy documents: zero failed-load incidents
  - 1 hour to 2 minutes compliance search time at McLeod Health
  - contradict-text published to PyPI
currently: Building at the intersection of backend engineering and AI infrastructure
```

---

## What I build

Backend systems where data infrastructure meets intelligent retrieval: fault-tolerant ingestion pipelines, semantic search at scale, and RAG systems built from components, not frameworks.

---

## Featured projects

### [contradict-text](https://pypi.org/project/contradict-text) · PyPI Library
`Python · NLI · BGE Embeddings · cross-encoder/nli-deberta-v3-small`

Semantic contradiction detection for text pairs. Two-stage design: topic similarity filter (BGE cosine) skips unrelated pairs before running the NLI model, keeping inference fast on real retrieval outputs. Built for RAG pipelines where retrieved sources disagree.

```bash
pip install contradict-text
```

---

### [PV RAG](https://github.com/rampalliprakhar/PV-RAG) · Pemphigus Vulgaris Literature Q&A
`Python · FAISS · BGE Embeddings · Cross-encoder Reranking · Mistral 7B · Gradio · SQLite · NCBI API`

Local, offline RAG system for a rare autoimmune disease. Indexes 12,000+ PubMed abstracts and PMC full-text papers. Patients ask questions in plain English, log daily symptoms and foods, and see which foods correlate with flares: all cross-referenced against the medical literature automatically. No health data leaves the machine.

---

### [Local RAG](https://github.com/rampalliprakhar/Local-RAG) · Semantic Q&A Over Your Own Documents
`Python · FAISS · BGE Embeddings · Cross-encoder Reranking · Mistral 7B · Gradio`

Offline RAG pipeline over personal documents. Auto-selects FAISS flat vs IVFPQ by dataset size (IVFPQ underperforms below ~3,900 chunks). Two-stage retrieval: FAISS top-50 candidates then cross-encoder reranking then top-5. Runs on 16GB RAM, CPU only, no API key required.

---

### [PolicyHealthAI](https://github.com/campbell-frost/policy-health-go) · Healthcare Policy Search Platform
`Go · PostgreSQL · pgvector · MinIO · OpenAI · React`

Backend for an AI-powered policy search platform. Chose pgvector over a dedicated vector DB to keep retrieval and relational metadata in one PostgreSQL instance, eliminating cross-service latency. Go services handle ingestion, embedding, and natural-language compliance queries at scale. 

---

### [VR Mock Interview](https://vrmi.vercel.app/) · Offline AI Interview Simulator
`Unity · C# · LLMUnity · LLaMA 3.2 · Overtone TTS · Undertone STT`

Fully offline VR interview simulator for Meta Quest. STT to LLaMA 3.2 to TTS voice pipeline engineered to sub-9s latency by moving LLM inference off the audio thread to prevent avatar freeze. Presented at FMU Research and Exhibition Day.

---

## Core stack

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" alt="Go" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="C#" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" alt="Next.js" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" alt="FastAPI" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" alt="Google Cloud" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" alt="SQLite" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/unity/unity-original.svg" alt="Unity" width="40" height="40"/>
</p>

---

## GitHub stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=rampalliprakhar&theme=github_dark" width="100%"/>
</p>
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=rampalliprakhar&theme=github_dark" height="160"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=rampalliprakhar&theme=github_dark" height="160"/>
</p>
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=rampalliprakhar&theme=github_dark" height="160"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=rampalliprakhar&theme=github_dark&utcOffset=-5" height="160"/>
</p>

---

<!-- FOOTER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=80&section=footer"/>
</p>
