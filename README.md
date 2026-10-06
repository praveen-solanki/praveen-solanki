<p align="center">
  <img src="./assets/hero.svg" width="100%" alt="Praveen Solanki - AI/ML Engineer" />
</p>

<p align="center">
  <strong>AI/ML Engineer building production systems around Generative AI, RAG, Knowledge Graphs, Agentic AI, and Context Intelligence.</strong>
</p>

<p align="center">
  <a href="#what-i-build">What I Build</a> &middot;
  <a href="#engineering--simpplr">Engineering @ Simpplr</a> &middot;
  <a href="#flagship-projects">Flagship Projects</a> &middot;
  <a href="#toolbox">Toolbox</a> &middot;
  <a href="#experience--education">Experience</a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/praveensolanki48">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:praveenthesoftwareengineer@gmail.com">
    <img src="https://img.shields.io/badge/Email-Say%20Hello-30363D?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="./docs/engineering-at-simpplr.md">
    <img src="https://img.shields.io/badge/Engineering%20Work-Read%20More-8957E5?style=flat-square&logo=github&logoColor=white" alt="Engineering work" />
  </a>
</p>

---

## About me

<p align="center">
  <img src="./assets/about-me.svg" width="100%" alt="About Praveen Solanki" />
</p>

<p align="center">
  I work on the engineering between a good AI demo and a reliable production system — retrieval, graphs, context, memory, safety, evaluation, and failure handling.
</p>

<details>
<summary><strong>More about what I focus on</strong></summary>
<br>

I am most interested in systems where **model quality is only one part of the problem**. The harder work is often deciding what context reaches the model, how knowledge is represented, how identities and relationships stay consistent, and how the system behaves when infrastructure is incomplete or wrong.

**Right now, my work is centered around:**
- enterprise Knowledge Graphs and GraphRAG
- agentic systems and policy / guardrail infrastructure
- scoped memory, personalization, and context lifecycle
- retrieval quality, evaluation, latency, and reliability
- turning research ideas into systems that can be benchmarked, debugged, and operated

**Background:** M.Tech CSE from IIT Mandi, currently building enterprise AI systems at Simpplr, with previous applied AI / enterprise RAG work at Bosch Global Software Technologies.

</details>

---

## What I build

<p align="center">
  <img src="./assets/what-i-build.svg" width="100%" alt="What I build — animated AI systems map" />
</p>

<p align="center">
  My work sits at the intersection of <strong>knowledge, retrieval, reasoning, memory, and production reliability</strong>. The orbit above represents the major system layers I repeatedly work across rather than isolated tools or models.
</p>

<details>
<summary><strong>Explore the systems behind the orbit</strong></summary>
<br>

### Knowledge & Context Systems
These systems decide **what the AI knows, how that knowledge is represented, and how the correct context is found**.

- **Knowledge Graph construction** — extracting entities, relationships, evidence, and provenance from enterprise data.
- **Entity / identity resolution** — determining when records refer to the same real-world person, object, or concept.
- **GraphRAG & multi-hop retrieval** — combining semantic retrieval with relationship traversal for questions that require more than one document or entity.
- **Context & memory architectures** — deciding what should be remembered, at which scope, and for how long.
- **Temporal / scoped personalization** — separating current, historical, session-level, team-level, and persistent information.

### Agentic & LLM Systems
These systems decide **how models act, which tools and policies they use, and how their outputs stay measurable and reliable**.

- **Multi-agent orchestration** — coordinating specialized agents and tool calls around a larger objective.
- **RAG pipelines & evaluation** — retrieval, reranking, grounded generation, and independent quality measurement.
- **Dynamic guardrails / policies** — applying tenant- and agent-specific safety behavior at runtime.
- **LLM routing & inference** — selecting and serving models according to workload, latency, and configuration.
- **Failure-aware workflows** — handling retries, truncation, rate limits, partial results, and unavailable dependencies.

</details>

---

## Engineering @ Simpplr

<p align="center">
  <img src="./assets/simpplr-engineering-v2.svg" width="100%" alt="Engineering at Simpplr — animated enterprise AI flow" />
</p>

<p align="center">
  I contribute to private enterprise AI systems across <strong>graph ingestion, retrieval, agent safety, memory, and production reliability</strong>. The flow above shows how those areas connect from knowledge ingestion to final user-facing AI behavior.
</p>

<details>
<summary><strong>Open engineering highlights</strong></summary>
<br>

### Knowledge Graph & GraphRAG
Focused on making enterprise knowledge **consistent, connected, and retrievable** across large corpora.

- corpus-level entity canonicalization and evidence preservation
- person / identity resolution across bulk and incremental ingestion
- relationship enrichment and multi-hop graph traversal
- cross-graph ranking, temporal handling, and duplicate reduction
- incremental processing that resolves new information against existing graph state

### Agent Safety Infrastructure
Worked on making safety behavior **configurable at runtime instead of hardcoded inside prompts**.

- tenant-aware guardrail categories
- Redis-backed policy retrieval with controlled fallbacks
- agent-specific guardrail application
- modular separation between policies and core agent prompts
- regression coverage for tenant switches, mappings, parsing, and fallback behavior

### Memory & Personalization
Worked on how user and team context is **stored, reconciled, authorized, and updated over time**.

- scoped memory writes and authorization checks
- add / update / delete / skip reconciliation decisions
- provenance and lifecycle handling
- distinguishing recurring information from one-time events
- tenant-aware model routing with bounded fallback behavior

### Production Reliability
Worked on the infrastructure around the AI path so failures are **visible, bounded, and recoverable**.

- batched and sharded checkpoint persistence
- request-size, token, timeout, and throttling controls
- bounded concurrency and memory-aware processing
- large WebSocket payload delivery
- Kafka / background-task observability
- graceful degradation when graph or supporting infrastructure is unavailable

<p align="center">
  <a href="./docs/engineering-at-simpplr.md"><strong>Read the full public-safe engineering summary →</strong></a>
</p>

</details>

---

## Flagship projects

<p align="center">
  <img src="./assets/flagship-projects.svg" width="100%" alt="Flagship projects — animated project spotlight" />
</p>

<p align="center">
  These projects were selected because each demonstrates a different part of my engineering range: <strong>agentic graph intelligence, rigorous RAG evaluation, real-time computer vision, and graph-based software intelligence</strong>.
</p>

<table>
<tr>
<td align="center" width="25%"><a href="https://github.com/praveen-solanki/AgenticMindGraph.ai"><strong>AgenticMindGraph.ai</strong></a><br><sub>Graph + Agentic Reasoning</sub></td>
<td align="center" width="25%"><a href="https://github.com/praveen-solanki/RAG-Full-Pipeline"><strong>RAG Full Pipeline</strong></a><br><sub>Hybrid vs Vectorless RAG</sub></td>
<td align="center" width="25%"><a href="https://github.com/praveen-solanki/ADAS-Perception-Pipeline"><strong>ADAS Perception</strong></a><br><sub>Real-time Computer Vision</sub></td>
<td align="center" width="25%"><a href="https://github.com/praveen-solanki/TestForge.ai-Automated-Test-Generation-Requirements-Traceability-System"><strong>TestForge.ai</strong></a><br><sub>Requirements ↔ Code Graph</sub></td>
</tr>
</table>

<details>
<summary><strong>01 — AgenticMindGraph.ai · graph + autonomous reasoning</strong></summary>
<br>

**Problem:** Technical specifications contain relationships, dependencies, contradictions, and evolving knowledge that flat document search cannot represent well.

**What I built:** An end-to-end system that converts technical PDFs into a Knowledge Graph and runs specialized agents for reasoning, conflict detection, evolution tracking, synthesis, and system monitoring.

**Engineering signal:** graph construction + agent orchestration + knowledge evolution + evaluation in the same system.

**Stack:** `Neo4j` · `LLMs` · `vLLM` · `BGE-M3` · `Multi-Agent Systems`

**[Explore the repository →](https://github.com/praveen-solanki/AgenticMindGraph.ai)**

</details>

<details>
<summary><strong>02 — RAG Full Pipeline · retrieval research + evaluation</strong></summary>
<br>

**Problem:** Complex engineering documentation requires both semantic retrieval and precise structural navigation; a single retrieval paradigm is not always enough.

**What I built:** A complete AUTOSAR intelligence pipeline comparing **Hybrid Vector RAG** with **Vectorless hierarchical retrieval** under a shared generation and evaluation setup.

**Evidence:** 103 specification PDFs · 4,500+ pages · 1,000+ validated QA pairs.

**Engineering signal:** dataset construction, retrieval benchmarking, controlled generation, evaluation, reproducibility, and research comparison rather than only a chatbot demo.

**Stack:** `BGE-M3` · `Qdrant` · `RRF` · `RAGAS` · `RAGChecker` · `vLLM`

**[Explore the repository →](https://github.com/praveen-solanki/RAG-Full-Pipeline)**

</details>

<details>
<summary><strong>03 — ADAS Perception Pipeline · real-time CV + performance engineering</strong></summary>
<br>

**Problem:** Real-time road perception requires multiple models to run together while preserving useful throughput and measurable accuracy.

**What I built:** A multi-model perception pipeline for vehicles, pedestrians, traffic signs, and traffic-light state with reproducible evaluation and backend benchmarking.

**Evidence:** **185.5 FPS** ONNX Runtime GPU · **mAP@0.5 = 0.554** · **97.82%** GTSRB traffic-sign accuracy.

**Engineering signal:** model integration, latency measurement, backend comparison, threshold analysis, reproducible evaluation, and documented failure cases.

**Stack:** `YOLO11m` · `ResNet-18` · `OpenCV` · `ONNX Runtime` · `BDD100K`

**[Explore the repository →](https://github.com/praveen-solanki/ADAS-Perception-Pipeline)**

</details>

<details>
<summary><strong>04 — TestForge.ai · requirements ↔ code intelligence</strong></summary>
<br>

**Problem:** Software requirements and implementation often drift apart, making traceability and change-impact analysis difficult.

**What I built:** A Unified Knowledge Graph connecting technical specifications with implementation details and exposing coverage, semantic drift, ghost requirements, natural-language-to-Cypher querying, and code-change impact analysis.

**Engineering signal:** graph modeling + AST/code analysis + LLM reasoning + backend APIs + interactive visualization.

**Stack:** `Neo4j` · `FastAPI` · `React` · `vLLM` · `Tree-sitter` · `Embeddings`

**[Explore the repository →](https://github.com/praveen-solanki/TestForge.ai-Automated-Test-Generation-Requirements-Traceability-System)**

</details>

---

<details>
<summary><strong>More projects worth exploring</strong></summary>
<br>

- **[InvenTrack](https://github.com/praveen-solanki/InvenTrack)** - production-ready inventory/order management system with FastAPI, React, atomic transactions, and live deployment.
- **[TB Bacilli Detection via Super-Resolution + Segmentation](https://github.com/praveen-solanki/TB-Bacilli-Detection-via-Super-Resolution-Segmentation)** - medical-imaging pipeline combining restoration and segmentation.
- **[Brain-2-Text](https://github.com/praveen-solanki/Brain-2-Text)** - neural decoding / EEG-to-text research project.
- **[Adaptive N-Back Task](https://github.com/praveen-solanki/Adaptive-N-Back-Task)** - adaptive cognitive assessment system.

</details>

---

## Toolbox

<p align="center">
  <img src="./assets/toolbox.svg" width="100%" alt="Animated AI engineering toolbox" />
</p>

<p align="center">
  I use tools as parts of a system, not as a checklist. The stack below reflects what I use across <strong>modeling, retrieval, graphs, backend infrastructure, evaluation, and deployment</strong>.
</p>

<details>
<summary><strong>Open the stack by category</strong></summary>
<br>

| Area | Stack |
|---|---|
| **Generative AI** | LLMs · RAG · GraphRAG · Agentic AI · Embeddings · Prompt Engineering · Evaluation |
| **Graph & Retrieval** | Neo4j · Qdrant · Elasticsearch · Entity Resolution · Multi-hop Retrieval · Hybrid Search |
| **LLM Infrastructure** | vLLM · OpenAI-compatible APIs · Redis · Model Routing · Concurrency / Throttling |
| **Deep Learning / CV** | PyTorch · TensorFlow · Transformers · YOLO · OpenCV · ONNX Runtime |
| **Backend / Systems** | Python · FastAPI · MongoDB · Kafka · WebSockets · Docker · Linux |

</details>

---

## How I think about AI engineering

<p align="center">
  <img src="./assets/engineering-thinking.svg" width="100%" alt="Animated AI engineering principles waveform" />
</p>

<p align="center">
  The waveform represents four principles I repeatedly use when designing AI systems: <strong>retrieve the right evidence, structure the context, design for failure, and measure the system independently</strong>.
</p>

<details>
<summary><strong>01 — Retrieval before generation</strong></summary>
<br>
A strong model cannot compensate for consistently weak evidence. I care about ranking, freshness, entity identity, graph traversal, provenance, and context selection before the answer reaches the LLM.
</details>

<details>
<summary><strong>02 — Context needs structure</strong></summary>
<br>
Flat memory and top-k retrieval are useful, but many enterprise problems need scope, relationships, validity, lifecycle, and history. That is where graphs and governed context become valuable.
</details>

<details>
<summary><strong>03 — Production AI must fail well</strong></summary>
<br>
Timeouts, model truncation, oversized payloads, stale caches, unavailable stores, partial evidence, and rate limits are part of the system — not edge cases to ignore.
</details>

<details>
<summary><strong>04 — Evaluation is part of the product</strong></summary>
<br>
I prefer measurable systems: benchmark retrieval separately, freeze generation when comparing retrievers, document failure cases, and make important results reproducible.
</details>

---

## Experience & education

<p align="center">
  <img src="./assets/experience-timeline-v2.svg" width="100%" alt="Animated experience and education timeline" />
</p>

<p align="center">
  My path has moved from academic AI research into applied enterprise RAG and now into broader production AI infrastructure spanning graphs, agents, retrieval, memory, and reliability.
</p>

<details>
<summary><strong>Open the timeline in detail</strong></summary>
<br>

### Simpplr · 2026 — now
**Associate Data Scientist / AI-ML Engineering**

Working on enterprise AI systems across:
- Knowledge Graph ingestion and entity resolution
- GraphRAG and multi-hop enterprise retrieval
- agent safety / guardrail infrastructure
- memory and personalization systems
- LLM infrastructure, reliability, and observability

### Bosch Global Software Technologies · 2026
**Applied AI / Enterprise RAG**

Worked on RAG for complex AUTOSAR engineering documentation, including:
- document extraction and structured chunking
- Hybrid RAG using dense + sparse retrieval
- Vectorless / hierarchical retrieval research
- retrieval and generation evaluation
- benchmarking and reproducibility

### IIT Mandi · 2024 — 2026
**M.Tech — Computer Science & Engineering**

Built a stronger foundation in machine learning, deep learning, NLP, computer vision, and research-oriented experimentation that later carried into production AI work.

</details>

---

## A small terminal view of my work

<p align="center">
  <img src="./assets/current-focus-terminal.svg" width="100%" alt="Animated live engineering focus terminal" />
</p>

<p align="center">
  This is the compact version of how I currently think about production AI: <strong>preserve knowledge, retrieve useful evidence, govern agent behavior, retain the right context, and engineer for real failure modes</strong>.
</p>

<details>
<summary><strong>Decode the engineering log</strong></summary>
<br>

- **[graph]** — preserve identity, evidence, relationships, provenance, and historical context instead of flattening everything into text.
- **[rag]** — retrieve and rank the right context before asking the model to reason.
- **[agents]** — give agents the correct tools, permissions, policies, and execution scope.
- **[memory]** — retain useful context while distinguishing persistent information from temporary or one-time instructions.
- **[prod]** — expect timeouts, payload limits, stale state, partial dependencies, retries, and observability requirements from the beginning.

</details>

---

<p align="center">
  <strong>Interested in production Generative AI, graph intelligence, retrieval systems, and agent infrastructure?</strong>
</p>

<p align="center">
  <a href="mailto:praveenthesoftwareengineer@gmail.com">Let's talk</a>
  &middot;
  <a href="https://linkedin.com/in/praveensolanki48">LinkedIn</a>
  &middot;
  <a href="https://github.com/praveen-solanki?tab=repositories">Repositories</a>
</p>

<p align="center">
  <sub>Designed to be read by humans first - metrics and visuals are here only when they communicate engineering signal.</sub>
</p>
