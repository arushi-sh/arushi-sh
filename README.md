<h1 align="center">Hi, I'm Arushi 👋</h1>
<h3 align="center">Backend Engineer · Go · Distributed Systems · AI-powered products</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/arushi-sharma-140b46229"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/arushi-sh"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Based%20in-Delhi%20NCR-orange?style=for-the-badge" />
</p>

---

### 🧑‍💻 About me

- Backend engineer with **2+ years** of experience building production APIs in **Go**.
- At **Busy Infotech (an IndiaMART company)** I helped build **BlackPearl CRM** from scratch — a multi-tenant sales & revenue-ops platform with **RBAC**, **50+ REST APIs across 8 modules**, bulk-import pipelines, and an **NSQ-based notification pipeline**.
- I like wiring **LLMs and ML models into real backends** — not just calling an API, but owning the service, the data model, and the prompts around it.
- Currently: building a file-storage service with semantic search, and going deep on **system design** and **DSA**.

---

### 🛠 Tech stack

**Languages**
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend & frameworks**
![Gin](https://img.shields.io/badge/Gin-008ECF?style=flat-square&logo=go&logoColor=white)
![GORM](https://img.shields.io/badge/GORM-00ADD8?style=flat-square&logo=go&logoColor=white)
![Fiber](https://img.shields.io/badge/Fiber-00ACD7?style=flat-square&logo=go&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Data & messaging**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![NSQ](https://img.shields.io/badge/NSQ-2C3E50?style=flat-square)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)

**Cloud, DevOps & observability**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

**AI / ML**
![OpenAI API](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20%2B%20MCP-D97757?style=flat-square&logo=anthropic&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

---

### 🤖 How I use AI

| Where | How |
|---|---|
| **Inside products** | LLM calls live behind Go services — the OpenAI Go SDK in JDScope, Claude in Moodify — with prompts kept as versioned code, not scattered strings. |
| **ML as a service** | scikit-learn models served through **FastAPI** microservices and called from a **Go** backend (PCOS Risk Platform). |
| **Day-to-day engineering** | Claude for design reviews, debugging and refactors; **MCP** integrations (e.g. Apify) to automate research and data-collection workflows. |

---

### 🚀 Featured projects

#### 🩺 [PCOS Risk Assessment Platform](https://github.com/arushi-sh/PCOS-App)
A full-stack app that helps doctors manage patients and run PCOS risk assessments.
- **Go (Gin) + GORM** backend with **JWT auth**, middleware, and modular `controller → process → service` layers for login, logout and patient domains
- Separate **Python FastAPI ML service** serving a **scikit-learn** model, called by the Go backend
- **Next.js / TypeScript** frontend; whole stack containerised with **Docker Compose**

`Go` `Gin` `GORM` `JWT` `FastAPI` `scikit-learn` `Next.js` `Docker`

#### 🔍 [JDScope — AI Job Description Analyzer](https://github.com/arushi-sh/JD-Analyzer)
AI-powered Chrome extension that analyzes LinkedIn job descriptions.
- **Go (Gin)** backend using the official **OpenAI Go SDK**, with prompts isolated in their own service layer
- Results persisted in **PostgreSQL** via **GORM**
- Chrome extension (content script + popup) talks to the backend

`Go` `Gin` `OpenAI API` `PostgreSQL` `GORM` `Chrome Extension`

#### 📺 [YouTube ELT Pipeline](https://github.com/arushi-sh/YoutubeELT)
End-to-end data pipeline that extracts channel analytics from the **YouTube Data API v3**.
- **Apache Airflow** DAGs for extract → load → transform into a **PostgreSQL** data warehouse
- Data-quality checks with **Soda**; unit + integration tests with **pytest**
- **Docker Compose** environment and a **GitHub Actions CI/CD** workflow

`Python` `Airflow` `PostgreSQL` `Soda` `Docker` `GitHub Actions`

#### 🗂️ [FileStorage](https://github.com/arushi-sh/FileStorage) — *in progress*
A backend file-storage system to upload, store, and search files — built in **Go (Gin)**, with **AWS S3** for storage and **PostgreSQL + pgvector** for semantic search.

#### 🎵 [Moodify](https://github.com/arushi-sh/Moodify) — *in progress*
Chrome extension that suggests songs based on your mood — **Go** backend with an auth module, using the **Claude API** to generate mood-based playlists.

<details>
<summary><b>More projects</b></summary>

| Project | What it is | Stack |
|---|---|---|
| [PCOS-Dashboard](https://github.com/arushi-sh/PCOS-Dashboard) | Clinician screening dashboard with BMI calc, PCOS risk prediction and patient history; modular load/transform/model pipeline | FastAPI, Streamlit, PostgreSQL, scikit-learn |
| [Crud-CRM](https://github.com/arushi-sh/Crud-CRM) | Lead-management CRUD API with a Postman collection | Go, Fiber, GORM |
| [GoogleDoc](https://github.com/arushi-sh/GoogleDoc) | Low-level-design simulation of a document editor | C++ |
| [spring-boot-todo](https://github.com/arushi-sh/spring-boot-todo) | Todo app to practise Java backend development | Java, Spring Boot, Thymeleaf |
| [Medical-Chatbot-NSDC](https://github.com/arushi-sh/Medical-Chatbot-NSDC) | Medical Q&A chatbot notebook | Python, Jupyter |
| [insurance-claim-analysis](https://github.com/arushi-sh/insurance-claim-analysis) | SQL schema, inserts, analysis and query optimisation | SQL |
| [DSA-Preparation](https://github.com/arushi-sh/DSA-Preparation) | Ongoing DSA practice | C++ |

</details>

---

### 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=arushi-sh&show_icons=true&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=arushi-sh&layout=compact&hide_border=true" />
</p>

---

<p align="center"><i>Open to backend engineering roles — Go, APIs, and AI-backed systems. Let's connect!</i></p>
