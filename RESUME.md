# Robert Fenech Adami

**AI Engineer / Data Engineer | Production ML & GenAI**

Malta · Open to relocation across Australia  
robertfa02@gmail.com · +356 99623332  
[LinkedIn](https://linkedin.com/in/robert-fenech-adami-308758222) · [GitHub](https://github.com/robbyfa)

**Planning relocation to Australia · Intending to apply for a Working Holiday visa (subclass 417) · Open to employer sponsorship**

---

## Professional Summary

AI Engineer / Data Engineer with an MSc in Data Science and hands-on experience building and operating production ML, data, and GenAI systems. Experienced across Python, SQL, AWS, Airflow, Kafka, SageMaker, MLflow, Docker, Kubernetes, CI/CD, monitoring, and large-scale data pipelines, with professional work spanning model evaluation, batch and service-based inference, experimentation, streaming integrations, and production observability.

Alongside my production ML background, I build applied GenAI systems using LangGraph, LangChain, RAG, MCP, vector stores, structured outputs, tool calling, human-in-the-loop workflows, and LLM evaluation.

---

## Technical Skills

**GenAI & Agentic AI:** LangGraph, LangChain, RAG, MCP, ChromaDB, LangSmith, Pydantic, structured outputs, tool calling, human-in-the-loop workflows, LLM evaluation, groundedness checks

**Data & ML Engineering:** Python, SQL, ETL/ELT, data pipelines, data quality, feature engineering, batch inference, model evaluation, backtesting, A/B testing, Spark, dbt

**Cloud, MLOps & Orchestration:** AWS, Amazon SageMaker, MLflow, Airflow, MWAA, AWS Batch, AWS Fargate, Docker, Kubernetes, ECR, CI/CD, GitHub Actions

**Streaming & Observability:** Kafka, Grafana, Prometheus, event-driven pipelines, production monitoring

**BI & Data Platforms:** Talend, Azure Data Factory, Qlik Sense, Power BI, Tableau, Databricks

---

## Professional Experience

### Data Engineer - Tipico
**Malta · September 2025 - Present**

- Own data pipelines that move ML models from experimentation into recurring batch and service-based production workflows, covering ETL, Airflow orchestration, Kafka integration, monitoring, and downstream delivery.
- Work with large-scale datasets ranging from millions to billions of rows across data preparation, feature engineering, model training support, backtesting, and batch inference workflows.
- Led the data integration for a responsible gaming self-exclusion workflow, retrieving customer risk scores from an internal model and publishing them through Kafka to a downstream consumer service.
- Owned evaluation workflows for bonus recommender changes, including ETL support, backtesting, regression checks, feature-importance analysis, fine-tuning support, and A/B test setup.
- Maintained and enhanced the bonus recommender by expanding the eligible customer base while validating model behaviour and performance before rollout.
- Collaborated on a deposit recommender delivered through batch and service-based patterns, contributing to **€200k+ in annual PSP fee savings**.
- Co-developed responsible gaming ETL and reporting workflows that reduced manual self-exclusion risk-case review effort by **10+ hours per week**.
- Supported additional ML and data products including customer survey analysis, customer risk scoring/profile services, and early VIP detection.
- Operate production ML workloads using Airflow/MWAA, AWS Batch/Fargate, SageMaker, MLflow, Docker, Kubernetes, Kafka, Grafana, and Prometheus.
- Work closely with Data Science, Compliance, CRM, Marketing, Payments, and operational stakeholders on model requirements, PII handling, retention policies, experiment results, and business impact.

### Data Engineer - iMovo Limited, A Deloitte Business
**Malta · 2024 - September 2025**

- Delivered data engineering, analytics, and business intelligence solutions across retail, industrial, airport authority, consultancy, and sports media client environments.
- Developed ETL logic, SQL scripts, and data pipelines using Talend, Azure Data Factory, Python, and SQL.
- Built dashboards and KPI reporting solutions in Qlik Sense, Power BI, and Tableau, working directly with stakeholders to define metrics, data requirements, and operational insights.
- Administered Tableau Cloud reporting environments and supported production BI workflows.
- Built Python and deep-learning models to analyse social media impact on web traffic and support content recommendation insights.

---

## Selected AI Projects

### [Customer Support Resolution Copilot](https://github.com/robbyfa/customer-support-agent)
**LangGraph · LangChain · RAG · ChromaDB · MCP · Pydantic · Streamlit · LangSmith**

Built and deployed a business workflow copilot that classifies support cases, retrieves policy context, loads structured customer data, generates internal recommendations and customer-safe drafts, validates outputs, and routes sensitive cases through human approval.

- Built an **11-node LangGraph workflow** with conditional routing, retry logic, groundedness checks, approval gates, and manual-review fallback.
- Implemented a layered context system combining **RAG over policy documents, ChromaDB vector search, and an MCP server** exposing customer, ticket, transaction, bonus, and policy context.
- Built MCP tooling supporting standalone **stdio and HTTP transports**, resource access, and LangChain tool conversion through `langchain-mcp-adapters`.
- Separated customer-facing responses from internal operational recommendations: **what to say vs what to do**.
- Added dual validation for customer-response groundedness and internal-recommendation safety.
- Implemented PII masking, audit trails, approval gates, and human-review routing for sensitive cases.
- Created a **25-case evaluation suite** with multiple quality dimensions and separation boundary checks, backed by **159 automated tests**.
- Deployed a public demo using synthetic customer data and mock policy documents.

### [Streaming Sports Intelligence Agent](https://github.com/robbyfa/sports-intelligence-agent)
**LangGraph · LangChain · RAG · Kafka-style streaming · ChromaDB · SQLite · Streamlit**

Built an event-driven sports intelligence agent combining streaming-style event ingestion, structured and semantic retrieval, LangGraph routing, and evidence-grounded analysis.

- Built Kafka-compatible event ingestion with SQLite and ChromaDB dual storage for structured and semantic querying.
- Implemented LangGraph routing across tool execution, event search, analyst-brief generation, and fallback search.
- Added structured outputs, evidence-grounded answers, source citations, and confidence scoring.
- Built an analyst-brief workflow with factual claim extraction and verification against source event data.
- Created a **20-question evaluation suite** covering retrieval relevance, groundedness, citation quality, route selection, and event freshness.

---

## Education

### MSc Information Studies - Data Science
**University of Amsterdam · 2023 - 2024**

### BSc Information Technology - Software Development
**University of Malta · October 2020 - July 2023**

---

## Certifications & Professional Development

- Databricks Certified Data Engineer Associate
- LangChain - Agentic AI Engineering with LangChain & LangGraph
- Talend Data Integration Certified Developer
- Qlik Sense Business Analyst
- Big Data Analytics with Hadoop and Apache Spark
- IBM Machine Learning coursework
- Data Scientist: Machine Learning Career Path

---

## Additional Information

**English:** IELTS - 8.0+ in Listening, Reading, Writing, and Speaking  
**Relocation:** Open to opportunities across Australia, including Sydney, Melbourne, Brisbane, Perth, Adelaide, Canberra, and other locations  
**Visa:** Planning to apply for a subclass 417 Working Holiday visa and open to longer-term employer sponsorship
