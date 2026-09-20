# Shamanth N

**AI Engineer in Bengaluru.** I build production LLM systems: retrieval pipelines, multi-agent
workflows and document understanding, plus the async backends that run them.

Currently at **VAIA Investment Advisory**, working on due diligence and ESG reporting platforms.

## What I've built

- **Due diligence reporting platform.** Turns uploaded company documents and live market data into
  analyst-ready reports in under five minutes. Async FastAPI and Celery, Dockerised on AWS, with an
  iterative retrieve, reason and verify research loop.
- **ESG and decarbonisation reporting tool.** OCR over billing documents, Scope 1, 2 and 3
  emissions calculation, and section drafting scored by Gemini and Claude against hybrid
  retrieval, traced in LangSmith. Figures trace back to source documents through a Neo4j
  knowledge graph.
- **[curated10.com](https://curated10.com).** An automated newsletter I built and run: LLM grading
  and ranking of about 50 articles per category, scheduled on AWS Lambda and EventBridge, delivered
  through Resend. 300+ subscribers.
- **ESG reasoning model.** Fine-tuned Qwen3.5-9B with continued pre-training, SFT, DPO and GRPO
  (LoRA via Unsloth). Accuracy on ESGenius went from 65.45% to 89.7%.

## Open source

| Project | What it is |
|---|---|
| [**AutoPitch**](https://github.com/shamanth811/autopitch) | Scores VC pitch decks section by section with LangGraph, benchmarks the raise against funding rounds extracted from SEC filings (Pinecone), and predicts investor objections. Gemini 2.5 Pro, Llama 3.1, FastAPI, LangSmith. |

## Research

- **VAIA Finance Readiness Benchmark**: an evaluation framework for enterprise finance and
  sustainability LLMs. Co-author; built the domain dataset. Preprint under review.
- **The Intersection of Art and AI: Innovations in Creative Collaboration**: first author, IEEE
  ICICAT 2024. [DOI](https://doi.org/10.1109/icicat62666.2024.10923276)

## Stack

**LLM systems:** LangGraph, LangChain, RAG, tool calling, structured outputs, LLM-as-judge evals  
**Backend:** Python, FastAPI, Celery, asyncio, Pydantic, SQL, TypeScript  
**Retrieval & data:** Pinecone, FAISS, hybrid search (BM25 + dense), Neo4j, PostgreSQL, Redis  
**Cloud & MLOps:** AWS (Lambda, EventBridge, S3, ECS), Docker, CI/CD, LangSmith, Weights & Biases, MLflow  
**Training:** SFT, DPO, GRPO, LoRA, Unsloth, PyTorch, Hugging Face, vLLM

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/shamanth-n)

B.E. in AI & ML, RNS Institute of Technology.
