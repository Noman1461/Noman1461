# Hi 👋, I'm Noman

**Data Engineer Contributor @ Omdena** | Building reliable data pipelines and automation systems

---

## 🚀 About Me

Electrical engineer transitioning into **Data Engineering** with hands-on experience building ETL pipelines, RESTful APIs, geospatial workflows, and automation systems. I’m currently working as a Data Engineer Contributor at Omdena, where I contribute to ingestion pipelines for weather, geospatial, and Earth observation data and help improve data quality and delivery workflows.

- 🔭 **Currently working on:** Production-grade ETL pipelines with Python, PostgreSQL, and cloud delivery
- 🌱 **Learning:** Docker | Azure AZ-900 (cloud fundamentals) | Modern data stack
- 👯 **Looking for:** Entry-level Data Engineer roles to build scalable data systems
- ⚡ **My motto:** *"Slowly but surely"* — I believe in consistent learning and building

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
| **Omdena Geospatial ETL Work** | ✅ Active | Ingestion and transformation pipelines for weather and Earth observation data |
| **API to Database Pipeline** | ⏳ In progress | FastAPI service with automated data ingestion |
| **Azure Mini Data Pipeline** | 📅 Planned | Cloud-based ETL using Azure services |

---

## 💼 Experience Snapshot

### Omdena — Data Engineer Contributor
- Designed and developed scalable ingestion pipelines for weather, geospatial, and Earth observation datasets.
- Helped modernize the Sentinel-2 pipeline by migrating processing logic to Google Earth Engine.
- Built Python-based ETL workflows for collection, validation, feature engineering, and cloud delivery to Amazon S3.
- Collaborated with data scientists and ML engineers to improve data contracts, quality, and downstream workflow readiness.

### Zyne Ventures — AI Automation Engineer
- Designed and deployed Flask RESTful APIs for job posting workflows.
- Built automation pipelines for payment confirmation processing.
- Reduced manual effort by improving data processing and workflow automation.

---

## 💻 Technical Skills

- **Languages:** Python, SQL
- **Data Engineering:** ETL/ELT, data quality checks, pipeline orchestration, geospatial workflows
- **Frameworks:** Flask, PyTorch (basics)
- **Databases:** PostgreSQL, MySQL
- **Tools:** Docker, Git, n8n, Power BI
- **Cloud / Learning:** Azure AZ-900, AWS S3, cloud data engineering

---

## 📂 Other Projects

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
  <i>Open to entry-level Data Engineer opportunities — let's build reliable data systems together!</i>
</p>
