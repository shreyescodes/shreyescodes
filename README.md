# Shreyas T C

**Software Engineer, Backend and AI** | Python, FastAPI, LangGraph | Regulated fintech | LiteLLM contributor

Bengaluru, Karnataka, India. Open to Software Engineer, Backend Engineer and AI Engineer roles, in Bengaluru or remote.

[Portfolio](https://shreyescodes.netlify.app/) · [LinkedIn](https://www.linkedin.com/in/shreyes19) · [LeetCode](https://leetcode.com/u/shreyescodes/) · [X](https://x.com/shreyescodes) · [Medium](https://medium.com/@shreyescodes)

[![XERJ Corpus Hub contributor](https://hub.xerj.org/contributors/shreyescodes/badge.svg)](https://hub.xerj.org/contributors/shreyescodes)

## What I do

I build backend services and the AI parts around them: APIs, data pipelines, RAG and agents. I work across the stack, from React frontends to FastAPI and Node.js services, with PostgreSQL and Redis underneath, shipped with Docker on AWS. I like systems that are correct, tested and easy to run.

I have worked on wealthtech and BFSI products, so audit trails and data integrity are normal requirements for me.

## Projects

- **[Data-Analyst-AI-Agent](https://github.com/shreyescodes/Data-Analyst-AI-Agent)**: ask a CSV, API or database questions in plain English and get SQL, charts and a profile report. Queries run on a read-only connection, the model gets up to 3 attempts at a failing query, and a CI job runs the AI mode on a local model, so no API key is needed. Python, Streamlit, mypy strict.
- **[Project-Aura](https://github.com/shreyescodes/Project-Aura)**: infrastructure as code for an OpenStack private cloud lab. Terraform builds 8 KVM nodes on 4 networks, Ansible sets up Ceph and OpenStack, a FastAPI service handles tenant onboarding, and the Prometheus alert rules are unit-tested and linked to runbooks.
- **[RAG-Data-Platform](https://github.com/shreyescodes/RAG-Data-Platform)**: ask questions about 5,000+ rows of synthetic financial data in plain English. Retrieval, enrichment and analysis agents answer them, PII is redacted before any LLM call, and each query is logged so answers can be audited. React, FastAPI, PostgreSQL, FAISS.
- **[Invoice-Intelligence-Platform](https://github.com/shreyescodes/Invoice-Intelligence-Platform)**: invoice processing on Azure. OCR and LLM extraction, purchase order checks against a mock SAP service, anomaly scoring with a scikit-learn one-class SVM, and a human approval step. React, FastAPI, Azure Durable Functions.
- **[vol-regime-backtester](https://github.com/shreyescodes/vol-regime-backtester)**: backtesting engine that sizes positions by volatility regime. Execution is fully vectorized, a stress suite simulates flash crashes and cost surges, and it runs on synthetic data or your own CSV files. Streamlit dashboard, Docker, unit tests.

## Open source

- [BerriAI/litellm #25559](https://github.com/BerriAI/litellm/pull/25559), merged on 13 April 2026. Hardened CORS, fixed exception masking in `create_views` and removed an infinite-loop risk in spend log cleanup.

## Work

- **Founding Engineer**, Atrean (wealthtech startup), Oct 2025 to Jun 2026. Owned the backend for a portfolio intelligence platform for family offices.
- **Technical Trainer (freelance)**, ACTE Technologies, Apr 2026 to Aug 2026. Taught data science and data analytics batches.
- **Associate Software Engineer**, Ahana Systems and Solutions, Jul 2024 to Jul 2025. Built full-stack microservices on AWS with Node.js, FastAPI and React, and worked on performance under live traffic.
- **Python Developer Intern**, GTPL (BFSI), Feb 2024 to May 2024. Backend services and integrations in a BFSI setup.

## Stack

- **Languages:** Python, TypeScript, JavaScript (Node.js), SQL
- **Backend:** FastAPI, Express, Celery, REST APIs, microservices
- **Data:** PostgreSQL, Redis, FAISS
- **AI:** LangGraph, LangChain, RAG, multi-agent systems, LLM evals, LiteLLM
- **Cloud and ops:** AWS (EC2, RDS, S3), Docker, GitHub Actions, Terraform, Ansible, Prometheus, Grafana
- **Frontend:** React
- **Testing:** pytest

## Education and recognition

- B.E. Electronics and Communication Engineering, RNS Institute of Technology (VTU), 2023.
- Best Paper Award, IETE National Conference, for an embedded AI healthcare system: human activity recognition with KNN on a Jetson Nano.
- KSCST research grant (Karnataka State Council for Science and Technology), co-sponsored by IISc, for applied AI and IoT research.
- Published paper: Human Activity Recognition using KNN-Machine Learning Algorithms approach (IJARESM).

## Learning now

Java, Spring Boot and Go. I am building a payments ledger with Kafka and AWS to learn them properly, and I will push it here stage by stage.
