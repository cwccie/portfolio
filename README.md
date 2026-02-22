# Portfolio — Corey Wade

> **25 years enterprise infrastructure x AI/ML PhD candidate**
> CCIE #14124 | CISSP | SOFAM Researcher

A structured portfolio of AI+Infrastructure projects spanning network operations, cybersecurity, and machine learning engineering. Each project ships with documentation, tests, Docker support, and CI/CD.

---

## Flagship Platforms

Production-grade systems that anchor the portfolio narrative.

| Project | Description | Tech Stack |
|---------|-------------|------------|
| [NetOpsHub](https://github.com/cwccie/netopshub) | AI-native network operations platform. Multi-agent troubleshooting, RAG over vendor docs, anomaly detection, compliance. netopshub.com | LangGraph, MCP, Qdrant, React, Docker |
| SOFAM-Net | Federated learning for cross-org threat detection without data sharing | Flower, PyG, Differential Privacy |
| SentinelForge | Autonomous SOC analyst — alert triage, ATT&CK mapping, playbook execution | LangGraph, MITRE ATT&CK, OCSF |
| NetGraph | GNN-based network topology intelligence and failure prediction | PyTorch Geometric, NetworkX, Grafana |
| InfraWatch | Time series foundation model for infrastructure anomaly detection | Chronos-Bolt, TimesFM, Prometheus |
| ConfigGuard | AI-driven network configuration compliance (NIST, CIS, PCI-DSS) | Batfish, RAG, Constrained Generation |
| AgentOps | Multi-agent infrastructure remediation with A2A protocol | A2A, MCP, OpenTelemetry |
| ZeroTrust-AI | AI-accelerated zero trust architecture with behavioral analytics | GNN, Flow Analysis, Risk Scoring |

## Libraries

Pip-installable Python packages consumed by tools and flagships.

| Library | What It Does |
|---------|-------------|
| netparse | Cisco IOS/JunOS/Arista EOS config parsing to structured JSON/YAML |
| ciscoparser | High-performance Cisco show command parser |
| slogparse | Security log parser: CEF, LEEF, syslog, Windows Events to OCSF |
| graphtopo | Network topology graph builder from SNMP/LLDP/CDP |
| flowgraph | NetFlow/sFlow to PyTorch Geometric graph objects |
| netembeddings | Pre-computed embeddings for networking concepts |
| netner | NER for network text: IPs, CVEs, hostnames, ASNs, ATT&CK IDs |
| ragchunk | Chunking for technical docs: code blocks, CLI output, configs |
| configeval | Evaluation framework for LLM-generated network configs |
| guardrails-infra | NeMo Guardrails for infrastructure AI safety |
| mcpnet | MCP server exposing Nornir/NAPALM device interactions |
| anomalyts | Anomaly detection for infrastructure time series |
| inframetrics | Time series preprocessing: counter wraps, seasonal decomp |
| otelai | OpenTelemetry instrumentation for AI/ML pipelines |
| fedthreat | Federated learning utilities for distributed threat detection |
| attackgraph | Attack graph construction with MITRE ATT&CK + GNN scoring |
| privacynet | Privacy-preserving network telemetry |
| ttp-extract | MITRE ATT&CK TTP extraction via NER |
| intentlang | DSL for network intent to vendor-specific configs |
| netsynth | Synthetic network config generator for training data |
| netrl | Gymnasium RL environment for network optimization |
| quantnet | Network-specific model quantization benchmarks |

## Tools

Complete working solutions with Docker Compose deployment and demo modes.

| Tool | What It Does |
|------|-------------|
| netchat | RAG-powered network documentation assistant |
| threatmapper | CVE prioritization with ATT&CK mapping + asset context |
| logforge | Hybrid log parser: Drain3 + LLM |
| netdiff | AI-powered network change impact analyzer |
| flowsense | GNN-based NetFlow anomaly detector |
| policygen | Natural language to vendor-specific ACLs/firewall rules |
| secrag | GraphRAG over MITRE ATT&CK + NIST + CIS |
| infracost | AI workload cost optimizer for Kubernetes |
| alertcorrelator | Cross-domain event correlation |
| edgeinfer | On-prem LLM inference server (GGUF + ONNX) |
| configdrift | Real-time config drift detector |
| phishguard | AI-generated phishing detection |
| saseguard | AI-enhanced SASE policy analyzer |
| compliancebot | EU AI Act readiness assessment |
| audittrail | AI system governance logger |
| topologyviz | Network diagram to structured data converter |
| incidentnarrator | AI incident report generator |
| netsynth-full | Full synthetic network data generator |

## Research

Jupyter notebooks validating techniques before flagships productionize them.

| Notebook | Technique | Validates |
|----------|-----------|-----------|
| tsfm-infrastructure-bench | TSFM benchmarking on infra metrics | InfraWatch |
| gnn-netflow-anomaly | GNN for NetFlow anomaly detection | FlowSense, NetGraph |
| federated-ids-benchmark | FL for IDS with differential privacy | SOFAM-Net |
| causal-rca-infrastructure | Causal inference for root cause analysis | NetDiff, AgentOps |
| graphrag-network-knowledge | GraphRAG vs standard RAG on network knowledge | NetOpsHub |
| offline-rl-network-optimization | Offline RL for traffic engineering | AgentOps |
| small-model-big-infra | SLMs on infrastructure NLP tasks | EdgeInfer |
| test-time-compute-infrastructure | Test-time compute scaling | InfraWatch |
| reasoning-models-infrastructure | Reasoning models on infra troubleshooting | NetOpsHub |
| deepfake-phishing-detection | AI-generated phishing detection | PhishGuard |
| neurosymbolic-network-rca | Neural + symbolic RCA | AgentOps |
| fl-qlora-collaborative-training | Federated QLoRA training | SOFAM-Net |
| multimodal-infra-diagnosis | Multi-modal infrastructure diagnosis | Flagships |
| continual-learning-security | Continual learning for CVE models | ThreatMapper |

## Templates

Opinionated reference architectures with Docker Compose deployment.

| Template | Architecture |
|----------|-------------|
| template-llm-network-agent | LangGraph agent + MCP + Nornir + RAG + guardrails |
| template-rag-enterprise | Production RAG: hybrid search + Qdrant + RAGAS eval |
| template-federated-ml | Flower FL: client/server + DP + secure aggregation |
| template-mlops-infrastructure | MLOps: Prometheus to MLflow to KServe |
| template-gnn-security | GNN for network security: PyG + TGN + Grafana |
| template-edge-inference | Edge AI: GGUF + ONNX Runtime + FastAPI |
| template-ai-governance | AI governance: model registry + compliance |
| template-soc-automation | SOC: alert triage + ATT&CK + playbooks |
| template-multi-agent-ops | Multi-agent: A2A protocol + Agent Cards |
| template-network-digital-twin | Network digital twin: topology + simulation |
| template-iac-ai-pipeline | AI-enhanced IaC: Terraform/Ansible gen + Checkov |
| template-observability-ai | AI-native observability: OTel + NL querying |

## Hugging Face Models

| Model | Base | Training Data | Purpose |
|-------|------|---------------|---------|
| NetOps-7B | Qwen 2.5 7B | 15-30K network operations examples | Network config generation, troubleshooting, explanation |
| CVE-Analyst-7B | Qwen 2.5 7B | 50-80K CVE/security examples | Vulnerability triage, ATT&CK mapping, remediation |

---

## Tech Stack

**AI/ML:** PyTorch, PyTorch Geometric, LangGraph, Flower, Unsloth, ONNX Runtime, llama.cpp
**Infrastructure:** Docker, Kubernetes, Terraform, Ansible, Prometheus, Grafana, InfluxDB
**Network:** Nornir, NAPALM, Netmiko, Batfish, TextFSM, SNMP, NetFlow, syslog
**Security:** MITRE ATT&CK, OCSF, NeMo Guardrails, OpenDP, SHAP/LIME
**Protocols:** MCP, A2A, OpenTelemetry, gRPC, REST
**Data:** Qdrant, FAISS, PostgreSQL, Redis, Pandas, NetworkX

---

*Built by Corey Wade — transforming 25 years of enterprise infrastructure experience into AI-native operations.*
