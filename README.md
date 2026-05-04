# Khalid Hussain

**Agentic AI Systems Developer** — Karachi, Pakistan

I build production-shaped agentic AI systems: routed multi-agent graphs, RAG pipelines with grounded citations, MCP-exposed tools, and the full-stack apps that put them in front of real users.

**Core stack:** LangGraph · FastAPI · MCP · RAG (ChromaDB + sentence-transformers) · React · PostgreSQL

---

## Pinned Projects

### Customer Support Agents — Agentic Support System
> LangGraph router · MCP tools · RAG · streaming SSE · [Repo](https://github.com/Khalid147-alt/customer-support-agents)

Production-shaped support agent. A `flash-lite` router classifies each turn into `rag` / `tool` / `escalate` before any expensive work runs. Tools (order lookup, product info, ticket creator) are exposed both **in-process** and over **MCP** (`FastMCP`) for protocol correctness. End-to-end token streaming via LangGraph `astream_events v2` → FastAPI SSE → React `ReadableStream`. Auto-escalation creates `TKT-YYYY-NNNN` tickets in Postgres.

**Stack:** FastAPI · LangGraph · MCP · ChromaDB · PostgreSQL · React/Vite · Docker · Gemini 2.5

---

### FlatSplit — Multi-Tenant Expense PWA
> Next.js 16 · AI receipt scanning · approval flows · [Live](https://flatsplit-two.vercel.app/) · [Repo](https://github.com/Khalid147-alt/flatsplit)

Built to solve a real problem in my own shared flat. Multi-tenant houses with admin approval flows for expenses, contribution pools, rent/WiFi/water tracking, and AI-powered receipt scanning that auto-fills expense data. Security-hardened: rate limiting, IDOR protection, CSP, bcrypt + JWT in httpOnly cookies.

**Stack:** Next.js 16 · React 19 · TypeScript · Prisma · PostgreSQL · Upstash Redis · Claude API · Tesseract.js · Web Push

---

### DocMind — RAG Document Intelligence *(in development)*
> Cited document Q&A over user-uploaded PDFs

Retrieval-augmented Q&A pipeline with MMR retrieval for diversity and source-cited responses, so users see exactly which chunks the model leaned on.

**Stack:** Python · LangChain · ChromaDB · HuggingFace `all-MiniLM-L6-v2` · Claude API · FastAPI

---

## Tech Stack

| Area | Technologies |
|------|-------------|
| Agentic AI | LangGraph · LangChain · MCP (FastMCP) · CrewAI · structured-output routing · streaming via SSE |
| RAG | ChromaDB · sentence-transformers · MMR / diversity re-rank · relevance-thresholded citations |
| Backend | FastAPI · Node.js · PostgreSQL · Prisma · asyncpg · JWT |
| Frontend | React · Next.js · TypeScript · Tailwind · Vite |
| LLMs | Anthropic Claude · Google Gemini · OpenAI |
| Infra | Docker · Vercel · Railway · Upstash Redis |

---

## Currently Learning

- Multi-agent coordination patterns and shared memory
- A2A (Agent-to-Agent) Protocol
- LLM observability and production tracing (LangSmith)

---

## Connect

📧 [sindhikhalid126@gmail.com](mailto:sindhikhalid126@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/khalid-hussain-55714727a) · 🐦 [@KhalidUnar27322](https://x.com/KhalidUnar27322)

*Open to freelance and remote roles in agentic AI and full-stack development.*
