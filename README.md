# Debajyoti Hazra
**AI Systems & Backend Infrastructure Engineer**  
*West Bengal, India* · [GitHub](https://github.com/Debajyoti02-mac)

---

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                                                                             │
│   debajyoti@infrastructure:~$ whoami                                        │
│   Debajyoti Hazra — AI Systems & Distributed Backend Engineer               │
│                                                                             │
│   debajyoti@infrastructure:~$ cat current_focus.json                        │
│   {                                                                         │
│     "domain": ["Production REST APIs", "Deterministic Agentic Systems"],    │
│     "foundations": ["DSA (Data Structures & Algorithms)", "System Design"], │
│     "arch": ["Hybrid RAG (Dense + Sparse)", "MCP Protocol", "FastAPI"]      │
│   }                                                                         │
│                                                                             │
│   debajyoti@infrastructure:~$ uptime --engineering                          │
│   Active | Mode: Learn → Architect → Ship → Benchmark                       │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

### 🏛️ Engineering & System Architecture

```
                       ┌────────────────────────────────────────┐
                       │           Client / REST Client         │
                       └───────────────────┬────────────────────┘
                                           │ HTTP / OpenAPI
                                           ▼
                       ┌────────────────────────────────────────┐
                       │          FastAPI Service Layer         │
                       └───────────────────┬────────────────────┘
                                           │
                    ┌──────────────────────┴──────────────────────┐
                    ▼                                             ▼
       ┌──────────────────────────┐                  ┌──────────────────────────┐
       │   Agent Loop (LangGraph) │                  │    MCP Server Cluster    │
       └────────────┬─────────────┘                  └────────────┬─────────────┘
                    │                                             │
      ┌─────────────┴─────────────┐                 ┌─────────────┴─────────────┐
      ▼                           ▼                 ▼                           ▼
┌───────────────┐         ┌───────────────┐   ┌───────────┐             ┌───────────┐
│ Dense Search  │         │ Sparse Search │   │ Tool Execution│           │ Evaluator │
│ (Chroma Vector│         │ (BM25 Index)  │   │ (AST Safe Math│           │ (Ragas /  │
│  Embeddings)  │         │               │   │  / Git I/O)   │           │ Ollama)   │
└───────┬───────┘         └───────┬───────┘   └───────────┘             └───────────┘
        │                         │
        └────────────┬────────────┘
                     ▼
       ┌──────────────────────────┐
       │ Reciprocal Rank Fusion   │
       │ (RRF Context Re-ranking) │
       └──────────────────────────┘
```

---

### 🚀 Technical Repository Index

| Project Repository | Architectural Focus | Core Tech Stack |
| :--- | :--- | :--- |
| [`fastapi-agents`](https://github.com/Debajyoti02-mac) | Production-ready REST endpoints wrapping multi-tool LLM workflows with strict `Pydantic` schema validation & structured error handling. | `FastAPI`, `Pydantic`, `Uvicorn`, `Python` |
| [`mcp-servers`](https://github.com/Debajyoti02-mac) | Model Context Protocol servers enabling deterministic tool usage (AST arithmetic execution, file systems, Git state manipulation). | `MCP SDK`, `AST Parsing`, `Python` |
| [`self-rag`](https://github.com/Debajyoti02-mac) | Self-reflective RAG with adaptive retrieval, dynamic routing, and automated evaluation metrics tracking context relevancy. | `LangChain`, `Ragas`, `Groq`, `Ollama` |
| [`hybrid-rag-engine`](https://github.com/Debajyoti02-mac) | Multi-stage retrieval combining dense vector embeddings with sparse term matching via Reciprocal Rank Fusion (RRF). | `ChromaDB`, `BM25`, `RRF`, `PyTorch` |
| [`dsa-patterns`](https://github.com/Debajyoti02-mac) | Algorithmic problem solving focusing on space/time complexity optimization (Arrays, Trees, Graphs, Dynamic Programming). | `Python`, `Algorithms`, `Data Structures` |

---

### 🛠️ Technical Stack & System Specs

```text
Backend Engineering   ::  FastAPI · REST API Design · Pydantic · System Design (Distributed Caching, Rate Limiting)
AI / Systems Stack    ::  LangChain · LangGraph · Model Context Protocol (MCP) · PyTorch · Ragas Evaluation
Information Retrieval ::  Hybrid Search (Dense + Sparse) · ChromaDB · FAISS · BM25 · Reciprocal Rank Fusion (RRF)
Compute & Execution   ::  Groq LPU (Low-Latency Inference) · Local Ollama (Quantized Benchmark Execution on Apple Silicon)
Core Languages        ::  Python 3.12+ · SQL (SQLite / PostgreSQL) · Shell Scripting
```

---

### 📐 System Design Principles & Philosophy

* **Deterministic Tool Call Safety:** Prefer strict AST parsing and sandboxed mathematical evaluation over unconstrained LLM code execution.
* **Context Relevancy Optimization:** Maximize retrieval signal-to-noise ratios via hybrid search (Dense + BM25) and rank fusion, lowering LLM token latency and memory footprint.
* **Production-First AI:** Avoid opaque multi-agent abstractions when single-agent or multi-tool REST services provide higher throughput, easier tracing, and zero bloat.
* **Resource-Aware Engineering:** Optimize local inference pipelines (Ollama) to manage memory constraints effectively on Apple Silicon hardware.

---

### 📊 System Metrics & Metrics Overview

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Debajyoti02-mac&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="Debajyoti's GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Debajyoti02-mac&layout=compact&theme=dark&hide_border=true" alt="Top Languages" width="48%" />
</p>

---

```
debajyoti@infrastructure:~$ exit
```
