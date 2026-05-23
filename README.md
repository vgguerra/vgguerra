# Victor Guerra

AI Software Engineer Intern at [Alvarez & Marsal](https://www.alvarezandmarsal.com/). I build agentic AI systems in Python and hybrid retrieval pipelines over unstructured corpora. Background in Telecommunications Engineering at IFSC and computer vision research at IPBeja in Portugal.

I prefer publishing the eval over publishing the demo.

## What I'm shipping

| Project | Stack | What it shows |
|---|---|---|
| **[OpenEnergyRag](https://github.com/vgguerra/OpenEnergyRag)** | FastAPI, Qdrant, e5-large + BM25, RRF, Groq | Citation-first RAG over Brazilian electricity-sector regulations (PRODIST/ANEEL, ONS). Published benchmark on a 25-question hand-curated eval set, `recall@10 = 1.000`. Free-tier deploy on Qdrant Cloud + Hugging Face Spaces + Vercel, CI/CD gated on release. |
| **[Travel-Agent](https://github.com/vgguerra/Travel-Agent)** | Python, LangGraph, tool use, LLM provider abstraction | Multi-agent travel planner with planner, searcher and writer roles coordinating through a shared state graph. |
| **[Barber](https://github.com/vgguerra/Barber)** | Java 21, Spring Boot 4, Next.js 16, Testcontainers, Flyway | Production-grade SaaS with JWT auth, RBAC (USER/ADMIN), opening-hours overlap validation, integration tests on a real Postgres via Testcontainers, GitHub Actions CI. |
| **[ChunkerIA](https://github.com/vgguerra/ChunkerIA)** | Python | Comparator for chunking strategies in RAG pipelines, with focus on Portuguese regulatory text. |

## How I work

- Read papers and model cards before picking libraries. The e5 query/passage prefix story in OpenEnergyRag came from the model card, not the docs.
- Publish the numbers. If I claim something is accurate or fast, the eval is in the repo and reproducible from a clean clone.
- Prefer direct code over abstraction frameworks when the framework hides the data flow. RAG done right is around 800 lines of Python; LangChain often costs more than it saves.

## Background

- 🎓 **Telecommunications Engineering** at IFSC (Instituto Federal de Santa Catarina)
- 🇵🇹 Exchange research at **IPBeja, Portugal**: computer vision automation of the Fullerton Battery, a functional fitness test for older adults, using MediaPipe, OpenCV and PyKinect
- 🔬 Prior research on **multi-agent generative AI for the Brazilian electrical sector** (now materialized in [OpenEnergyRag](https://github.com/vgguerra/OpenEnergyRag))
- 💼 Currently building intelligent solutions at Alvarez & Marsal
- 📘 English: Advanced

## Stack I use day to day

[![](https://skillicons.dev/icons?i=python,java,spring,fastapi,nextjs,typescript,tailwind,postgres,docker,linux,git&theme=dark)](https://skillicons.dev)

Beyond what icons exist for: Qdrant for vector storage, fastembed for e5 + BM25, LangGraph for agent orchestration, uv for Python dependency management, Hugging Face Spaces and Vercel for free-tier production deploys.

## Reach out

- [LinkedIn](https://www.linkedin.com/in/victor-guerra-9597101b6/)
- [Instagram](https://instagram.com/vl.guerra)
