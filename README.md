### Darshan Kumar Satpathy

AI & Data Solutions Architect in Bhubaneswar, India. I architect enterprise AI that makes it to production: multi-agent platforms, governed data agents, bank risk models, streaming and lakehouse platforms. Portfolio: **[darshansatpathy.github.io](https://darshansatpathy.github.io)** · [LinkedIn](https://www.linkedin.com/in/darshansatpathy)

Open to Lead and Principal AI Architect roles, including international and remote-first teams.

The repositories below are open-source reference implementations of patterns from my production work. They run on synthetic or public data, are tested in CI and each one measures the failure it is built to prevent.

#### Enterprise architecture, cloud and governance
| Repository | What it proves |
|---|---|
| [azure-ai-landing-zone](https://github.com/darshansatpathy/azure-ai-landing-zone) | Private, keyless Azure OpenAI in Terraform, with a policy-as-code checker that fails the build if a door is reopened |
| [ai-platform-reference-architecture](https://github.com/darshansatpathy/ai-platform-reference-architecture) | A 27-component AI platform written as data; `archfit` fails the build when the design contradicts itself |
| [ai-governance-evidence-pack](https://github.com/darshansatpathy/ai-governance-evidence-pack) | 41 EU AI Act, NIST AI RMF and ISO 42001 controls mapped to hash-pinned evidence, with gaps stated openly |
| [databricks-medallion-lakehouse](https://github.com/darshansatpathy/databricks-medallion-lakehouse) | Each table is a spec; Lakeflow SQL, Unity Catalog governance and a bundle are generated and linted (not yet run on Databricks) |
| [claude-agent-reference](https://github.com/darshansatpathy/claude-agent-reference) | A production agent loop on the Claude API in about 2,000 readable lines, zero runtime dependencies |

#### Delivery governance for AI systems
| Repository | What it proves |
|---|---|
| [ai-design-review-kit](https://github.com/darshansatpathy/ai-design-review-kit) | An AI architecture review as files: questions, evidence, accepted risks and a verdict CI can enforce |
| [ai-threat-model-as-code](https://github.com/darshansatpathy/ai-threat-model-as-code) | Threats derived from the data-flow graph and mapped to OWASP LLM Top 10 and MITRE ATLAS ids; ready, conditional or blocked |
| [model-promotion-gates](https://github.com/darshansatpathy/model-promotion-gates) | 23 evidence-bound gates on model stage transitions, with approvals tied to the exact artefact digest and expiring waivers |
| [data-contracts-registry](https://github.com/darshansatpathy/data-contracts-registry) | Data contracts as reviewed code; a change that would break a consumer fails the build |
| [ai-finops-showback](https://github.com/darshansatpathy/ai-finops-showback) | AI spend by team and app from usage exports, shared costs allocated by explicit rule, totals that agree to the cent |

#### Agent platform and safety
| Repository | What it proves |
|---|---|
| [agent-guardrails-gateway](https://github.com/darshansatpathy/agent-guardrails-gateway) | Policy enforcement between agents and tools; 23 of 23 attack scenarios contained |
| [multi-agent-ops-automation](https://github.com/darshansatpathy/multi-agent-ops-automation) | Supervisor and worker agents behind a deterministic executor with idempotency and approvals |
| [human-in-the-loop-inbox](https://github.com/darshansatpathy/human-in-the-loop-inbox) | Approvals bound to exact arguments; single-use grants |
| [no-code-agent-studio](https://github.com/darshansatpathy/no-code-agent-studio) | Agents as YAML, released dev to prod with test gates and risk review |
| [mcp-server-toolkit](https://github.com/darshansatpathy/mcp-server-toolkit) | Production template for MCP servers: OAuth, scopes, tenancy, audit |

#### Grounded and governed AI
| Repository | What it proves |
|---|---|
| [governed-data-agents](https://github.com/darshansatpathy/governed-data-agents) | Business questions answered without the model writing SQL; row-level security |
| [agentic-rag-reference](https://github.com/darshansatpathy/agentic-rag-reference) | Permission-aware, cited RAG that abstains when it should |
| [agent-memory-service](https://github.com/darshansatpathy/agent-memory-service) | Agent memory with supersession, PII refusal and tenant isolation |

#### LLMOps
| Repository | What it proves |
|---|---|
| [agent-eval-harness](https://github.com/darshansatpathy/agent-eval-harness) | CI gate that blocks pull requests that make an agent worse |
| [agent-tracing-otel](https://github.com/darshansatpathy/agent-tracing-otel) | OpenTelemetry tracing built around cost per completed task |
| [llm-router-cost-telemetry](https://github.com/darshansatpathy/llm-router-cost-telemetry) | OpenAI-compatible router; evaluated on real graded traffic |

#### Data, ML and platform engineering
| Repository | What it proves |
|---|---|
| [realtime-transaction-streaming](https://github.com/darshansatpathy/realtime-transaction-streaming) | Exactly-once Kafka processing, proven by killing processes mid-flight |
| [lakehouse-iceberg-trino](https://github.com/darshansatpathy/lakehouse-iceberg-trino) | Open lakehouse with every table checked against an independent answer |
| [snowflake-migration-toolkit](https://github.com/darshansatpathy/snowflake-migration-toolkit) | Teradata and Oracle to Snowflake: translation and row-level validation |
| [integration-migration-factory](https://github.com/darshansatpathy/integration-migration-factory) | ESB to Kafka migration with record-by-record regression |
| [ha-model-inference-platform](https://github.com/darshansatpathy/ha-model-inference-platform) | Canary releases, SLO burn-rate alerts and zero-drop failover on Kubernetes |
| [db-incident-remediation-agents](https://github.com/darshansatpathy/db-incident-remediation-agents) | Prometheus alert to verified PostgreSQL fix, with a policy governor |
| [credit-risk-ml-platform](https://github.com/darshansatpathy/credit-risk-ml-platform) | Probability-of-default models with model-risk checks and validation report |
| [demand-forecasting-platform](https://github.com/darshansatpathy/demand-forecasting-platform) | Coherent hierarchical forecasts gated by backtests |
| [lidar-gnn-digital-twin](https://github.com/darshansatpathy/lidar-gnn-digital-twin) | Graph neural network segmentation and change detection on LiDAR scans |
