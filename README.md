# Alan Wang

**AI / Agentic Systems Engineering · Backend / Distributed Infrastructure**

I’m interested in the point where a model’s answer becomes a system’s action: what it can observe, what it may change, and how we know the result is correct.

Computer Science graduate from **Nanyang Technological University**, based in Singapore. My experience spans **RAG and LLM applications at Binance**, **backend services supporting ML workflows at ByteDance**, and now **Redis / KV infrastructure at Xiaomi**.

[LinkedIn](https://www.linkedin.com/in/yangming-wang/) · [Email](mailto:agooseelan@gmail.com)

## Engineering projects

### OpsPilot — AI Production Incident Copilot
**LangGraph · MCP · BM25 · Signed approvals**

An incident copilot with a compiled stateful workflow, MCP HTTP tools, a BM25 knowledge index, signed approval verification, and persistent audit records. Its PostgreSQL path uses durable checkpoints; an in-memory fallback is separate. Implemented locally, with public release preparation in progress.

An actual-model smoke run with synthetic telemetry and an in-memory graph stopped at human approval. This is separate from deterministic workflow tests and does not establish production RCA quality. Public source and evidence links are not yet available.

### Transaction Processing Platform
**Java · PostgreSQL · Kafka**

A ledger with exact integer balances, durable idempotency, a fenced transactional outbox, and idempotent consumer effects, with tests for concurrency, crashes, and outages. Implemented locally, with public release preparation in progress.

Public source and evidence links are not yet available. Local benchmark studies do not establish production capacity or exactly-once messaging.

### [Redis Reliability Lab](https://github.com/Alaneel/redis-reliability-lab)
**Go · Redis Cluster · Docker**

A fault laboratory that measures service recovery, restored redundancy, and acknowledged-write survival separately. Its offline diagnostic extension cites recorded observations, preserves uncertainty, and produces read-only remediation plans.

[Code](https://github.com/Alaneel/redis-reliability-lab/tree/main/internal) · [Run a fault experiment](https://github.com/Alaneel/redis-reliability-lab/blob/main/docs/running-experiments.md) · [Case studies](https://github.com/Alaneel/redis-reliability-lab/blob/main/docs/aiops-case-studies.md) · [Evaluation & limits](https://github.com/Alaneel/redis-reliability-lab/blob/main/docs/aiops-evaluation.md) · [Tests & execution evidence](https://github.com/Alaneel/redis-reliability-lab/blob/main/docs/phase4-validation.md)

The diagnosis engine is deterministic and has no LLM integration. Results come from a small, single-host laboratory; they do not establish production RCA accuracy or power-loss durability.

## Where I’ve worked

- **Binance** — RAG / LLM application work with Dify and Lucene.
- **ByteDance** — backend services supporting ML workflows.
- **Xiaomi** — Redis / KV infrastructure.

## Beyond the shortlist

[Video Toolkit](https://github.com/Alaneel/video-toolkit) — a Rust desktop app and CLI for local media workflows. [Release packages](https://github.com/Alaneel/video-toolkit/releases/tag/v2.1.0).

I like projects with inspectable state, reproducible failures, and evidence that survives a closer look.

