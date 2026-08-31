# Robert Fenech Adami | AI Engineering & Data Systems

**AI Engineer / Data Engineer** with a production ML background, focused on building applied GenAI systems using LangChain, LangGraph, RAG, vector stores, MCP, structured outputs, tool calling, human-in-the-loop workflows, and evaluation.

I build practical AI systems that connect language models to data, tools, workflows, and business processes.

## CV

For more detail on my professional experience, technical background, and selected AI projects, see my [CV](./RESUME.md).

---

## Selected AI Projects

### 🎧 [Customer Support Resolution Copilot](https://github.com/robbyfa/customer-support-agent)

Business workflow copilot that helps support agents classify customer cases, retrieve policy guidance, load structured customer context, generate internal recommendations, draft customer-safe responses, validate outputs, and route sensitive cases through human approval.

**Stack:** LangGraph · LangChain · RAG · ChromaDB · MCP · Pydantic · Streamlit · LangSmith

- Built an 11-node LangGraph workflow with conditional routing, groundedness checks, retry logic, approval gates, and manual review fallback
- Implemented a layered context system using RAG over policy documents, ChromaDB vector search, and an MCP server for structured customer, ticket, transaction, bonus, and policy context
- Built an MCP server with support-domain tools, policy resources, stdio/HTTP support, and LangChain tool conversion via `langchain-mcp-adapters`
- Separated customer-facing drafts from internal operational recommendations: **what to say** vs **what to do**
- Added dual validation for customer response groundedness and internal recommendation safety
- Implemented PII masking, audit trails, approval gates, and human-review routing for sensitive cases
- Created a 25-case evaluation suite with 5 quality dimensions, 5 separation boundary checks, and 159 automated tests

> [Live demo](https://customer-support-agent-nxj2ca4bxnx95dpaxbzcqr.streamlit.app/) · Uses synthetic customer data and mock policy documents only.

---

### ⚽ [Streaming Sports Intelligence Agent](https://github.com/robbyfa/sports-intelligence-agent)

Event-driven RAG agent for sports analysis, using streaming-style ingestion, LangGraph routing, source-grounded answers, claim verification, and evaluation.

**Stack:** LangGraph · LangChain · RAG · Kafka-style streaming · ChromaDB · SQLite · Streamlit

- Built Kafka-compatible event ingestion with SQLite and ChromaDB dual storage for structured and semantic queries
- Implemented LangGraph routing across tool execution, event search, analyst brief generation, and fallback search
- Added structured outputs, source-grounded analysis, confidence scoring, and cited evidence
- Built an analyst brief workflow with claim extraction and verification against source event data
- Created a 20-question evaluation suite covering retrieval relevance, groundedness, citation quality, route selection, and event freshness

---

## What I Build

| Area | Details |
|---|---|
| **Agentic workflows** | LangGraph multi-node pipelines with conditional routing, retries, approval gates, manual review fallback, and human-in-the-loop logic |
| **Context systems** | Layered context architectures using RAG, vector stores, MCP tools/resources, structured customer context, and policy retrieval |
| **RAG systems** | ChromaDB retrieval, metadata filtering, section-aware chunking, source attribution, and groundedness verification |
| **MCP integrations** | MCP servers exposing domain tools/resources over stdio or HTTP, with LangChain tool conversion and graph integration |
| **Structured outputs** | Pydantic models for classification, recommendations, customer drafts, risk flags, and analyst reports |
| **AI safety patterns** | PII masking, approval gates, audit trails, dual groundedness checks, manual review fallback, and prevention of unsupported action claims |
| **Evaluation** | Custom evaluation suites, weighted scoring, boundary checks, LangSmith tracing, and regression-style testing |
| **Data engineering** | Event-driven pipelines, streaming-style ingestion, SQL/vector dual storage, ETL, and production ML workflow experience |

---

## Current Focus

- Building applied GenAI systems with LangChain, LangGraph, RAG, MCP, vector stores, and LangSmith
- Designing safe AI workflows with structured outputs, tool calling, approval gates, audit trails, and evaluation
- Applying my production data and ML background to AI Engineer / Applied AI roles

---

## Connect

- 💼 [LinkedIn](https://linkedin.com/in/robert-fenech-adami-308758222)
- 📧 robertfa02@gmail.com
