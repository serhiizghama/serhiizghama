# Hey, I'm Serhii 👋  &nbsp; I 💚 Backend

**6+ years in distributed systems · building AI-native architecture**

> 🌍 Open to remote opportunities — backend, AI systems, agent infrastructure

---

- **Core stack:** Node.js · TypeScript · NestJS · Go · AWS
- Built and scaled **microservices in production** — 40+ services (Fintech) and 98-service clinical data lake (Life Sciences)
- Deep **AWS** experience: Lambda, ECS, SQS, S3, API Gateway, Secrets Manager, CodeBuild
- Event-driven architecture: **Kafka · RabbitMQ · Redis Streams**
- Actively building **AI agent infrastructure** — multi-agent runtimes, LLM orchestration, MCP servers
- MSc thesis: **Gamma** — a browser-native multi-agent runtime system (NestJS microkernel + Redis Streams Memory Bus)
- Open-source contributor — **60+ merged PRs** in AI-tooling repos, repeat contributor in 12 of them — TypeScript agent frameworks, now expanding into Python/Go LLM infrastructure (embeddings, structured generation, agent memory)

---

### 🤖 AI & LLM Stack

What I actually use and build with:

| Tool / Technology | How I use it |
|---|---|
| **Anthropic Claude API** | Agent reasoning, orchestration, code generation, multi-turn pipelines |
| **OpenAI API** (GPT-4) | Multi-provider gateway, fallback routing, embeddings |
| **Google Gemini API** | Vision, classification, real-time narration (gemini-2.0-flash) |
| **Model Context Protocol (MCP)** | Building MCP servers for external services (Monobank, Viber, etc.) |
| **RAG + pgvector** | Semantic search pipelines over custom knowledge bases |
| **Ollama / Llama 3 / Qwen** | Local inference, offline agent loops, cost-free experimentation |
| **Multi-agent architecture** | Hierarchical agent systems with lifecycle management, inter-agent bus |
| **SSE + WebSocket streaming** | Real-time LLM token delivery to clients |

**Personal AI Projects — MCP servers (TypeScript):**
- **[monobank-mcp](https://github.com/serhiizghama/monobank-mcp)** — MCP server for Monobank Open API: accounts, statements, exchange rates, webhooks, Corporate API
- **[liqpay-mcp](https://github.com/serhiizghama/liqpay-mcp)** — MCP server for LiqPay, Ukraine's leading payment platform (PrivatBank)
- **[viber-mcp](https://github.com/serhiizghama/viber-mcp)** — MCP server for Viber messenger (Rakuten Viber Bot API)

---

### 🤝 Open-Source Contributions

Active contributor across AI-tooling and LLM-infrastructure repos — sorted by merge depth, not just stars. Two-year focus on TypeScript agent frameworks, now branching into Python/Go AI-core projects (structured generation, embeddings, agent memory, LLM clients).

| Project | Company / Author | ⭐ | Merged | What I fixed |
|---|---|---|---|---|
| [yamadashy/repomix](https://github.com/yamadashy/repomix) | Kazuki Yamada | 28k | 10 | Windows path-separator tree bug, `--token-count-tree` underscore-dir bug, Cloudflare Turnstile fix, GitHub shorthand auto-detect, case-insensitive extensions, oversized-directory output split, markdown fence widened against embedded diffs, extensionless-filename language hint, output-path POSIX normalization |
| [assistant-ui/assistant-ui](https://github.com/assistant-ui/assistant-ui) | Assistant-UI | 12k | 9 | Popover tab-select fix, AG-UI message export, reasoning copy exclusion, LangGraph subgraph tool-call/interrupt surfacing, `threadId`/`initialThreadId` forwarding, human-in-the-loop resume on falsy tool result, composer attachments visible during in-flight upload, persist paused LocalRuntime runs across refresh, preserve metadata across joined assistant messages |
| [mastra-ai/mastra](https://github.com/mastra-ai/mastra) | Mastra | 27k | 6 | `DurableAgent` readOnly-memory & tool-fork fixes, leaked scorer-hook cleanup, Gemini tool-schema typeless-property handling, stream `onFinish` payload fix, Datadog LLM Obs tag promotion |
| [theopenco/llmgateway](https://github.com/theopenco/llmgateway) | LLM Gateway | 1.6k | 5 | Vertex OAuth header auth, cached-mutation staleness through uncached db reads, streaming Responses-API output-index collision, Vertex-Anthropic streaming token usage extraction, JSON healing with braces inside strings |
| [danny-avila/LibreChat](https://github.com/danny-avila/LibreChat) | Danny Avila | 42k | 4 | Agent conversation-starters dropped from list projection, Bedrock MCP tool-description compat, Redis cluster-safe cache delete, artifacts capability gate |
| [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) | Google | 49k | 4 | Multi-file upload support, network/console pagination past page 0, page title in `list_pages`, respect user's npm registry in update check |
| [ax-llm/ax](https://github.com/ax-llm/ax) | Ax | 2.9k | 3 | Expose request body in error traces, per-item URL array validation, dedup streaming structured-output arrays |
| [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) | Promptfoo | 24k | 2 | Code-scan comment validation, extension-hook prompt preservation |
| [embeddings-benchmark/mteb](https://github.com/embeddings-benchmark/mteb) | MTEB Community | 3.4k | 2 | Fixed MRR / p-MRR ranking tie-breaks to match the `pytrec_eval` reference implementation across two related retrieval metrics |
| [Nano-Collective/nanocoder](https://github.com/Nano-Collective/nanocoder) | Nano Collective | 2.4k | 2 | Stopped MCP server reporting "connected" after failed tool discovery (leaked process), blocked IPv6-loopback bypass in the `fetch_url` SSRF guard |
| [CopilotKit/CopilotKit](https://github.com/CopilotKit/CopilotKit) | CopilotKit | 37k | 2 | Re-landed dropped run-started event bridge for the Web Inspector, forward core headers on owned thread-store requests |
| [ComposioHQ/composio](https://github.com/ComposioHQ/composio) | Composio | 30k | 2 | Nullable/relaxed output schema for third-party API nulls, resolve `$ref`/`$defs` so file flags survive schema dereferencing |
| [rowboatlabs/rowboat](https://github.com/rowboatlabs/rowboat) | RowBoat Labs | 17k | 1 | Forward configured headers to remote MCP transports |
| [plastic-labs/honcho](https://github.com/plastic-labs/honcho) | Plastic Labs | 6.7k | 1 | Honor the `DERIVER_DEDUPLICATE` setting in `create_observations` (silently ignored) |
| [sashabaranov/go-openai](https://github.com/sashabaranov/go-openai) | Alex Baranov | 10.7k | 1 | Added `ChunkingStrategy` support to `AudioRequest` for diarization models |
| [openai/openai-node](https://github.com/openai/openai-node) | OpenAI | 11k | 1 | Preserve Azure model-to-deployment mapping for `images.edit` |
| [MinishLab/model2vec](https://github.com/MinishLab/model2vec) | Minish | 2.2k | 1 | Export classifier/regressor pipelines to ONNX |
| [labring/FastGPT](https://github.com/labring/FastGPT) | Labring (Sealos) | 29k | 1 | MCP transport: fall back to legacy SSE only on 4xx errors |
| [rohitg00/agentmemory](https://github.com/rohitg00/agentmemory) | Rohit Ghumare | 27k | 1 | Memory recall format & endpoint fix |
| [alpic-ai/skybridge](https://github.com/alpic-ai/skybridge) | Alpic | 2.0k | 1 | CSS asset URL transform skip |
| [dyad-sh/dyad](https://github.com/dyad-sh/dyad) | Dyad | 21k | 1 | LM Studio model listing dropped vision-capable models |

---

### 🌐 Web3 Background

Earlier projects before shifting focus to AI systems:

- Built apps interacting with **Solana blockchain** (Web3.js, RPC, transactions)
- DEX integrations: Raydium, Orca, Meteora, Phoenix, Openbook, Lifinity
- On-chain arbitrage bot with **Jito MEV bundle submission** and 3-hop route discovery
- Real-time wallet & transaction monitoring with Telegram alerts

---

### 📊 Activity

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=serhiizghama&theme=react-dark&hide_border=true&area=true)](https://github.com/Ashutosh00710/github-readme-activity-graph)

---

### 🔗 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/serhiizghama)
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/serhiizghama)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/serhiizghama)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:serhii.zghama@gmail.com)

---

### ⚒️ Languages & Tools

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-e0234e?style=for-the-badge&logo=nestjs&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

![Profile views](https://komarev.com/ghpvc/?username=serhiizghama&label=Profile%20views&color=0e75b6&style=flat)
