# Soham Jindal

### Software engineer building reliable backend, distributed, and applied-ML systems

Computer Engineering at Purdue University · AI/ML minor · Expected May 2028

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-111827?style=flat-square&logo=vercel&logoColor=white)](https://brohum10.github.io/soham-portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sohamj2025)
[![Email](https://img.shields.io/badge/Email-Soham-334155?style=flat-square&logo=gmail&logoColor=white)](mailto:soham.jindal16@gmail.com)

I like engineering work where correctness, observability, and performance all matter: guardrailed AI systems, concurrent crawlers, consensus protocols, retrieval infrastructure, trace analysis, and privacy-conscious product software. My repositories emphasize runnable examples, explicit trade-offs, automated tests, and results that another engineer can reproduce.

## Start here

| Project | What it explores | Engineering evidence |
|:--|:--|:--|
| **[LLM Incident Response Copilot](https://github.com/brohum10/llm-incident-response-copilot)** | Guardrailed RAG service that retrieves runbooks, gathers evidence through allowlisted read-only tools, validates cited plans, and approval-gates mutating actions | Deterministic evaluation: **1.00 Recall@4**, **1.00 citation coverage**, and **1.00 unsafe-request block rate**; 30 tests and 94% coverage |
| **[Concurrent Web Crawler & Search Engine](https://github.com/brohum10/concurrent-web-crawler)** | Java/Spring crawler with bounded asynchronous jobs, concurrent BFS, crawl-safety controls, BM25 search, PostgreSQL, and Prometheus metrics | 25,000-document benchmark: **20.503 ms p95** and **1.000 Recall@10**; 19 deterministic tests |
| **[Mini Raft Store](https://github.com/brohum10/mini-raft-store)** | Dependency-free distributed key-value store with leader election, majority commits, durable logs, failover, and conflict repair | Multi-process tests kill and restart leaders/followers while verifying committed data and catch-up |
| **[Semantic Search & Response Platform](https://github.com/brohum10/semantic-search-platform)** | Local-first retrieval service using Flask, SQLite, FAISS, hybrid reranking, and source-backed extractive responses | 100,000-document benchmark: **16.625 ms p95**, **1.000 Recall@10**, and **1.000 MRR** |
| **[Causal Trace Analyzer](https://github.com/brohum10/causal-trace-analyzer)** | Vector-clock analysis that reconstructs a causal DAG, finds concurrent race suspects, and calculates a latency-critical path | 33 tests at **94.83% branch coverage**; 400-event benchmark improved from about **725 ms to 130.339 ms median** |
| **[Luma Journal](https://github.com/brohum10/LumaJournal)** | Privacy-first SwiftUI journal using Apple Foundation Models, on-device dictation, SwiftData, and review-before-write actions | No accounts, analytics, or network layer; protocol-backed services and deterministic mapping/date tests |
| **[Software Engineering Portfolio](https://github.com/brohum10/soham-portfolio)** | Responsive React/Vite portfolio presenting experience, architecture-focused projects, and reproducible project results | Accessible navigation, responsive layouts, downloadable résumé, and GitHub Pages deployment |

> Performance figures above come from the deterministic benchmark commands and recorded results in each project. They describe local synthetic workloads, not production traffic.

## Experience

- **ADT — Software Engineering Intern, AI & CX Systems:** Built Python/pandas and pytest workflows for 600+ AI-assisted interactions, surfaced 25+ defects, and reduced weekly triage from 5 hours to 90 minutes.
- **L3Harris — Software Engineering Intern, ML Systems:** Processed 200,000+ NASA NOS3 telemetry records and improved labeled attack recall from 68% to 83% through feature engineering and error analysis.
- **Alpha Net — Software Engineer Intern:** Shipped JavaScript/AWS workflows supporting 50,000+ monthly sessions and Swift/Kotlin REST features that reduced response time by 20%.

## Engineering toolkit

| | Technologies |
|:--|:--|
| **Languages** | Python · Java · C++ · C · JavaScript/TypeScript · SQL · Kotlin · Swift |
| **Backend & data** | Spring Boot · FastAPI · Flask · Node.js · PostgreSQL · SQLite · FAISS |
| **Systems & delivery** | Linux/Unix · Git · Docker · AWS · Google Cloud · pytest · JUnit · GitHub Actions |

## How I work

1. Start with behavior, invariants, and failure modes—not a framework.
2. Keep core logic behind small interfaces so it can be tested without external infrastructure.
3. Treat safety limits, useful errors, and operational visibility as product features.
4. Measure results with deterministic workloads and document exactly what those numbers mean.
5. Leave the next engineer a clear architecture, setup path, and honest list of trade-offs.

I’m seeking **Summer 2027 software engineering internships** in backend, infrastructure, data, and ML-adjacent engineering.
