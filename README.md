<h1 align="center">Hey, I'm Sabhari Sriram 👋</h1>

<p align="center">
  <b>AI/ML Engineer · RAG Pipelines · LLM Applications · Production Deployments</b><br/>
  <sub>B.Tech Artificial Intelligence & Data Science · Karpagam College of Engineering · 2026</sub>
</p>

<p align="center">
  <a href="https://sabhari-sriram.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Visit-FF5733?style=flat-square&logo=vercel&logoColor=white"/></a>
  <a href="mailto:sabharisriram@gmail.com"><img src="https://img.shields.io/badge/Email-sabharisriram%40gmail.com-blue?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/sabhari-sriram"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
</p>

---

> 🚀 **Open to full-time AI/ML Engineer roles — May 2026**  
> I build AI systems that work in production: RAG pipelines, real-time data, containerized microservices.

---

## 🧠 About Me

AI & Data Science graduate passionate about closing the gap between research and production. I've shipped real LLM-powered applications — multi-user RAG systems, real-time financial sentiment pipelines, and deep learning models — using tools like **FastAPI**, **Docker**, **Kafka**, and **HuggingFace Transformers**.

- 🔭 Currently building: **Payanam** (latest project — JavaScript)
- 🌱 Learning: Advanced agentic AI systems & multi-modal LLMs
- 💬 Ask me about: RAG pipelines, LLM deployment, Kafka microservices
- 📍 Based in Tamil Nadu, India

---

## 🛠️ Tech Stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**ML / Deep Learning**  
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**AI / LLM**  
![LangChain](https://img.shields.io/badge/RAG%20Pipelines-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-4267B2?style=flat-square&logo=meta&logoColor=white)

**Backend & APIs**  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**Cloud & Deployment**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![HuggingFace Spaces](https://img.shields.io/badge/HF%20Spaces-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

---

## 🚀 Featured Projects

### 🌑 [Shadow LLM Platform](https://github.com/Sabharisriram/shadow-llm-platform)
> Production-grade MLOps platform to validate a new LLM on live traffic before cutover — zero user impact

- **Shadow deployment engine** — mirrors every production request to a candidate model asynchronously, response never shown to users
- Dual scoring via **sentence-transformers (MiniLM-L6-v2)** semantic similarity + **NLTK BLEU-4** lexical scoring on a `ThreadPoolExecutor`
- **Auto-promotion engine** with 3 pluggable strategies (Conservative / Aggressive / Rollback) — adjusts traffic 0% → 100% using a 1-hour rolling PostgreSQL window, every 5 mins
- Full observability: **structlog** JSON + **Prometheus** (5 metric families) + **OpenTelemetry** OTLP spans + **Grafana** 4-panel dashboard
- Hermetic test suite — 64 tests with in-memory SQLite, zero external services, zero ML model downloads

`Python` `FastAPI` `PostgreSQL` `Redis` `Docker Compose` `Prometheus` `Grafana` `React` `MLOps`

---

### 🤖 [AI Study Assistant](https://github.com/Sabharisriram/ai-study-assistant)
> Multi-user RAG application — upload PDFs/images, get context-aware answers powered by LLMs

- Built with **FastAPI + Streamlit + Groq (LLaMA 3.1 8B)**
- Semantic vector search using **Qdrant Cloud + FastEmbed** with per-user document isolation
- Deployed on **HuggingFace Spaces** (Docker backend) + **Streamlit Cloud** (frontend)
- Auth via **Supabase** — fully production-ready and publicly accessible

`Python` `FastAPI` `RAG` `Qdrant` `Docker` `Supabase` `LLaMA`

---

### 📈 [Real-Time Financial Sentiment Analyzer](https://github.com/Sabharisriram/financial-sentiment-analyzer)
> End-to-end containerized sentiment pipeline delivering live Bullish / Bearish / Neutral signals

- **Apache Kafka** producer/consumer architecture for real-time news ingestion
- **Ollama (Llama 3)** + **FAISS** for contextual sentiment scoring with natural-language justifications
- 5 microservices orchestrated via **Docker Compose** — live web dashboard output

`Python` `Kafka` `Ollama` `FAISS` `Docker Compose` `FastAPI` `Microservices`

---

### 🧬 [mRNA Degradation Prediction](https://github.com/Sabharisriram/mRNA-degradation)
> Deep learning model for per-nucleotide degradation rate prediction — vaccine stability research

- **3-layer stacked GRU** architecture with domain-specific feature engineering
- End-to-end pipeline: JSON parsing → tokenization → 3D NumPy arrays
- Improved generalization across variable-length RNA sequence distributions

`Python` `TensorFlow` `GRU` `NumPy` `Bioinformatics`

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Sabharisriram&show_icons=true&theme=github_dark&hide_border=true&count_private=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sabharisriram&layout=compact&theme=github_dark&hide_border=true" height="150"/>
</p>

---

## 🏅 Certifications

- 🐍 **Python for Data Science** — IBM (July 2023)
- 🤖 **Artificial Intelligence Fundamentals** — IBM (October 2023)
- 📊 **Qlik Sense Business Analyst** — Qlik (September 2023)

---

## 💼 Experience

**Machine Learning Intern** · DataReveal, Coimbatore *(March 2025 – August 2025)*  
Built preprocessing pipelines, trained & evaluated ML models (Scikit-learn, TensorFlow, HuggingFace), containerized deployments with Docker.

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Sabharisriram&color=58a6ff&style=flat-square&label=Profile+Views"/>
</p>

<p align="center">
  <i>⚡ "Ship it, measure it, improve it."</i>
</p>
