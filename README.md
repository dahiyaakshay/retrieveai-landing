# RetrieveAI

RetrieveAI is a **Scoped-First AI Retrieval Intelligence Engine** built to measure how generative AI systems retrieve, interpret, and represent a brand.

Unlike traditional SEO tools that measure rankings on search engines, RetrieveAI analyzes **inclusion inside LLM inference** — modeling how brands surface in AI-generated answers.

This is not an SEO tool.

This is Retrieval Engineering infrastructure.

---

## 🧠 The Problem

Search has shifted.

Users increasingly ask AI systems instead of browsing search results.  
Large language models synthesize, summarize, compare, and recommend brands — often without exposing traditional ranking signals.

Brands now compete inside:

- Chat-based answers
- AI summaries
- Conversational recommendations
- Multi-source synthesis outputs

Traditional analytics tools do not measure this layer.

RetrieveAI does.

---

## 🚀 What RetrieveAI Does

RetrieveAI transforms a website into a scoped, structured retrieval intelligence audit using:

- URL discovery & taxonomy classification
- Context-aware audit scoping
- Structured content extraction
- Entity reinforcement modeling
- Deterministic prompt simulation
- Retrieval coverage scoring
- Multi-dimensional AI visibility scoring

It produces a unified score system that reflects:

- AI Visibility
- Entity Strength
- Structured Clarity
- Retrieval Coverage
- Commerce Readiness (architecture-ready)

---

## 🏗 Architectural Philosophy

RetrieveAI is designed with production-grade backend discipline.

### 1️⃣ Scoped-First Audit Model

Rather than crawling entire websites blindly, RetrieveAI introduces structured audit scopes:

- `single_page`
- `context_cluster`
- `category`
- `full_site`

The **Context Cluster model** preserves cross-page authority signals without requiring full-site cost overhead.

This balances:
- Accuracy
- Performance
- Cost control
- Signal integrity

---

### 2️⃣ Deterministic LLM Simulation

RetrieveAI enforces:

- `temperature = 0`
- Pinned model versions
- Versioned cache keys
- Embedding deduplication

This ensures score stability across runs and enables meaningful delta comparison.

LLM calls are treated as infrastructure, not experiments.

---

### 3️⃣ Defensive Engineering Patterns

The system architecture includes:

- Central audit orchestrator
- Idempotent phase execution
- Hard runtime caps
- Circuit breaker per provider
- Postgres semaphore concurrency control
- Transaction boundaries (BEGIN / COMMIT / ROLLBACK)
- Snapshot locking for audit immutability
- Cost ledger per API call
- Batch embedding control

RetrieveAI is built to fail gracefully — not crash silently.

---

### 4️⃣ Scope-Aware Scoring Engine

Scores adjust expectations based on audit depth.

Signal flags communicate reduced context when:

- Single-page audits are run
- Coverage universe is intentionally constrained

This preserves mathematical honesty in scoring.

---

## 📊 Core Engine Layers

RetrieveAI is structured into layered execution phases:

1. URL Discovery (lightweight sitemap reconnaissance)
2. Scope Selection
3. Context Bundle Generation
4. Crawl & Extraction
5. Structured Data & Technical Audit
6. Entity & Content Analysis
7. Prompt Simulation Engine
8. Unified Scoring Engine
9. Recommendation Engine
10. Snapshot & Delta Comparison

Each phase is isolated, resumable, and transaction-wrapped.

---

## 🔬 Retrieval ≠ Ranking

RetrieveAI operates on a different paradigm:

| Traditional SEO | RetrieveAI |
|----------------|------------|
| Measures ranking position | Measures answer inclusion |
| Crawls entire site | Scoped-first context modeling |
| Page-level optimization | Retrieval-level optimization |
| Keyword signals | Entity & intent signals |
| SERP visibility | LLM inference visibility |

The goal is not to rank.

The goal is to be retrieved.

---

## ⚙️ Technology Stack

- Node.js (service-layer architecture)
- TypeScript (strict mode)
- PostgreSQL (pgvector-enabled)
- Playwright (headless crawl engine)
- Deterministic LLM dispatch
- Modular scoring engine
- Defensive orchestration patterns

No Redis.  
No unnecessary abstraction layers.  
Single-datastore architecture.

---

## 📈 Intended Audience

RetrieveAI is designed for:

- AI-era marketing teams
- Enterprise SEO strategists
- Technical founders
- AI product teams
- Structured data architects

Anyone who needs to understand how AI systems reason about their brand.

---

## 🧭 Positioning

RetrieveAI operates in the emerging category of:

- Retrieval Engineering
- AI Visibility Intelligence
- LLM-Aware Marketing Infrastructure
- Machine Trust Architecture

It is built for the post-search ecosystem.

---

## 📁 Repository Contents

This repository contains the public-facing landing prototype.

The full backend, simulation engine, and scoring logic are private.

---

## 👤 Developer

Built and designed by **Akshay**

Focused on AI-native marketing infrastructure and retrieval engineering systems.
