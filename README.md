<p align="center">
  <img src="https://github.com/jalpatel11/jalpatel11/blob/c74e1520abcd61861410ccb90833d925ff245c0c/hii.gif" />
</p>

<h1 align="center">Hi, I'm Jal Patel 👋</h1>

<p align="center">
  <b>MS Graduate @ Arizona State University</b> &nbsp;|&nbsp; <b>Software & ML Engineer</b> &nbsp;|&nbsp; <b>Full-Stack Builder</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jal1102"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/jalpatel11"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="mailto:jal85524@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://jalpatel.dev"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white" /></a>
</p>

---

## About Me

I recently graduated with my MS in Data Science, Analytics and Engineering from Arizona State University, with hands-on experience building production-grade software systems, ML pipelines, and full-stack applications.

My work sits at the intersection of **software engineering**, **applied ML**, and **data engineering**. I care about building things that actually work in production, not just in notebooks.

- 🏢 Currently **Data Scientist @ Integrated Travel** (Remote) — researching a community-driven tourism and entertainment discovery platform
- 🔧 Built a self-healing SRE Agent from scratch that resolves CI/CD failures autonomously with a 95% success rate
- 🌍 Open-source contributor to **GRASS GIS** (OSGeo) — merged test-suite contributions to `r.timestamp` and `g.gisenv`
- 🛠️ Shipped real products across backend, frontend, and ML across multiple internships and projects
- 📍 Based in Tempe, AZ — open to full-time opportunities starting May 2026

---

## Experience Highlights

### 🧳 Integrated Travel — Data Scientist (Jun 2026 – Present)
- Researching a community-driven tourism and entertainment discovery platform for Central Alberta, focused on local events, attractions, transportation access, and grassroots economic development
- Supporting early-stage research on data sources, geospatial analysis, and AI-assisted workflows to improve tourism visibility for smaller communities

### 🤖 Sentari AI — SDE Intern (Aug 2025 – Jan 2026)
- Architected REST microservices in Python integrating AI pipelines, processing 30+ simultaneous data streams and reducing inference latency by 21%
- Launched a full-stack **React + FastAPI** monitoring dashboard enabling real-time anomaly detection, cutting incident response time by **35%**
- Engineered responsive frontend features in TypeScript and React, contributing to **200% month-over-month platform growth**
- Built an offline processing pipeline that safely queued data and delivered it reliably once connectivity was restored
- Secured a full-stack login page with **OAuth2** authentication in **TypeScript & React**, improving token verification speed by **27%**

### 🏗️ Plexusnet Services — SWE Intern (Jan 2024 – May 2024)
- Built scalable backend systems in Python, Django, and PostgreSQL, accelerating system response times by **18%**
- Streamlined CI/CD pipelines using Docker and GitHub Actions, cutting manual release errors by **30%**
- Traced and resolved complex REST API and microservices integration issues using pytest, reducing systemic defects by **25%**
- Formulated API specifications and architecture diagrams supporting scalability of 5+ core platform features

### ⚡ Vardhan Insys — SWE Intern (Jun 2023 – Jul 2023)
- Automated email response workflows using PHP scripting, reducing manual response time by 30% and improving
customer query turnaround.
- Redesigned and deployed the company website on AWS with SEO optimization strategies using PHP, increasing
organic search traffic by 20% and improving site load performance.

---

## Open Source Contributions

Contributing test coverage and tooling to **GRASS GIS**, the open-source geospatial engine used by researchers worldwide.

- **[r.timestamp: Add pytest test suite](https://github.com/OSGeo/grass/pull/7802)** — 8 tests covering timestamp set/read/overwrite/remove and error handling
- **[g.gisenv: Add pytest test suite](https://github.com/OSGeo/grass/pull/7803)** — 11 tests covering variable read/write, case-insensitive lookup, and protected-variable behavior

---

## Featured Projects

### 🔧 [Self-Healing SRE Agent](https://github.com/jalpatel11/Self-Healing-SRE-Agent) &nbsp; ![Status](https://img.shields.io/badge/Status-In_Development-orange?style=flat-square) ![Version](https://img.shields.io/badge/Version-1.0-blue?style=flat-square)
> LangGraph · Groq Llama 3.3-70B · FastAPI · Streamlit · PyGithub · LangSmith · Python AST

Multi-agent AI system for automated incident response. Built from scratch on nights and weekends because the problem was worth solving. V1 is complete and the core self-healing loop works end to end.

- **Multi-agent orchestration** via LangGraph — Investigator and Mechanic agents with explicit handoff and communication tracking
- **Self-correcting loop** — up to 3 attempts with validation feedback, mimicking how human engineers debug
- **95% success rate** after self-correction, resolving incidents in **30-60 seconds** at **$0.02-0.06 per fix**
- **Full observability** via LangSmith decision tracing and GitHub Actions logs
- **Safe by default** — iteration limits, AST-based code validation, human approval required before merge

---

### 🧠 [Calmindra — AI Mental Health Companion](https://github.com/jalpatel11/calmindra) &nbsp; [![Live Demo](https://img.shields.io/badge/Live_Demo-calmindra.jalpatel.dev-2563EB?style=flat-square)](https://calmindra.jalpatel.dev/)
> Next.js · FastAPI · Neo4j · Ollama · LoRA · Docker · GCP

Full-stack mental health chatbot with a Next.js frontend and a FastAPI backend exposing JWT-authenticated REST APIs, backed by a Neo4j graph database. Containerized with Docker and deployed on GCP for scalable, always-on inference.

- LoRA fine-tuned **Ollama** model reaching **91% accuracy** at **sub-500ms latency**
- JWT-authenticated REST APIs backed by a **Neo4j** graph database
- Containerized and deployed on **GCP** cloud infrastructure

---

### ✈️ [IFRPM — Intelligent Fleet Risk and Predictive Maintenance](https://github.com/jalpatel11/IFRPM)
> Python · FastAPI · TensorFlow (Keras) · Scikit-Learn · Machine Learning

FastAPI backend with a dynamic multi-model ensemble for Remaining Useful Life (RUL) prediction. Automatically ingests and aggregates predictions across Keras (`.h5`) and Scikit-Learn (`.pkl`) models for robust fleet health monitoring, presented through a React dashboard with real-time risk scoring and predictive alerts.

---

### 🗺️ [Phoenix LandCover Segmentation](https://github.com/jalpatel11/phoenix-landcover-segmentation)
> Python · TensorFlow/Keras · U-Net · Google Earth Engine · Sentinel-2

Deep learning pipeline for pixel-wise land use classification over Central Phoenix using Sentinel-2 satellite imagery. Custom U-Net across 9 land cover classes, with patch-based training and full-image reconstruction.

- **95.95%** pixel accuracy, **95.50%** weighted F1, **92.79%** mean IoU

---

### 📚 [Book Recommender](https://github.com/jalpatel11/book-recommender-system)
> Python · Data Analysis · Cosine Similarity · Recommender Systems

User-based collaborative filtering recommender system trained on the Book Crossing dataset. Computes cosine similarity across user rating vectors to identify similar readers and generate personalized book title suggestions.

---

### 🔗 [SafeBite Blockchain — Food Traceability](https://github.com/jalpatel11/SafeBite-Blockchain-Food-Traceability)
> JavaScript · Blockchain · Smart Contracts · Web3

Blockchain-based food traceability system tracking the journey of food products from farm to table using smart contracts and decentralized ledger technology, ensuring data integrity and transparency end to end.

---

### 📊 [GUI Scheduling Algorithms](https://github.com/jalpatel11/GUI_Scheduling_algorithms) &nbsp; [![Live Demo](https://img.shields.io/badge/Live_Demo-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://jalpatel11-gui-scheduling-algorithms-app-yfyzch.streamlit.app)
> Python · Streamlit · Algorithms · Operating Systems

Interactive Streamlit app simulating and visualizing CPU scheduling algorithms (FCFS, SJF, Round Robin), letting users input custom process parameters and compare turnaround/waiting time through dynamic Gantt charts.

---

### 🖥️ [Student Performance Review System](https://github.com/jalpatel11/Student_performance_review_system)
> Python · Tkinter · SQLite · Pandas

Desktop analytics application with a Tkinter GUI for institutions to monitor and analyze student metrics, backed by SQLite for data storage and Pandas for correlation analysis and predictive modeling.

---

## Education

- 🎓 **M.S. Data Science, Analytics and Engineering** — Arizona State University (Aug 2024 – May 2026)
- 🎓 **B.Tech, Computer Science and Engineering** — Nirma University (Oct 2020 – Aug 2024)

---

## Technical Skills

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
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

### Frontend & Backend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)

### Data & Infrastructure
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

---

## Certifications

![HackerRank](https://img.shields.io/badge/HackerRank-Advanced_SQL-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-Cloud_Foundation-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Coursera](https://img.shields.io/badge/Stanford-ML_Specialization-0056D2?style=for-the-badge&logo=coursera&logoColor=white)

---

<p align="center">
  <i>Open to full-time Software Engineer, ML Engineer, and Data Engineer roles starting May 2026</i>
</p>
