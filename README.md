# Shaheer Aslam

Software engineer working across TypeScript/React front ends and Python backends, with a focus on AI systems that hold up outside a notebook. MSc Applied Artificial Intelligence at London South Bank University. Based in London.

[Portfolio](https://www.shaheeraslam.net) · [shaheer.aslam@icloud.com](mailto:shaheer.aslam@icloud.com)

---

## Featured work

**[agent-failure-detection](https://github.com/shaheerr1/agent-failure-detection)** · Runtime failure detection for LLM agents (MSc dissertation)

A DeBERTa classifier that identifies unsafe execution, loops and hallucination from partial agent traces, reaching 0.820 macro F1 (bootstrap 95% CI 0.734 to 0.891). I measured the runtime false alarm rate before claiming it was deployable: 13.2% of healthy trace prefixes raised an alarm, at 0.942 per-prefix alarm precision. I then ran four adversarial ablations against my own model, masking tool names, stripping formatting markers and removing final answers. Both shortcut hypotheses were refuted. Hallucination detection loses 0.155 F1 once the final answer is removed, which sets the ceiling on catching that failure mode at runtime.

`Python` `PyTorch` `DeBERTa` `FastAPI`

**[ChurnRadar](https://github.com/shaheerr1/YOUR-REPO)** · Deployed churn prediction service

XGBoost model at 84.5% accuracy across 7,043 telecom records, with SHAP explanations surfacing the drivers behind every risk score. Served in under 3 seconds through a FastAPI backend and a React/TypeScript dashboard.

`Python` `XGBoost` `SHAP` `FastAPI` `React` `TypeScript`

**[LeadFlow](https://github.com/shaheerr1/YOUR-REPO)** · Multi-agent outreach pipeline

End-to-end lead discovery, tailored email generation and follow-up scheduling on GPT-4o and LangChain. Produces 5 to 10 qualified leads per run with personalised emails in 1 to 2 seconds, dispatched through the Gmail API behind a human review queue.

`Python` `LangChain` `FastAPI`

**[Quant Mania](https://github.com/shaheerr1/YOUR-REPO)** · Real-time crypto data pipeline

Sub-second streaming pipeline running ML anomaly and volatility detection, with Prometheus, Grafana and Loki for monitoring.

`Kafka` `Flink` `FastAPI` `Prometheus` `Grafana`

---

## Stack

**Languages** TypeScript, Python, SQL, Swift, Dart

**Frontend** React, Next.js, Tailwind, SwiftUI, Flutter

**Backend and data** FastAPI, Node, PostgreSQL, Redis, MongoDB, Firebase, Kafka, Flink, Airflow

**ML and AI** PyTorch, XGBoost, scikit-learn, LangChain, LangGraph, RAG, Hugging Face

**Infra** Docker, GitHub Actions, AWS, GCP, Nginx, Prometheus, Grafana, Linux
