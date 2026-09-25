<p align="center">
  <img src="https://github.com/jalpatel11/jalpatel11/blob/c74e1520abcd61861410ccb90833d925ff245c0c/hii.gif" />
</p>

<h1 align="center">Hi, I'm Jal Patel 👋</h1>

<p align="center">
  <b>Junior Software Engineer @ Green Tanner Industrial</b> &nbsp;|&nbsp; <b>MS Data Science @ Arizona State University</b> &nbsp;|&nbsp; <b>Full-Stack & AI Builder</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jal-patel-swe/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/jalpatel11"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="mailto:jal85524@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://jalpatel.dev"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white" /></a>
</p>

---

## About Me

I finished my MS in Data Science, Analytics and Engineering at Arizona State University in May 2026 and now work as a Junior Software Engineer at Green Tanner Industrial. I've built production software systems, ML pipelines, and full-stack applications across internships, a full-time role, and side projects.

My work sits at the intersection of **software engineering**, **applied ML**, and **data engineering**. I care about building things that actually work in production, not just in notebooks.

- 🏢 Junior Software Engineer at **Green Tanner Industrial** (Chandler, AZ), building full-stack features and a RAG pipeline for an internal construction-management platform
- 🤖 Building **Harper**, a terminal coding agent in Go that works with five LLM providers
- 🔧 Built a self-healing SRE agent from scratch that fixes CI/CD failures on its own, with a 95% fix success rate
- 🌍 Open-source contributor to **GRASS GIS** (OSGeo), with three merged test-suite pull requests
- 📍 Based in Tempe, AZ

---

## Experience Highlights

### 💼 Green Tanner Industrial — Junior Software Engineer (Sep 2026 – Present)
- Build and maintain full-stack features for an internal construction-management platform, connecting field and office workflows through API integrations with tools including **Procore**
- Develop a **Retrieval-Augmented Generation (RAG)** pipeline for internal software, using retrieval and semantic search in a production AI system
- Work across **Rust**, WebAssembly, HTMX, Alpine.js, Tailwind CSS, and **PostgreSQL**, in a pair-programming and mentorship model with senior engineers

### 🧳 Integrated Travel — Data Scientist (Jun 2026 – Present)
- Researching a community-driven tourism and entertainment discovery platform for Central Alberta, focused on local events, attractions, transportation access, and grassroots economic development
- Supporting early-stage research on data sources, geospatial analysis, and AI-assisted workflows to improve tourism visibility for smaller communities

### 🤖 Sentari AI — Software Development Engineer Intern (Aug 2025 – Jan 2026)
- Architected **Python** backend microservices and **REST APIs** for an AI journaling app's transcription and emotion-analysis pipeline, reducing inference latency by **21%** across 30+ concurrent data streams during 200% month-over-month growth
- Shipped a React and Flask dashboard for monitoring Whisper transcription and journaling insight workflows, improving production visibility and cutting incident response time by **35%**
- Built an offline processing pipeline that eliminated data loss in journaling entries during connectivity failures, and implemented **OAuth2** authentication that improved token verification speed by **27%**

### 🏗️ Plexusnet Services — Software Engineer Intern (Jan 2024 – May 2024)
- Built scalable **Python**, **Django**, and **PostgreSQL** backend services for a documentation platform, tuning SQL indexing and query performance to speed up responses by **18%** across core features
- Streamlined **CI/CD** pipelines with **Docker**, **Kubernetes**, and GitHub Actions, cutting deployment errors by **30%** across 5+ services
- Worked with QA on debugging and unit testing to trace and fix **REST API** integration failures, reducing recurring defects by **25%**

### ⚡ Vardhan Insys — Software Engineer Intern (Jun 2023 – Jul 2023)
- Automated email response workflows and redesigned the company website in **PHP** with SEO optimization on **AWS**, reducing manual response time by **30%** and increasing organic search traffic by **20%**

---

## Open Source Contributions

Test coverage for **GRASS GIS**, the open-source geospatial engine used by researchers worldwide.

- **[lib/datetime: Add pytest unit tests for datetime_scan and datetime_format](https://github.com/OSGeo/grass/pull/7871)** (107 ctypes unit tests for the C library behind `G_format_timestamp` and `G_scan_timestamp`)
- **[g.gisenv: Add pytest test suite](https://github.com/OSGeo/grass/pull/7803)** (11 tests covering variable read/write, case-insensitive lookup, and protected-variable behavior)
- **[r.timestamp: Add pytest test suite](https://github.com/OSGeo/grass/pull/7802)** (8 tests covering timestamp set/read/overwrite/remove and error handling)

---

## Featured Projects

### 🧑‍💻 [Harper — Go Terminal Coding Agent](https://github.com/jalpatel11/Harper) &nbsp; ![Status](https://img.shields.io/badge/Status-In_Development-orange?style=flat-square)
> Go · Ollama · vLLM · Anthropic

A provider-agnostic terminal coding agent written in Go. It supports five LLM providers, including Anthropic, and runs an orchestrator/worker loop that hands subtasks to workers in parallel through concurrent goroutine fan-out.

- **Permission system** with three modes (allow, ask, deny) and structured JSONL session logging, so the engineer stays in charge of what the agent is allowed to run

---

### 🔧 [Self-Healing SRE Agent](https://github.com/jalpatel11/Self-Healing-SRE-Agent) &nbsp; ![Status](https://img.shields.io/badge/Status-In_Development-orange?style=flat-square) ![Version](https://img.shields.io/badge/Version-1.0-blue?style=flat-square)
> LangGraph · Groq Llama 3.3-70B · FastAPI · Streamlit · PyGithub · LangSmith · Python AST

Multi-agent AI system for automated incident response. Built from scratch on nights and weekends because the problem was worth solving. V1 is complete and the core self-healing loop works end to end.

- **Multi-agent orchestration** via LangGraph, with Investigator and Mechanic agents that hand off explicitly and track their communication
- **Self-correcting loop** that retries up to 3 times with validation feedback, the way an engineer would debug
- **95% success rate** after self-correction, resolving incidents in **30-60 seconds** at **$0.02-0.06 per fix**
- **Full observability** through LangSmith decision tracing and GitHub Actions logs
- **Safe by default** with iteration limits, AST-based code validation, and human approval required before merge

---

### 🧠 [Calmindra — AI Mental Health Companion](https://github.com/jalpatel11/calmindra) &nbsp; [![Live Demo](https://img.shields.io/badge/Live_Demo-calmindra.jalpatel.dev-2563EB?style=flat-square)](https://calmindra.jalpatel.dev/)
> Next.js · FastAPI · Neo4j · Mistral-7B · LoRA · Ollama · Docker · GCP

Full-stack mental health chatbot with a Next.js frontend and a FastAPI backend exposing JWT-authenticated REST APIs, backed by a Neo4j graph database. Containerized with Docker and deployed on GCP.

- Fine-tuned **Mistral-7B-v0.3** with **LoRA** and supervised fine-tuning, served through Ollama
- Benchmarked against a curated evaluation set to reach **91% accuracy** at **sub-500ms latency**

---

### ✈️ [IFRPM — Intelligent Fleet Risk and Predictive Maintenance](https://github.com/jalpatel11/IFRPM)
> Python · FastAPI · TensorFlow (Keras) · Scikit-Learn · Machine Learning

FastAPI backend with a dynamic multi-model ensemble for Remaining Useful Life (RUL) prediction. It ingests and aggregates predictions across Keras (`.h5`) and Scikit-Learn (`.pkl`) models for fleet health monitoring, and a React dashboard shows real-time risk scores and predictive alerts.

---

### 🗺️ [Phoenix LandCover Segmentation](https://github.com/jalpatel11/phoenix-landcover-segmentation)
> Python · TensorFlow/Keras · U-Net · Google Earth Engine · Sentinel-2

Deep learning pipeline for pixel-wise land use classification over Central Phoenix from Sentinel-2 satellite imagery. A custom U-Net covers 9 land cover classes, with patch-based training and full-image reconstruction.

- **95.95%** pixel accuracy, **95.50%** weighted F1, **92.79%** mean IoU

---

### 📚 [Book Recommender](https://github.com/jalpatel11/book-recommender-system)
> Python · Data Analysis · Cosine Similarity · Recommender Systems

User-based collaborative filtering recommender trained on the Book Crossing dataset. It computes cosine similarity across user rating vectors to find similar readers and suggest books.

---

### 🔗 [SafeBite Blockchain — Food Traceability](https://github.com/jalpatel11/SafeBite-Blockchain-Food-Traceability)
> JavaScript · Blockchain · Smart Contracts · Web3

Tracks food products from farm to table using smart contracts and a decentralized ledger, so each step in the supply chain is recorded and verifiable.

---

### 📊 [GUI Scheduling Algorithms](https://github.com/jalpatel11/GUI_Scheduling_algorithms) &nbsp; [![Live Demo](https://img.shields.io/badge/Live_Demo-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://jalpatel11-gui-scheduling-algorithms-app-yfyzch.streamlit.app)
> Python · Streamlit · Algorithms · Operating Systems

Streamlit app that simulates CPU scheduling algorithms (FCFS, SJF, Round Robin). You enter custom process parameters and compare turnaround and waiting time through Gantt charts.

---

### 🖥️ [Student Performance Review System](https://github.com/jalpatel11/Student_performance_review_system)
> Python · Tkinter · SQLite · Pandas

Desktop app with a Tkinter GUI for tracking and analyzing student metrics, using SQLite for storage and Pandas for correlation analysis and predictive modeling.

---

## Education

- 🎓 **M.S. Data Science, Analytics and Engineering**, Arizona State University (Aug 2024 – May 2026)
- 🎓 **B.Tech, Computer Science and Engineering**, Nirma University (Oct 2020 – Aug 2024)

---

## Technical Skills

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### ML & AI
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangGraph](https://img.shields.io/badge/LangGraph-000000?style=for-the-badge&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-000000?style=for-the-badge&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logoColor=white)

### AI-Assisted Development
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=for-the-badge&logo=githubcopilot&logoColor=white)

### Frontend & Backend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![HTMX](https://img.shields.io/badge/HTMX-3366CC?style=for-the-badge&logo=htmx&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)

### Data & Infrastructure
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

---

## Certifications & Achievements

![LeetCode](https://img.shields.io/badge/LeetCode-Knight_(top_25%25)-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)
![HackerRank](https://img.shields.io/badge/HackerRank-Advanced_SQL-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-Cloud_Foundation-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Coursera](https://img.shields.io/badge/Stanford-ML_Specialization-0056D2?style=for-the-badge&logo=coursera&logoColor=white)
![GRASS GIS](https://img.shields.io/badge/Open_Source-GRASS_GIS-2E7D32?style=for-the-badge)

---

<p align="center">
  <i>Feel free to reach out on LinkedIn or by email.</i>
</p>
