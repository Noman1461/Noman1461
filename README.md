# Hi 👋, I'm Noman

**Data Engineer Contributor @ Omdena** | Building reliable data pipelines and automation systems

---

## 🚀 About Me

Electrical engineer transitioning into **Data Engineering and AI/ML Engineering**, with hands-on experience building ETL pipelines, AI-powered applications, RESTful APIs, geospatial workflows, and automation systems. I’m currently working as a Data Engineer Contributor at Omdena, contributing to data ingestion pipelines and AI-driven agricultural projects, while continuing to build expertise across data engineering, machine learning, and Generative AI.

- 🔭 **Currently working on:** Production-grade data and AI workflows using Python, PostgreSQL, Apache Airflow, and cloud technologies
- 🌱 **Learning:** **Microsoft Fabric (DP-700)** | Docker | Azure Cloud Fundamentals | Modern Data & AI Stack
- 👯 **Looking for:** Opportunities in **Data Engineering, AI/ML Engineering, Data Science, and AI Engineering**

**[View My Resume](https://github.com/Noman1461/Noman1461/blob/main/Noman_Ajmal_Resume.pdf)** • **[Connect on LinkedIn](https://www.linkedin.com/in/nomanajmal/)**

---

## 🛠️ Featured Project: CafeFlow ETL Pipeline

> A **production-style ETL pipeline** that converts messy cafe transaction data into a structured analytics-ready dataset using validation, error tracking, and automated quality reporting.

### ⚙️ Pipeline Overview

**1. Raw CSV Data** -> **2. Extract Layer** (Read & ingest raw records) -> **3. Validation & Transformation** (Data cleaning + quality checks)
-> **4. Load Layer** (PostgreSQL warehouse) -> **5. Monitoring & Reporting** (Error logs + quality reports)

---

### 🔑 Key Engineering Features

| Layer | Implementation |
|------|------|
| **Extract** | Efficient ingestion of 7,000+ raw transaction records from CSV |
| **Validation** | 6+ data quality checks including ID validation, price/quantity verification, and date parsing |
| **Transform** | Business logic applied for spending category classification and high-value order detection |
| **Load** | Idempotent loading into PostgreSQL using `ON CONFLICT` upsert strategy |
| **Observability** | Automated error logging and JSON-based quality reports for debugging and monitoring |
| **Engineering Practices** | Modular pipeline architecture (`extract.py`, `transform.py`, `load.py`) with clean separation of concerns |
| **Version Control** | Full Git workflow with reproducible pipeline runs |
| **Next Step** | Docker containerization for reproducible deployment |

---

### 📊 Data Quality Results

| Metric | Value |
|------|------|
| Total Records Processed | 7,139 |
| Valid Records Loaded | 84% data pass rate |
| Data Quality Checks | 6+ |
| Output | Rejected row logging + JSON quality reports |

---

🔗 **[View Full Project Repository](https://github.com/Noman1461/DE-projects/tree/main/etlproject)**

---

## 📌 Pipeline Projects Roadmap

| Project | Status | Description |
|---------|--------|-------------|
| **CafeFlow ETL** | ✅ Complete | Python-based ETL with validation & monitoring |
| **Consumer Complaint Analytics** | ✅ Complete | Airflow-orchestrated ETL pipeline with Docker and automated reporting |
| **Omdena Geospatial & Weather Pipelines** | ✅ Complete  | Data ingestion and processing workflows for agricultural AI applications |
| **RAG & AI Agent System** | ✅ Complete | LLM-powered RAG system with FAISS, HuggingFace embeddings, and ReAct agents |

---

## 💼 Experience Snapshot

### Omdena — Data Engineer Contributor
- Designed and developed scalable ingestion pipelines for weather, geospatial, and Earth observation datasets.
- Helped modernize the Sentinel-2 pipeline by migrating processing logic to Google Earth Engine.
- Built Python-based ETL workflows for collection, validation, feature engineering, and cloud delivery to Amazon S3.
- Collaborated with data scientists and ML engineers to improve data contracts, quality, and downstream workflow readiness.

### Zyne Ventures — Data Scientist
- Designed and built a Retrieval-Augmented Generation (RAG) system using FAISS and HuggingFace embeddings to ground LLM responses in a local knowledge base.
- Implemented a **ReAct AI agent** using Python and LangChain with autonomous tool selection and context retrieval, powered by Llama-3.1-70B.
- Developed persistent agent memory to maintain state across runs and improve workflow reliability.
- Built AI automation and REST API workflows to integrate intelligent solutions into business processes.

---

## 💻 Technical Skills

- **Languages:** Python, SQL
- **AI/ML:** Machine Learning, Deep Learning, NLP, Generative AI, LLMs, RAG, AI Agents, Feature Engineering
- **AI Frameworks:** PyTorch, Scikit-Learn, LangChain, HuggingFace
- **Data Engineering:** ETL/ELT, Data Quality, Airflow, Data Processing, Geospatial Workflows
- **Databases:** PostgreSQL, MySQL
- **API & Tools:** FastAPI, Flask, REST APIs, Docker, Git, n8n
- **Cloud / Learning:** AWS S3, Microsoft Fabric, Azure

---

## 📂 Other Projects

**Consumer Complaint Analytics: Automated ETL Pipeline**
- End-to-end **Apache Airflow ETL pipeline** extracting 22,714+ records from a public regulatory API and loading them into MySQL
- Implemented data transformation, Airflow XCom, FileSensor, automated Google Sheets publishing, and email notifications
- Containerized the workflow using **Docker** for reproducible pipeline execution

**Corporate Credit Risk Data Warehouse**
- Designed an enterprise-style **PostgreSQL Data Warehouse** using a Kimball dimensional model with 8 dimensions and 5 fact tables
- Built metadata-driven **ETL and Data Quality frameworks** with validation rules, execution logging, and failed-rule reporting
- Developed analytical SQL queries and a **Power BI dashboard** for credit exposure, delinquency, recovery, and Early Warning Indicator analysis

**IntelliNews: Automated News Classification**
- Flask-based web app using TF-IDF and logistic regression
- End-to-end ML pipeline with REST API deployment on Render
- 🔗 [View Repository](https://github.com/Noman1461/nlp-projects)

---

## 📫 Let's Connect

<p align="left">
  <a href="https://www.linkedin.com/in/nomanajmal/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:noman.pnec1461@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
  <a href="https://leetcode.com/nomi1461/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
  </a>
</p>

---

<p align="center">
  <i>Open to entry-level AI/ML, Data Science, Data Engineer opportunities.</i>
</p>
