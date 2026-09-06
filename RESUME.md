# Robert Fenech Adami

**Data Scientist / Data Engineer**  
Malta · robertfa02@gmail.com · +356 99623332  
[LinkedIn](https://linkedin.com/in/robert-fenech-adami-308758222)

---

## Profile

AI Engineer / Data Engineer with a production ML background, focused on building practical GenAI and data systems using LangChain, LangGraph, RAG, structured outputs, tool calling, human-in-the-loop workflows, and evaluation.

Professionally experienced in production data and ML workflows across ETL, Airflow orchestration, batch inference, Kafka integrations, monitoring, CI/CD, AWS, SageMaker, MLflow, Docker, Kubernetes, Grafana, and Prometheus. MSc Data Science graduate with experience working on large-scale datasets and collaborating with Data Science, Compliance, CRM, Marketing, Payments, and operational stakeholders.

---

## Technical Skills

**AI Engineering:** LangChain, LangGraph, RAG, structured outputs, tool calling, human-in-the-loop workflows, LangSmith, ChromaDB, Pydantic

**Data Engineering:** Python, SQL, ETL/ELT, data pipelines, data quality, feature engineering, batch processing, dbt, Spark

**MLOps & Cloud:** AWS, SageMaker, MLflow, Airflow, MWAA, AWS Batch, AWS Fargate, Docker, Kubernetes, ECR, CI/CD, GitHub Actions

**Streaming & Monitoring:** Kafka, Grafana, Prometheus, event-driven pipelines, production observability

**BI & Analytics:** Qlik Sense, Power BI, Tableau, Talend, Azure Data Factory, Databricks

---

## Selected AI Projects

### [Customer Support Resolution Copilot](https://github.com/robbyfa/customer-support-agent)

Business workflow copilot that helps support agents classify customer cases, retrieve policy guidance, generate internal recommendations, draft customer-safe responses, validate outputs, and route sensitive cases through human approval.

**Stack:** LangGraph · LangChain · RAG · ChromaDB · Pydantic · Streamlit · LangSmith

- Built an 11-node LangGraph workflow with conditional routing, groundedness checks, retry logic, and manual review fallback.
- Separated customer-facing drafts from internal operational recommendations: **what to say** vs **what to do**.
- Added dual validation for customer response groundedness and internal recommendation safety.
- Implemented PII masking, audit trails, approval gates, and human-review routing for sensitive cases.
- Created a 25-case evaluation suite with quality dimensions, separation boundary checks, and 159 automated tests.
- Deployed a live demo using synthetic customer data and mock policy documents.

---

### [Streaming Sports Intelligence Agent](https://github.com/robbyfa/sports-intelligence-agent)

Event-driven RAG agent for sports analysis using streaming-style ingestion, LangGraph routing, source-grounded answers, claim verification, and evaluation.

**Stack:** LangGraph · LangChain · RAG · Kafka-style streaming · ChromaDB · SQLite · Streamlit

- Built Kafka-compatible event ingestion with SQLite and ChromaDB dual storage for structured and semantic queries.
- Implemented LangGraph routing across tool execution, event search, analyst brief generation, and fallback search.
- Added structured outputs, source-grounded analysis, confidence scoring, and cited evidence.
- Built an analyst brief workflow with claim extraction and verification against source event data.
- Created a 20-question evaluation suite covering retrieval relevance, groundedness, citation quality, route selection, and event freshness.

---

## Work Experience

### Data Engineer - Tipico  
**Malta · September 2025 – Present**

- Own data pipelines that move ML models from experimentation into recurring batch and service-based workflows, including ETL, Airflow orchestration, Kafka integration, monitoring, and delivery to downstream systems.
- Led the data integration for a responsible gaming self-exclusion workflow, retrieving customer risk scores from an internal model and publishing them via Kafka to a downstream consumer service.
- Owned evaluation workflows for bonus recommender changes, including ETL support, backtesting, regression checks, feature-importance analysis, fine-tuning, and A/B test setup.
- Maintained and enhanced the bonus recommender by expanding the eligible customer base while validating model performance before rollout.
- Collaborated on a deposit recommender delivered through batch and service patterns, contributing to €200k+ annual savings in PSP fees.
- Co-developed responsible gaming ETL and dashboards that reduced manual self-exclusion risk-case review effort by 10+ hours per week.
- Supported additional ML and data products including customer survey analysis, customer risk scoring/profile services, and early VIP detection.
- Worked closely with Data Science, Compliance, CRM, Marketing, and Payments stakeholders on model requirements, PII, retention policies, experiment results, and business impact.

---

### Data Engineer - iMovo Limited, A Deloitte Business  
**Malta · 2024 – September 2025**

- Delivered data engineering, business intelligence, and reporting solutions across retail, industrial, airport authority, consultancy, and sports media client environments.
- Built dashboards and KPI reporting in Qlik Sense, Power BI, and Tableau, partnering with stakeholders to define metrics, data requirements, and operational insights.
- Developed ETL logic, SQL scripts, and data pipelines using Talend, Azure Data Factory, Python, and SQL.
- Administered Tableau Cloud reporting environments.
- Built Python/deep-learning models to analyse social media impact on web traffic and support content recommendation insights.

---

## Education

### MSc Information Studies - Data Science  
**University of Amsterdam · 2023 – 2024**

### BSc Information Technology - Software Development  
**University of Malta · October 2020 – July 2023**

---

## Certifications

- LangChain - Agentic AI Engineering with LangChain & LangGraph
- Talend Data Integration Certified Developer
- Qlik Sense Business Analyst
- Databricks Certified Data Engineer Associate Cert Prep
- Big Data Analytics with Hadoop and Apache Spark
- IBM Machine Learning Certificates
- Data Scientist: Machine Learning Career Path
