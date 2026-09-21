# Hey, I'm Serhii 👋

**Backend / Platform Engineer — LLM systems in production**

> 🌍 Open to remote roles: AI Platform · Agent Infrastructure · LLM Systems · Backend (AI)

---

- **Stack:** TypeScript · Python · Go · Node.js / NestJS · PostgreSQL · Redis · Kafka · gRPC · AWS
- 6+ years of backend in **fintech** and **life sciences** — event-driven microservices, streaming data pipelines, AWS serverless
- Now building the layer around LLMs: **routing · tools / MCP · memory & state · evals · observability · orchestration · serving & cost**
- Open-source contributor — **93 merged PRs** across 30 repos, repeat contributor in 18, including upstreams maintained by **OpenAI** and **Google**

---

### 🛠 Systems I build

| Project | What it is | Layer |
|---|---|---|
| **[warren](https://github.com/serhiizghama/warren)** | Self-hosted network of always-on Claude Code agents: an orchestrator routes work to domain agents, they talk over a file-based message bus, run on cron/launchd and are reachable from a phone. Runs on a subscription, not the metered API | orchestration · state · ops |
| **[gamma-runtime](https://github.com/serhiizghama/gamma-runtime)** | Local-first multi-agent platform: NestJS microkernel, Redis Streams as the event bus, SSE / WebSocket streaming to the browser (MSc thesis) | orchestration · serving |
| **[monobank-mcp](https://github.com/serhiizghama/monobank-mcp)** · **[liqpay-mcp](https://github.com/serhiizghama/liqpay-mcp)** · **[viber-mcp](https://github.com/serhiizghama/viber-mcp)** | MCP servers for banking, payments and messaging APIs — `monobank-mcp` is published on npm | tools / MCP |
| **[ai-agent-auth](https://github.com/serhiizghama/ai-agent-auth)** | Cryptographic authentication protocol for autonomous agents: DIDs + Ed25519 challenge signing, replay protection, revocation, ~1.2 ms sign + verify | agent identity |
| **[futures-engine](https://github.com/serhiizghama/futures-engine)** | Event-driven position processing: Kafka between services, Redis on the hot path, PostgreSQL as the source of truth | backend foundation |
| Voice delivery pipeline | Text-to-speech track with retry layers, fallback voices and a re-synthesis queue, delivered through Telegram bots (private) | serving · resilience |

---

### 🤝 Open-Source Contributions

Contributor across LLM-infrastructure repos — sorted by merge depth, not just stars. Started with TypeScript agent frameworks, now equally active in Python and Go: MCP SDKs and servers, embeddings and retrieval, LLM API clients, vector-search benchmarks, agent memory, eval tooling.

| Project | Company / Author | ⭐ | Merged |
|---|---|---|---|
| [yamadashy/repomix](https://github.com/yamadashy/repomix) | Kazuki Yamada | 28k | 13 |
| [assistant-ui/assistant-ui](https://github.com/assistant-ui/assistant-ui) | Assistant-UI | 12k | 9 |
| [mastra-ai/mastra](https://github.com/mastra-ai/mastra) | Mastra | 28k | 6 |
| [theopenco/llmgateway](https://github.com/theopenco/llmgateway) | LLM Gateway | 1.6k | 6 |
| [MinishLab/model2vec](https://github.com/MinishLab/model2vec) | Minish Lab | 2.2k | 6 |
| [neuml/txtai](https://github.com/neuml/txtai) | NeuML | 13k | 5 |
| [datalayer/jupyter-mcp-server](https://github.com/datalayer/jupyter-mcp-server) | Datalayer | 1.3k | 5 |
| [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) | Google | 52k | 4 |
| [danny-avila/LibreChat](https://github.com/danny-avila/LibreChat) | Danny Avila | 44k | 4 |
| [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) | Mark3Labs | 9.1k | 4 |
| [ax-llm/ax](https://github.com/ax-llm/ax) | Ax | 2.9k | 3 |
| [embeddings-benchmark/mteb](https://github.com/embeddings-benchmark/mteb) | MTEB Community | 3.4k | 3 |
| [sashabaranov/go-openai](https://github.com/sashabaranov/go-openai) | Alex Baranov | 10.8k | 3 |
| [CopilotKit/CopilotKit](https://github.com/CopilotKit/CopilotKit) | CopilotKit | 37k | 2 |
| [ComposioHQ/composio](https://github.com/ComposioHQ/composio) | Composio | 30k | 2 |
| [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) | Promptfoo | 25k | 2 |
| [plastic-labs/honcho](https://github.com/plastic-labs/honcho) | Plastic Labs | 7.2k | 2 |
| [Nano-Collective/nanocoder](https://github.com/Nano-Collective/nanocoder) | Nano Collective | 2.5k | 2 |
| [labring/FastGPT](https://github.com/labring/FastGPT) | Labring (Sealos) | 30k | 1 |
| [rohitg00/agentmemory](https://github.com/rohitg00/agentmemory) | Rohit Ghumare | 28k | 1 |
| [dyad-sh/dyad](https://github.com/dyad-sh/dyad) | Dyad | 22k | 1 |
| [rowboatlabs/rowboat](https://github.com/rowboatlabs/rowboat) | RowBoat Labs | 18k | 1 |
| [openai/openai-node](https://github.com/openai/openai-node) | OpenAI | 11k | 1 |
| [thrasher-corp/gocryptotrader](https://github.com/thrasher-corp/gocryptotrader) | Thrasher Corp | 3.5k | 1 |
| [alpic-ai/skybridge](https://github.com/alpic-ai/skybridge) | Alpic | 2.0k | 1 |
| [zilliztech/VectorDBBench](https://github.com/zilliztech/VectorDBBench) | Zilliz | 1.2k | 1 |
| [provos/ironcurtain](https://github.com/provos/ironcurtain) | Niels Provos | 0.6k | 1 |

---

### 💼 Background

**PaidPex** (2025 – now) — backend for a trading platform: real-time market data over WebSockets, a price-aggregation pipeline (workers → gRPC → gateway → Kafka), Redis-based leader election, PostgreSQL.

**EDETEK** (2019 – 2025) — clinical data management platform for life sciences: event-driven pipelines on AWS Lambda / SQS / S3, large-scale stream processing of CSV / XML / JSON with distributed locks, shared libraries across Nx / Lerna monorepos.

---

### 🔗 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/serhiizghama)
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/serhiizghama)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/serhiizghama)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:serhii.zghama@gmail.com)

---

![Profile views](https://komarev.com/ghpvc/?username=serhiizghama&label=Profile%20views&color=0e75b6&style=flat)
