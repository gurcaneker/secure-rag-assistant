# Secure RAG Assistant (Public Demo)

Security-aware Retrieval-Augmented Generation (RAG) demo inspired by 
public-sector needs.
This project showcases how to build a **document Q&A assistant** with a 
focus on **confidentiality**, **access boundaries**, and **auditability**.

> ⚠️ Public demo only: **No institutional data** is used. All documents 
are synthetic/sample.

## Why this project
Regulated environments (public sector, finance, healthcare) need AI 
assistants that:
- reduce hallucinations by grounding answers in retrieved context,
- enforce access boundaries (at least conceptually),
- keep an auditable trail of what was asked and what was used to answer.

## Key Features (Demo Scope)
- Document ingestion → chunking → indexing (sample docs)
- Query-time retrieval + answer synthesis
- Basic role-based access concept (demo-level)
- Logging & traceability (demo-level)

## Tech Stack
- Python
- FastAPI
- Vector search (pluggable)
- Docker (optional)

## Docs
- Architecture: `docs/architecture.md`
- Threat model: `docs/threat-model.md`

## Roadmap
- [ ] Minimal API endpoints (ingest / query)
- [ ] Evaluation scripts (quality checks)
- [ ] Access-control demo layer
- [ ] Tests + CI

