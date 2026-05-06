# Hi, I'm Mike Abernathy

Full-stack engineer based in the U.S. — Azure cloud, modern frontend, AI tooling, and the IaC + pipeline plumbing that makes it all reproducible.

## Featured project — PCPC: one product, three architectures

**[Abernaughty/PCPC](https://github.com/Abernaughty/PCPC)** is a Pokémon card price checker that's *intentionally* deployed three ways from one repo to demonstrate architectural range:

| Path | Stack | What it shows |
|---|---|---|
| **Vercel BFF** | SvelteKit 2 + Svelte 5 → SvelteKit `+server.ts` → Cosmos | Modern edge / SSR / BFF |
| **APIM + Functions** | API Management → Azure Functions v4 → Cosmos / Redis | Enterprise IaC, gateway expertise, ADO pipelines |
| **ACA Container** | Same Functions image → Azure Container Apps + KEDA | Container fluency, FedRAMP-friendly deployment |

One frontend, three switchable backends, one shared schema via [`@pcpc/shared`](https://github.com/Abernaughty/PCPC/tree/main/backend/shared). The architectural reasoning lives in [ADRs](https://github.com/Abernaughty/PCPC/tree/main/docs/adr) and a [comparison document](https://github.com/Abernaughty/PCPC/blob/main/docs/architecture-comparison.md).

Plan, phasing, and risk model: [`docs/PORTFOLIO_PLAN.md`](https://github.com/Abernaughty/PCPC/blob/main/docs/PORTFOLIO_PLAN.md).

## Other active work

- **[maber-web](https://github.com/Abernaughty/maber-web)** — pnpm + Turbo monorepo of personal SvelteKit apps (landing, blackjack, portfolio) on Vercel.
- **[agent-dev](https://github.com/Abernaughty/agent-dev)** — containerized AI agent dev environment with Docker + MCP servers.
- **[code-vector-sync](https://github.com/Abernaughty/code-vector-sync)** — MCP server for semantic code search using Qdrant vector embeddings.
- **[langchain-price-agent](https://github.com/Abernaughty/langchain-price-agent)** — LangChain/LangGraph agent experiments for card pricing.
- **[maber.io](https://github.com/Abernaughty/maber.io)** — personal site with a real-time WebGL fluid simulation background.

## Tech I work with

**Cloud & runtime** · Azure (Functions, APIM, Container Apps, Cosmos DB, Key Vault, Application Insights) · Docker · KEDA · Redis
**IaC & pipelines** · Terraform (multi-module) · Azure DevOps · GitHub Actions · ACR-backed CI containers
**Frontend** · SvelteKit · Svelte 5 runes · Tailwind v4 · Vercel · TypeScript
**Backend & data** · Node.js (Functions v4) · Python · Cosmos DB · Redis
**AI tooling** · MCP servers · LangChain / LangGraph · Qdrant vector search

## Connect

- 💼 [LinkedIn](https://linkedin.com/in/michael-abernathy-674a96217)
- 📅 [cal.com/mike-abernathy](https://cal.com/mike-abernathy)
- ✉️ [mike@maber.io](mailto:mike@maber.io)
- 📄 [Resume](https://maberstorageacct.blob.core.windows.net/resume/Michael%20Abernathy%20-%20Resume.pdf)
