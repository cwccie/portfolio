# Portfolio — Corey Wade

> **25 years enterprise infrastructure x AI/ML PhD candidate**
> CCIE #14124 | CISSP | SOFAM Researcher

A structured portfolio of **76+ AI+Infrastructure projects** spanning network operations, cybersecurity, and machine learning engineering. Each project ships with documentation, tests, Docker support, and CI/CD.

**[netopshub.com](https://netopshub.com)** — AI-native network operations platform (flagship)

---

## Portfolio at a Glance

| Category | Count | Description |
|----------|-------|-------------|
| Flagship Platforms | 8 | Production-grade systems anchoring the portfolio |
| Substantial Tools | 18 | Working solutions with Docker Compose deployment |
| Foundation Libraries | 22 | Pip-installable Python packages |
| Research Notebooks | 14 | Jupyter notebooks validating techniques |
| Architecture Templates | 12 | Opinionated reference architectures |
| Hugging Face Models | 2 | Fine-tuned LLMs for network ops and security |
| **Total** | **76+** | |

---

## Flagship Platforms

Production-grade systems that anchor the portfolio narrative.

| Project | Description | Tech Stack |
|---------|-------------|------------|
| [NetOpsHub](https://github.com/cwccie/netopshub) | AI-native network operations platform. Multi-agent troubleshooting, RAG over vendor docs, anomaly detection, compliance. [netopshub.com](https://netopshub.com) | FastAPI, React, LangGraph, MCP, Qdrant, Docker |
| [SOFAM-Net](https://github.com/cwccie/sofam-net) | Federated learning for cross-org threat detection without data sharing | Flower, PyG, Differential Privacy |
| [SentinelForge](https://github.com/cwccie/sentinelforge) | Autonomous SOC analyst — alert triage, ATT&CK mapping, playbook execution | LangGraph, MITRE ATT&CK, OCSF |
| [NetGraph](https://github.com/cwccie/netgraph) | GNN-based network topology intelligence and failure prediction | PyTorch Geometric, NetworkX, Grafana |
| [InfraWatch](https://github.com/cwccie/infrawatch) | Time series foundation model for infrastructure anomaly detection | Chronos-Bolt, TimesFM, Prometheus |
| [ConfigGuard](https://github.com/cwccie/configguard) | AI-driven network configuration compliance (NIST, CIS, PCI-DSS) | Batfish, RAG, Constrained Generation |
| [AgentOps](https://github.com/cwccie/agentops) | Multi-agent infrastructure remediation with A2A protocol | A2A, MCP, OpenTelemetry |
| [ZeroTrust-AI](https://github.com/cwccie/zerotrust-ai) | AI-accelerated zero trust architecture with behavioral analytics | GNN, Flow Analysis, Risk Scoring |

---

## Libraries

Pip-installable Python packages consumed by tools and flagships.

| Library | What It Does |
|---------|-------------|
| [netparse](https://github.com/cwccie/netparse) | Cisco IOS/JunOS/Arista EOS config parsing to structured JSON/YAML |
| [ciscoparser](https://github.com/cwccie/ciscoparser) | High-performance Cisco show command parser |
| [slogparse](https://github.com/cwccie/slogparse) | Security log parser: CEF, LEEF, syslog, Windows Events to OCSF |
| [graphtopo](https://github.com/cwccie/graphtopo) | Network topology graph builder from SNMP/LLDP/CDP |
| [flowgraph](https://github.com/cwccie/flowgraph) | NetFlow/sFlow to PyTorch Geometric graph objects |
| [netembeddings](https://github.com/cwccie/netembeddings) | Pre-computed embeddings for networking concepts |
| [netner](https://github.com/cwccie/netner) | NER for network text: IPs, CVEs, hostnames, ASNs, ATT&CK IDs |
| [ragchunk](https://github.com/cwccie/ragchunk) | Chunking for technical docs: code blocks, CLI output, configs |
| [configeval](https://github.com/cwccie/configeval) | Evaluation framework for LLM-generated network configs |
| [guardrails-infra](https://github.com/cwccie/guardrails-infra) | NeMo Guardrails for infrastructure AI safety |
| [mcpnet](https://github.com/cwccie/mcpnet) | MCP server exposing Nornir/NAPALM device interactions |
| [anomalyts](https://github.com/cwccie/anomalyts) | Anomaly detection for infrastructure time series |
| [inframetrics](https://github.com/cwccie/inframetrics) | Time series preprocessing: counter wraps, seasonal decomp |
| [otelai](https://github.com/cwccie/otelai) | OpenTelemetry instrumentation for AI/ML pipelines |
| [fedthreat](https://github.com/cwccie/fedthreat) | Federated learning utilities for distributed threat detection |
| [attackgraph](https://github.com/cwccie/attackgraph) | Attack graph construction with MITRE ATT&CK + GNN scoring |
| [privacynet](https://github.com/cwccie/privacynet) | Privacy-preserving network telemetry |
| [ttp-extract](https://github.com/cwccie/ttp-extract) | MITRE ATT&CK TTP extraction via NER |
| [intentlang](https://github.com/cwccie/intentlang) | DSL for network intent to vendor-specific configs |
| [netsynth](https://github.com/cwccie/netsynth) | Synthetic network config generator for training data |
| [netrl](https://github.com/cwccie/netrl) | Gymnasium RL environment for network optimization |
| [quantnet](https://github.com/cwccie/quantnet) | Network-specific model quantization benchmarks |

---

## Tools

Complete working solutions with Docker Compose deployment and demo modes.

| Tool | What It Does |
|------|-------------|
| [netchat](https://github.com/cwccie/netchat) | RAG-powered network documentation assistant |
| [threatmapper](https://github.com/cwccie/threatmapper) | CVE prioritization with ATT&CK mapping + asset context |
| [logforge](https://github.com/cwccie/logforge) | Hybrid log parser: Drain3 + LLM |
| [netdiff](https://github.com/cwccie/netdiff) | AI-powered network change impact analyzer |
| [flowsense](https://github.com/cwccie/flowsense) | GNN-based NetFlow anomaly detector |
| [policygen](https://github.com/cwccie/policygen) | Natural language to vendor-specific ACLs/firewall rules |
| [secrag](https://github.com/cwccie/secrag) | GraphRAG over MITRE ATT&CK + NIST + CIS |
| [infracost](https://github.com/cwccie/infracost) | AI workload cost optimizer for Kubernetes |
| [alertcorrelator](https://github.com/cwccie/alertcorrelator) | Cross-domain event correlation |
| [edgeinfer](https://github.com/cwccie/edgeinfer) | On-prem LLM inference server (GGUF + ONNX) |
| [configdrift](https://github.com/cwccie/configdrift) | Real-time config drift detector |
| [phishguard](https://github.com/cwccie/phishguard) | AI-generated phishing detection |
| [saseguard](https://github.com/cwccie/saseguard) | AI-enhanced SASE policy analyzer |
| [compliancebot](https://github.com/cwccie/compliancebot) | EU AI Act readiness assessment |
| [audittrail](https://github.com/cwccie/audittrail) | AI system governance logger |
| [topologyviz](https://github.com/cwccie/topologyviz) | Network diagram to structured data converter |
| [incidentnarrator](https://github.com/cwccie/incidentnarrator) | AI incident report generator |
| [netsynth-full](https://github.com/cwccie/netsynth-full) | Full synthetic network data generator |

---

## Research

Jupyter notebooks validating techniques before flagships productionize them.

| Notebook | Technique | Validates |
|----------|-----------|-----------|
| [tsfm-infrastructure-bench](https://github.com/cwccie/tsfm-infrastructure-bench) | TSFM benchmarking on infra metrics | InfraWatch |
| [gnn-netflow-anomaly](https://github.com/cwccie/gnn-netflow-anomaly) | GNN for NetFlow anomaly detection | FlowSense, NetGraph |
| [federated-ids-benchmark](https://github.com/cwccie/federated-ids-benchmark) | FL for IDS with differential privacy | SOFAM-Net |
| [causal-rca-infrastructure](https://github.com/cwccie/causal-rca-infrastructure) | Causal inference for root cause analysis | NetDiff, AgentOps |
| [graphrag-network-knowledge](https://github.com/cwccie/graphrag-network-knowledge) | GraphRAG vs standard RAG on network knowledge | NetOpsHub |
| [offline-rl-network-optimization](https://github.com/cwccie/offline-rl-network-optimization) | Offline RL for traffic engineering | AgentOps |
| [small-model-big-infra](https://github.com/cwccie/small-model-big-infra) | SLMs on infrastructure NLP tasks | EdgeInfer |
| [test-time-compute-infrastructure](https://github.com/cwccie/test-time-compute-infrastructure) | Test-time compute scaling | InfraWatch |
| [reasoning-models-infrastructure](https://github.com/cwccie/reasoning-models-infrastructure) | Reasoning models on infra troubleshooting | NetOpsHub |
| [deepfake-phishing-detection](https://github.com/cwccie/deepfake-phishing-detection) | AI-generated phishing detection | PhishGuard |
| [neurosymbolic-network-rca](https://github.com/cwccie/neurosymbolic-network-rca) | Neural + symbolic RCA | AgentOps |
| [fl-qlora-collaborative-training](https://github.com/cwccie/fl-qlora-collaborative-training) | Federated QLoRA training | SOFAM-Net |
| [multimodal-infra-diagnosis](https://github.com/cwccie/multimodal-infra-diagnosis) | Multi-modal infrastructure diagnosis | Flagships |
| [continual-learning-security](https://github.com/cwccie/continual-learning-security) | Continual learning for CVE models | ThreatMapper |

---

## Templates

Opinionated reference architectures with Docker Compose deployment.

| Template | Architecture |
|----------|-------------|
| [template-llm-network-agent](https://github.com/cwccie/template-llm-network-agent) | LangGraph agent + MCP + Nornir + RAG + guardrails |
| [template-rag-enterprise](https://github.com/cwccie/template-rag-enterprise) | Production RAG: hybrid search + Qdrant + RAGAS eval |
| [template-federated-ml](https://github.com/cwccie/template-federated-ml) | Flower FL: client/server + DP + secure aggregation |
| [template-mlops-infrastructure](https://github.com/cwccie/template-mlops-infrastructure) | MLOps: Prometheus to MLflow to KServe |
| [template-gnn-security](https://github.com/cwccie/template-gnn-security) | GNN for network security: PyG + TGN + Grafana |
| [template-edge-inference](https://github.com/cwccie/template-edge-inference) | Edge AI: GGUF + ONNX Runtime + FastAPI |
| [template-ai-governance](https://github.com/cwccie/template-ai-governance) | AI governance: model registry + compliance |
| [template-soc-automation](https://github.com/cwccie/template-soc-automation) | SOC: alert triage + ATT&CK + playbooks |
| [template-multi-agent-ops](https://github.com/cwccie/template-multi-agent-ops) | Multi-agent: A2A protocol + Agent Cards |
| [template-network-digital-twin](https://github.com/cwccie/template-network-digital-twin) | Network digital twin: topology + simulation |
| [template-iac-ai-pipeline](https://github.com/cwccie/template-iac-ai-pipeline) | AI-enhanced IaC: Terraform/Ansible gen + Checkov |
| [template-observability-ai](https://github.com/cwccie/template-observability-ai) | AI-native observability: OTel + NL querying |

---

## Hugging Face Models

| Model | Base | Training Data | Purpose |
|-------|------|---------------|---------|
| [NetOps-7B](https://github.com/cwccie/netops-7b) | Qwen 2.5 7B | 15-30K network operations examples | Network config generation, troubleshooting, explanation |
| [CVE-Analyst-7B](https://github.com/cwccie/cve-analyst-7b) | Qwen 2.5 7B | 50-80K CVE/security examples | Vulnerability triage, ATT&CK mapping, remediation |

---

## Technology Radar

Technologies I'm investing in and why they matter for enterprise infrastructure.

### Adopt

| Technology | Why |
|-----------|-----|
| **LangGraph / Agentic AI** | Multi-step infrastructure reasoning requires stateful agent orchestration, not single-shot prompts |
| **GNN (PyTorch Geometric)** | Networks are graphs — GNNs are the natural representation for topology analysis, anomaly detection, and failure prediction |
| **MCP (Model Context Protocol)** | Standardized tool integration for LLM agents. MCP will become the USB-C of AI tooling |
| **RAG + Vector Search** | Enterprise network knowledge lives in vendor docs, runbooks, and tribal knowledge — RAG makes it queryable |
| **OpenTelemetry** | Observability standard for both infrastructure and AI pipelines. Unified telemetry across the stack |

### Trial

| Technology | Why |
|-----------|-----|
| **A2A (Agent-to-Agent Protocol)** | Multi-agent collaboration for complex infrastructure operations. Early but promising |
| **Time Series Foundation Models** | Chronos-Bolt and TimesFM show zero-shot anomaly detection is viable for infrastructure metrics |
| **Federated Learning** | Cross-org threat intelligence without sharing sensitive data — critical for enterprise adoption |
| **QLoRA Fine-tuning** | Domain-specific LLMs at 7B scale run on commodity hardware and outperform general 70B models on infra tasks |

### Assess

| Technology | Why |
|-----------|-----|
| **Neurosymbolic AI** | Combining neural anomaly detection with symbolic topology rules for explainable root cause analysis |
| **Offline RL** | Learning network optimization policies from historical data without risking production networks |
| **Causal Inference** | Moving beyond correlation to actual root cause identification in complex distributed systems |

---

## Tech Stack

**AI/ML:** PyTorch, PyTorch Geometric, LangGraph, Flower, Unsloth, ONNX Runtime, llama.cpp
**Infrastructure:** Docker, Kubernetes, Terraform, Ansible, Prometheus, Grafana, InfluxDB
**Network:** Nornir, NAPALM, Netmiko, Batfish, TextFSM, SNMP, NetFlow, syslog
**Security:** MITRE ATT&CK, OCSF, NeMo Guardrails, OpenDP, SHAP/LIME
**Protocols:** MCP, A2A, OpenTelemetry, gRPC, REST
**Data:** Qdrant, FAISS, PostgreSQL, Redis, Pandas, NetworkX
**Frontend:** React, TypeScript, Tailwind CSS, Recharts

---

## About

**Corey A. Wade** — PhD candidate (AI + Cybersecurity), CISSP, retired CCIE #14124

25 years of enterprise infrastructure experience (Cisco TAC, network architecture, security consulting) combined with current PhD research in AI-driven network defense. This portfolio demonstrates the ability to ship production-grade AI systems, not just prototype them.

### What I Bring

- **Domain depth:** CCIE-level network expertise + CISSP security knowledge + PhD-level ML research
- **Full-stack AI:** From training custom models (QLoRA, GNNs, FL) to deploying them (Docker, K8s, FastAPI)
- **Production mindset:** Every repo has tests, CI/CD, Docker support, and documentation
- **Research-to-product pipeline:** 14 research notebooks validate techniques that 8 flagship platforms productionize

### Contact

- **GitHub:** [cwccie](https://github.com/cwccie)
- **Domain:** [netopshub.com](https://netopshub.com)
- **PhD Research:** [SOFAM](https://github.com/cwccie/SOFAM) — Self-Optimizing Fuzzy-ARTMAP

---

*Built by Corey Wade — transforming 25 years of enterprise infrastructure experience into AI-native operations.*
