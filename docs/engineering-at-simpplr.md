# Engineering @ Simpplr

> Selected highlights from my work across private enterprise AI systems.  
> This page intentionally excludes proprietary code, customer data, internal identifiers, and confidential implementation details.

## What I work on

My work focuses on the engineering required to make **enterprise AI systems accurate, scalable, governable, and reliable in production** — spanning ingestion, graph construction, retrieval, agents, personalization, safety, and final-answer delivery.

`Knowledge Graphs` · `GraphRAG` · `Enterprise Retrieval` · `Agentic AI` · `AI Guardrails` · `Memory & Personalization` · `Entity Resolution` · `Production LLM Systems`

---

## Knowledge Graphs & Entity Resolution

- Improved corpus-level **entity canonicalization** so descriptions, aliases, relationships, source evidence, and access-control metadata survive multi-document processing.
- Built and refined **person identity resolution** across bulk and incremental ingestion, including renamed identities and same-name disambiguation.
- Strengthened incremental processing so new claims can resolve against previously processed corpus state.
- Improved people, authorship, organization, and relationship modeling while keeping source-specific connector logic isolated.
- Introduced **size-aware LLM batching** for description aggregation to reduce oversized prompts and unnecessary model calls.
- Simplified connector ingestion by consuming structured, pre-resolved people data and removing unnecessary runtime enrichment work.

## GraphRAG & Enterprise Retrieval

- Improved **cross-graph evidence ranking** so useful evidence from later graph sources is not hidden by premature limits.
- Added relationship-focused enrichment and **multi-hop traversal** for organizational, authorship, and other structured connections.
- Improved ranking using relevance, recency, trust, support, and source quality while preserving conflicting evidence.
- Added current-vs-historical people handling so inactive identities are filtered from current-state answers while remaining available for historical questions.
- Improved team, department, and people-list retrieval with explicit truncation and incomplete-result reporting.
- Made answer structure more deterministic across table, timeline, per-person, and prose responses.
- Reduced duplicated context through better document deduplication and evidence allocation.

## Agent Guardrails & Policy Infrastructure

- Developed tenant-aware **guardrail category management** for configurable runtime safety controls.
- Integrated dynamic guardrail retrieval from **Redis** with controlled fallback behavior.
- Added support for agent-specific guardrail identifiers so agents receive only applicable policies.
- Separated policy composition from core agent prompts to make safety behavior more modular and configurable.
- Added regression and integration coverage for guardrail mappings, tenant switches, parsing, fallback behavior, and execution paths.

## Memory & Personalization

- Extended scoped memory writes to support **team-level context** with authorization, provenance, workspace derivation, and strict API validation.
- Improved reconciliation rules for deciding when information should be **added, updated, deleted, or skipped**.
- Strengthened privacy-aware handling of sensitive information and explicit deletion requests.
- Improved distinction between recurring user information and one-time events.
- Added tenant-aware LLM model routing with cached model inventory and bounded fallback behavior.

## Production Reliability & Scale

- Added **sharded and batched checkpoint persistence** for large graph-ingestion runs.
- Hardened embedding workloads around API limits, timeouts, retries, and coordinated throttling.
- Reduced memory pressure in large clustering/canonicalization workloads through bounded processing.
- Added defensive handling for oversized database writes and persistence batches.
- Split oversized **WebSocket payloads** so citations, evidence, actions, and long answers can be reconstructed instead of silently dropped.
- Improved Kafka, WebSocket, background-task, storage, and retrieval observability.
- Preserved fast retrieval paths during graph outages by separating modes that require graph verification from modes that should stay graph-independent.

---

## Engineering principles behind the work

**Correctness first** — preserve evidence, relationships, ACL metadata, and provenance.  
**Graceful degradation** — partial infrastructure failures should not unnecessarily break user-facing AI flows.  
**Bounded scale** — concurrency, persistence, batching, prompt size, and memory usage need explicit limits.  
**Retrieval quality** — ranking, freshness, relationships, temporal behavior, and answer consistency matter as much as generation quality.  
**Safety & governance** — authorization, tenant isolation, guardrails, and memory lifecycle are first-class system concerns.  
**Test with the change** — regression and integration coverage should ship with behavior changes, not later.

---

## Technologies

**AI / GenAI:** LLMs, RAG, GraphRAG, embeddings, prompt orchestration, agentic systems, guardrails, memory systems  
**Graph & Retrieval:** Neo4j, knowledge graphs, entity resolution, multi-hop retrieval, semantic ranking  
**Backend & Data:** Python, REST APIs, Redis, MongoDB, Kafka, WebSockets  
**Engineering:** async processing, concurrency control, caching, checkpointing, fault tolerance, observability, automated testing
