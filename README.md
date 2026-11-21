<div align="center">

# Piyush Priyam

### Software Engineer · Machine Learning Engineer · Backend & AI Systems

**Building scalable backend services, REST APIs, microservices, and production ML/RAG platforms.**

Halifax, Nova Scotia, Canada · 7+ Years Experience · M.Sc. Computing & Data Analytics (4.08 GPA)

[About](#about) · [Featured Projects](#featured-projects) · [Experience](#experience) · [Tech Stack](#tech-stack) · [GitHub Analytics](#github-analytics) · [Connect](#connect)

</div>

---

## About

I'm a **Software Engineer & Machine Learning Engineer** with **7+ years of production experience** designing backend services, REST APIs, microservices, ETL pipelines, and applied AI/ML systems across government, enterprise, and consulting environments.

- **Currently:** Application Developer (Software Engineer) at the **Government of Nova Scotia**, leading full-lifecycle engineering and modernization for provincial digital services (**LATIS** & **RYSTA**).
- **Backend & Systems Impact:** Engineered backend services, APIs, and SQL indexing optimizations that cut heavy query execution time by **~38%**, lowered key transaction latency by **~24%**, and reduced average API response times by **~14%**.
- **Production ML & MLOps:** Built web-scale ML serving APIs and MLOps workflows at **TietoEVRY** (cutting model release turnaround from days to hours) and calibrated MMM, CLTV, and recommendation engines at **Lifesight**.
- **Open Source & AI:** Building containerized RAG services, developer utilities, and reusable Python/Django packages.
- **Ask me about:** Python, Django, FastAPI, REST APIs, Microservices, SQL Optimization, Hybrid RAG / LLMs, and MLOps.

---

## Featured Projects

### [DocuMind — Open-Source Hybrid RAG Platform](https://github.com/piyushpriyam-crey/Documind)
`FastAPI` · `ChromaDB` · `Sentence Transformers` · `Ollama / vLLM` · `SQLite` · `Docker` · `pytest` · `GitHub Actions`

- Production-oriented Retrieval-Augmented Generation (RAG) chatbot and REST API grounding answers strictly in uploaded documents with inline source citations (filename, chunk index, similarity score).
- Supports **15+ document formats** with magic-byte MIME sniffing, headless LibreOffice conversion, and optional Tesseract OCR.
- Implements **hybrid retrieval** (dense embeddings + cached BM25), optional cross-encoder reranking, query rewriting, parent–child chunking, contextual summaries, and HyDE.
- Includes token-by-token **SSE streaming**, SQLite-persisted conversation memory and background ingestion jobs, API key auth, per-IP rate limiting, per-document access tokens, liveness/readiness probes (`/api/health`, `/api/ready`), non-root Docker Compose packaging, and automated `pytest` CI.

### [Simple Form Builder — Multi-Form Django Studio](https://github.com/piyushpriyam-crey/SimpleFormBuilder)
`Python` · `Django` · `JavaScript` · `SortableJS` · `Bootstrap 5`

- Full-stack Django application with a drag-and-drop visual form builder across **12 configurable field types** and per-field validation/options.
- Renders live Bootstrap 5 previews and stores form submissions as structured JSON payloads viewable directly in Django Admin.
- Features one-click exporters for portable **JSON schemas**, ready-to-use **Django `forms.py`** classes, and standalone **Bootstrap 5 HTML** pages.

### Open-Source Packages & Libraries

| Project | Stack | Highlights |
| :--- | :--- | :--- |
| **Django Multi-Sessions** | `Python` · `Django` · `sessionStorage` · `htmx` | Reusable Django package enabling isolated per-tab browser sessions via custom middleware, with tab-scoped messages, history handling, redirects, and `htmx` support. |
| **EmailValidator** | `Python` · `DNS` · `dnspython` | RFC-compliant email and domain validator with live `MX`/`A`/`AAAA`/`TXT`/`NS` DNS lookups, SPF & DMARC retrieval, configurable timeouts, and automated tests. |
| **HTML PDF Maker** | `Python` · `WeasyPrint` | Modular Python library converting HTML files, strings, fragments, and URLs into styled PDFs with CSS customization, metadata, editable PDF forms, and test coverage. |

---

## Experience

| Role & Organization | Timeline | Selected Engineering Impact |
| :--- | :--- | :--- |
| **Application Developer (Software Engineer)** — Government of Nova Scotia | Nov 2023 – Present | Leading full-lifecycle backend, REST API, and microservice development for **LATIS**, **RYSTA**, and NS Services Modernization; cut SQL query times by **~38%**, transaction latency by **~24%**, and API response times by **~14%**. |
| **AI / ML Engineer Intern (Co-op)** — Lifesight | Apr 2023 – Nov 2023 | Tuned product recommendations (**~4.5%** conversion lift), calibrated MMM & CLTV models (**~6.5%** modeled ROAS lift, **~3.5%** cohort churn reduction), and automated ML prep workflows (**~6 hrs/wk** saved). |
| **Python Developer & Data Scientist** — Freelance / Self-Employed | May 2021 – Jun 2022 | Built IoT predictive maintenance models (**~16%** lower unplanned downtime), redesigned batch ETL pipelines (**~35%** faster), and automated recurring reporting (**~6 hrs → ~2.5 hrs**). |
| **Software Engineer** — TietoEVRY | Jun 2018 – Apr 2021 | Engineered production Python/R backend services, APIs, and MLOps pipelines serving ML models at web scale, cutting release turnaround from **days to hours**. |

**Education & Credentials:** M.Sc. in Computing and Data Analytics (Co-op), Saint Mary's University (**4.08 GPA**) · B.E. in Electronics & Telecommunications, Savitribai Phule Pune University · *Machine Learning* (Stanford University) · *Advanced Coding in AI* (University of Helsinki)

---

## Tech Stack

**Languages & query**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

**Backend, web & cloud**

![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat-square&logo=sass&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

**Data & machine learning**

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=plotly&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)

**Databases & infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Microsoft SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?style=flat-square&logo=gunicorn&logoColor=white)

**Dev tools & delivery**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

## GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.shion.dev/api?username=piyushpriyam-crey&theme=dark&hide_border=true&include_all_commits=true&count_private=false" alt="GitHub stats" />
<img height="165" src="https://streak-stats.demolab.com/?user=piyushpriyam-crey&theme=dark&hide_border=true" alt="GitHub contribution streak" />

<img src="https://github-readme-stats.shion.dev/api/top-langs/?username=piyushpriyam-crey&theme=dark&hide_border=true&include_all_commits=true&count_private=false&layout=compact" alt="Most used programming languages" />

</div>

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/priyam-piyush)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@piyush.priyam)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/sarcastic.crey)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:piyushpriyam.piyush@gmail.com)

</div>

<div align="center">

Thanks for stopping by — let's build something useful.

![Profile views](https://komarev.com/ghpvc/?username=piyushpriyam-crey&style=flat-square&color=blue)

</div>