# Hi, I'm Won Been Lee

I build secure, AI-native products that turn noisy signals into actionable insight.  
Right now I split my time between two mission-driven teams:

- **MailShieldAI** - enterprise email security with LLM-powered mail triage, adversarial testing, and a Go/TypeScript production stack.
- **BinaryMedAI** - healthcare anomaly detection where FastAPI microservices orchestrate ML pipelines and reporting flows across clinical teams.

## What I'm Building
- **LLM Gateways that ship to prod**: architected `mailshieldai/llm-gateway`, bridging Vercel AI SDK frontends with LangChain agents, Harmony tool calling, MCP server discovery, and Ollama streaming completions.
- **Evaluation at scale**: designed a Grok + Faker synthetic data generator that stress-tests MailShieldAI's models with realistic phishing payloads.
- **Service meshes you can reason about**: refactored BinaryMed's orchestrator into a layered FastAPI design (config via Pydantic, loguru observability, typed DTO boundaries) with togglable mock data for frontend-first delivery.
- **Docs that unblock teams**: consolidated deployment runbooks, troubleshooting guides, and API reference so new contributors can ship without hand-holding.

## Highlights from MailShieldAI
- Crafted modular LangChain adapters for MCP tool ecosystems and message pipelines (`mailshieldai/llm-gateway`), slashing legacy code by >70% while enabling auth-aware tool injection.
- Built streaming-safe message translators between Vercel AI SDK clients and LangChain backends, plus extensive pytest coverage and UV-managed builds for reliability.
- Delivered Jinja-backed prompt systems, multi-model (OpenAI-compatible + Ollama) support, and Go services that front the threat-scoring backend.
- Shipped TypeScript/Next.js frontends, Go microservices, and Python-based synthetic evaluators to keep the detection stack honest end-to-end.

## Highlights from BinaryMedAI
- Reimagined the orchestration layer as a clean service boundary: FastAPI routers -> service logic -> MongoDB/ADM/PDFM adapters with deterministic DTOs.
- Added on-demand PDF generation, schedule lifecycle management, and DEBUG-mode mock data to keep the frontend unblocked during integrations.
- Standardized deployment with Docker Compose, UV package management, and network-aware `.env` bootstraps for rapid demos.
- Authored expandable documentation (architecture, deployment, troubleshooting) so the medical ops team can self-serve.

## Technical Toolkit
- **Languages**: TypeScript, Python, Go, SQL basics, Shell
- **Frameworks & AI**: FastAPI, LangChain, Vercel AI SDK, Harmony spec, Ollama, Pydantic, pytest / pytest-asyncio
- **Frontend**: Next.js, React, Tailwind, component-driven prototyping
- **Infrastructure & Ops**: Docker, Docker Compose, uv, GitHub Actions, structured logging (loguru), MCP tooling
- **Practices**: Modular architectures, typed DTO contracts, synthetic dataset generation, defense-in-depth for email and healthcare domains

## Currently Exploring
- Agentic security workflows that mix static detection with human-in-the-loop review.
- LLM-powered red teaming for phishing and medical anomaly pipelines.
- Safer deployment playbooks for regulated environments (SOC2, HIPAA-ready roadmaps).

## Let's Collaborate
I'm always up for pairing on security tooling, ML evaluation frameworks, or developer experience upgrades.

📫 `owen@mailshield.ai` | `wonbeenlee093@gmail.com`


