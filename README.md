<h1 align="center">Aous Abdulhamid</h1>
<h3 align="center">AI Engineer · Agentic AI · Multi-Agent Systems · RAG · LLM Evaluation · Azure · LLMOps</h3>
<p align="center">📍 Passau & Cologne, Germany · Open to relocation</p>

<p align="center">
  <a href="https://aous-abdulhamid.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/aous-abdulhamid/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:aous.abdulhamid@gmail.com"><img src="https://img.shields.io/badge/Email-aous.abdulhamid%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://stackoverflow.com/users/25087596/aous-abdulhamid"><img src="https://img.shields.io/badge/Stack%20Overflow-F58025?style=flat&logo=stackoverflow&logoColor=white" alt="Stack Overflow"></a>
</p>

I build production Generative AI systems: agentic RAG, multi-agent architectures with LangChain/LangGraph, and the evaluation pipelines that keep them honest. Currently an AI Engineer at **Webasto**, shipping enterprise GenAI tools for R&D engineering, while finishing an M.Sc. in Artificial Intelligence Engineering at the **University of Passau** (thesis on multi-turn LLM evaluation). Before that, I spent over a year as a Data Scientist at **MTN Group** building churn models for 2M subscribers.

- 🔭 Running an agentic RAG system on Azure that 25+ mechanical engineers use to verify battery designs in minutes instead of hours.
- 🌱 Thesis work on multi-turn LLM evaluation.
- 💬 Ask me about RAG pipelines, agentic workflows, LLM evaluation, or Azure LLMOps.
- 📫 Reach me at [aous.abdulhamid@gmail.com](mailto:aous.abdulhamid@gmail.com) or [LinkedIn](https://www.linkedin.com/in/aous-abdulhamid/).

## Experience

**AI Engineer (Working Student), [Webasto](https://www.webasto-group.com/)** · Munich, Germany · Jan 2025 – present
- Designed and shipped an agentic RAG system on Azure that cut battery-design verification for automotive OEMs from 2 hours to under 5 minutes, now used by 25+ mechanical engineers across Webasto sites.
- Unified 25,000+ multimodal files (Word, Excel, PNG) from ERP, PLM/CAD, and requirements systems into one Azure AI Search index via custom connectors (DAX, C#, OSLC) and automated chunking and embedding.
- Raised answer relevance from 0.62 to 0.85 and faithfulness to 0.85 with hybrid search (BM25 + vector) and semantic reranking, tracked by an automated RAGAS evaluation pipeline on 100 questions.
- Deployed to production on Azure Container Apps (Bicep, Docker, GitLab CI/CD) with page-level source citations, p95 latency under 3 s, and evaluation gates that block regressions before release.
- Reduced a 45-minute Abaqus scripting task to a single prompt with a LangGraph ReAct agent exposing 15 simulation tools, adopted by the engineering team via Streamlit.

**Data Scientist, MTN Group** · Telecommunications · Oct 2022 – Jan 2024
- Built churn-prediction models (XGBoost, scikit-learn) on 12 months of usage data for 2M subscribers, reaching 85% accuracy and 0.87 ROC-AUC, with SHAP to explain the main churn drivers.
- Increased retention by 30% in targeted segments, validated by A/B tests on a 25,000-subscriber control group.
- Deployed the models as a Flask REST API with weekly batch scoring for Sales and Marketing self-service.
- Owned the ML lifecycle from SQL feature engineering (30+ features) to MLflow tracking and reporting.

## Education

- **M.Sc. Artificial Intelligence Engineering**, University of Passau, Germany · Apr 2024 – Jan 2027 (expected) · Thesis: Multi-Turn LLM Evaluation
- **B.Sc. Informatics Engineering, Specialisation in Artificial Intelligence**, Arab International University · Oct 2017 – Sep 2023 · Five-year engineering program; ranked 3rd of 114 in the National Bachelor's Exam; thesis: [Soul Composer](https://github.com/aous1998/Soul-Composer), graded 95/100

## Certifications

Building with Claude API (Anthropic, 2026) · Retrieval Augmented Generation (DeepLearning.AI, 2026) · Data Analysis with Python (IBM, 2025) · Neural Networks and Deep Learning (DeepLearning.AI, 2023) · Machine Learning with Python (IBM, 2022)

## Featured Projects

| Project | Stack | Description |
|---|---|---|
| **Production-Grade RAG Knowledge Assistant** | Python, LangChain, ChromaDB, Cohere Rerank, LangSmith | Scaled a RAG pipeline from 10 to 10,000+ documents, fixing five production failure modes with hybrid search (BM25 + dense), cross-encoder reranking, parent-document retrieval, tracing, and caching. |
| [TripMate AI](https://github.com/aous1998/TripMate-AI) | Python, LangGraph, MCP, FastAPI, PostgreSQL, Docker | Multi-agent travel planner: a supervisor routes to six specialised agents over a typed state graph, with MCP tools, guardrails, and human-in-the-loop approval. |
| [Slotfill](https://github.com/aous1998/slotfill) | Python, Hugging Face Transformers, PEFT, vLLM | LoRA fine-tuned adapter for strict-schema invoice extraction, benchmarked against a frontier LLM. |
| **Doorman** | Python, LangGraph, Guard Model | Prompt-injection guardrails for a resume-screening agent, hardened with tool allowlists and a 60-attack red-team suite. |
| [mlab (ml-library)](https://github.com/aous1998/ml-library) | Python, NumPy, pytest | M.Sc. lab at the University of Passau: 12+ ML models built in pure NumPy (random forest, SVM, CNN, and more) behind a scikit-learn-style API, applied to NLP and vision tasks. |
| [browser-reliability](https://github.com/aous1998/browser-reliability) | Python, local LLM | Master's seminar study of LLM browser-agent reliability for web QA: precision, recall, and run-to-run consistency of a local qwen3:8b agent vs. a rule-based checker on seeded defects. |
| [Soul Composer](https://github.com/aous1998/Soul-Composer) | Python, Deep Learning | AI song-composition app covering the full ML lifecycle, from data pipeline and model training to full-stack delivery. B.Sc. thesis, graded 95/100. |
| [Fluencia](https://github.com/aous1998/Fluencia) | AI, Speech | AI-powered speech-training app for stuttering therapy. |

## Skills

**LLM & Generative AI:** RAG · Agentic AI · Multi-Agent Systems · Agent Orchestration · Tool Calling (MCP) · Prompt Engineering · Embeddings · Semantic & Hybrid Search · Reranking · Guardrails · LoRA Fine-Tuning

**Frameworks:** LangChain · LangGraph · LlamaIndex · Semantic Kernel · AutoGen · Claude API

**LLM Evaluation & LLMOps:** RAGAS · Azure AI Evaluation SDK · LangSmith (tracing, observability) · MLflow

**Machine Learning & Deep Learning:** PyTorch · TensorFlow · Hugging Face · scikit-learn · NumPy · pandas

**Cloud & DevOps:** Azure (AI Foundry, Azure OpenAI, AI Search, Container Apps) · Docker · Kubernetes · Bicep · GitLab CI/CD · GitHub Actions

**Programming & Backend:** Python · C# · TypeScript · JavaScript · FastAPI · Flask · React · Streamlit

**Databases:** SQL · PostgreSQL · MySQL · SQL Server · Cosmos DB · pgvector · ChromaDB · Pinecone

**Languages:** English (C1, fluent) · Arabic (native) · German (A2, B1 expected Jan 2027)

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white">
</p>
