### Hi, I'm Victor 👋

**MLOps & AI engineer** from Brazil. 5+ years taking data to production: ETL, databases and
data lakes first, then ML models, and now LLM agents. I care about the parts that make AI
reliable in production: evaluation gates, observability, guardrails and deploys you can roll back.

Currently doing a postgrad in ML in Production. Site: **[vgmelo.tech](https://vgmelo.tech)**

---

#### 🔭 Open source

| Project | What it is |
| --- | --- |
| [**agent-orchestrator**](https://github.com/vicgamelo/agent-orchestrator) | Multi-agent API: supervisor/worker delegation, parallel tool calls, MCP tools, guardrails and tracing. Runs on Claude or local models. |
| [**mcp-server-brasil**](https://github.com/vicgamelo/mcp-server-brasil) | MCP server with Brazilian public data for agents: CEP, CNPJ (alphanumeric too), holidays, business days, Banco Central, IBGE. Live at `mcp.vgmelo.tech/mcp`. |
| [**genai-lens**](https://github.com/vicgamelo/genai-lens) | Self-hosted LLM observability: traces, tokens, cost and latency per model, OpenTelemetry GenAI endpoint, PII redaction. |
| [**mlops-platform**](https://github.com/vicgamelo/mlops-platform) | MLflow end to end for credit risk: lineage, gated champion/challenger promotion with a fairness check, drift (PSI), hot-swapping model serving. |
| [**ml-from-scratch**](https://github.com/vicgamelo/ml-from-scratch) | Classic ML and attention in pure NumPy, every algorithm verified against scikit-learn. |
| [**vps-infra**](https://github.com/vicgamelo/vps-infra) | How all of the above runs on one VPS: Caddy, Docker Compose, hardening, backups. |

They're meant to work together: the agents call **mcp-server-brasil** over MCP, every run is
traced in **genai-lens**, and **mlops-platform** serves the model that **vps-infra** deploys.

#### 🧰 Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?logo=mlflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langchain&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude-D97757?logo=anthropic&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?logo=opentelemetry&logoColor=white)

#### 📫 Find me

[vgmelo.tech](https://vgmelo.tech) · [GitHub](https://github.com/vicgamelo)
