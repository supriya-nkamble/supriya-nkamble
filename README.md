# Hi, I'm Supriya 👋

I take AI systems from an ambiguous problem to production — owning the
**architecture**, the **evaluation strategy**, and the **path to ship**. Retrieval
systems are my depth; making them trustworthy is the point.

A decade building software — Java systems at BNY Mellon, a Master of Computing at
ANU, ML at CSIRO, and the last ~5 years on AI at Typefi.

🔗 [Portfolio](https://portfolio-supriya-nkamble.vercel.app) ·
[LinkedIn](https://www.linkedin.com/in/-supriya-kamble/) ·
supriyakamble76@gmail.com

---

### How I work

- **Evaluate before you optimize** — held-out test set, run once, never used for tuning.
- **Provenance is enforced, not documented** — the index manifest guards the model; retrieval refuses to run on a mismatch.
- **Degrade, don't guess** — retrieval-only fallback when there's no LLM key.
- **Every fix ships with the test that would have caught it** — a ~60-finding audit, each mapped to its regression test.

---

### Featured

| Project | What it is | Signal |
| --- | --- | --- |
| **[Legal-QA](https://github.com/supriya-nkamble/Legal-QA)** | Hybrid RAG over Australian law — BM25 + BGE + RRF + cross-encoder rerank, FastAPI + React, Terraform → Cloud Run via Workload Identity Federation | **Hit@1 0.60 → 0.82** with reranking · 33 tests · `HARDENING.md` maps every finding to a test |
| **[Personal-Tutor](https://github.com/supriya-nkamble/Personal-Tutor)** | Multimodal RAG tutor — PDF / video / OCR ingestion behind one interface, cited answers, quiz generation | PRD with Non-Goals + a "this stack is wrong" section · architecture decision table |
| **[Credit-Card Fraud Detection](https://github.com/supriya-nkamble/credit-card-fraud-detection)** | Imbalanced classification on 284k transactions | 6 models · SMOTE on the train fold only · ROC-AUC / F1 / κ |

Also: [Emotion Detective](https://github.com/supriya-nkamble/sentiment-analysis)
(DistilBERT fine-tune, 6 emotions) ·
[Book Recommender](https://github.com/supriya-nkamble/recommendation-system)
([live demo](https://recommend-book.streamlit.app)) ·
[Text-Summarizer](https://github.com/supriya-nkamble/Text-Summarizer)
(config-driven MLOps pipeline).

---

### Stack

**Architecture & leadership**
![AI system architecture](https://img.shields.io/badge/AI%20system%20architecture-4f46e5?style=flat-square)
![Evaluation strategy](https://img.shields.io/badge/evaluation%20strategy-4f46e5?style=flat-square)
![Responsible AI](https://img.shields.io/badge/Responsible%20AI%20%2F%20guardrails-4f46e5?style=flat-square)
![Design docs & ADRs](https://img.shields.io/badge/design%20docs%20%26%20ADRs-4f46e5?style=flat-square)

**GenAI / RAG**
![LangChain](https://img.shields.io/badge/LangChain-1c3c3c?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-1c3c3c?style=flat-square)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-000?style=flat-square)
![hybrid retrieval + rerank](https://img.shields.io/badge/hybrid%20retrieval%20%2B%20rerank-4f46e5?style=flat-square)
![Ragas / Ranx](https://img.shields.io/badge/Ragas%20%2F%20Ranx-4f46e5?style=flat-square)

**ML / DL**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Transformers](https://img.shields.io/badge/🤗%20Transformers-FFD21E?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**MLOps / Serving**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)

---

<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=supriya-nkamble&show_icons=true&hide_border=true&hide=stars&card_width=420" alt="stats" />
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=supriya-nkamble&layout=compact&hide_border=true&langs_count=8" alt="top languages" />
</p>
