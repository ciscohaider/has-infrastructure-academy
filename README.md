# HAS Infrastructure Academy

> **A collection of high-fidelity, interactive explainers designed to simplify complex IT concepts.**
> Each module is a standalone interactive HTML file — no framework, no install, just open and learn.

---

## 📚 Explainer Library

| # | Topic | File | Description |
|---|-------|------|-------------|
| 01 | **AIOps** | `aiops-explainer-v2.html` | How AI transforms IT operations — anomaly detection, event correlation, auto-remediation, maturity model |
| 02 | **How AI Models Work** | `ai-model-explainer.html` | Neural networks, training, backpropagation, inference, tokenization, model types |
| 03 | **How LLMs Work** | `llm-explainer.html` | Transformer architecture, attention, tokenization, RLHF, model landscape |
| 04 | **AI Agents** | `ai-agent-explainer.html` | ReAct pattern, tool use, memory types, multi-agent architectures, live simulator |
| 05 | **Model Context Protocol (MCP)** | `mcp-explainer.html` | MCP architecture, primitives (Tools/Resources/Prompts), building MCP servers |
| 06 | **AI Hallucination** | `hallucination-explainer.html` | Why hallucination happens, six types, confidence problem, RAG grounding, mitigation |
| 07 | **How ACH Works** | `ach-explainer.html` | ACH network roles, transaction lifecycle, NACHA file format, return codes, Same Day ACH |
| 08 | **How Databases Work** | `database-explainer.html` | Storage engine, MVCC, SQL query planner, indexes, ACID, WAL, NoSQL types |
| 09 | **Red Hat OpenShift** | `openshift-explainer.html` | Kubernetes + OpenShift architecture, pods, operators, CI/CD pipelines, OC CLI lab |

---

## ✨ Features

- **Interactive** — every explainer has clickable diagrams, live simulators, and expandable deep-dives
- **No dependencies** — single HTML file per topic, opens in any browser
- **IT-professional depth** — covers internals, not just surface-level overviews
- **Live simulators** — run realistic scenarios and watch systems respond in real time
- **Code examples** — real YAML, Python, SQL, and architecture diagrams throughout
- **HAS branded** — consistent watermark across all modules

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/has-infrastructure-academy.git

# Open any explainer directly in your browser
open aiops-explainer-v2.html
```

No server required. No npm install. No build step. Just open the HTML file.

---

## 📖 How Each Explainer Is Structured

Every module follows the same pattern:

```
Hero Section          →  What the topic is and why it matters
Tabbed Navigation     →  8–9 deep-dive sections
Interactive Content   →  Clickable diagrams, live demos, code blocks
Simulator             →  Real-time scenario walkthrough
Reference Tables      →  Comparison tables, decision guides
```

---

## 🗂 Topics Covered Per Module

### AIOps
Data pipeline · ML algorithms (Isolation Forest, LSTM, DBSCAN, GNN) · Anomaly detection · Event correlation · Auto-remediation · Tooling landscape (Dynatrace, Datadog, ServiceNow, Splunk ITSI) · 5-level maturity model · Live incident simulator (5 scenarios)

### How AI Models Work
What a model actually is · Neural network architecture · Training loop · Backpropagation · Inference and token sampling · Temperature and KV cache · Model types (LLM, Diffusion, Embedding, RL)

### How LLMs Work
Tokenization and BPE · Transformer architecture (attention, MLP layers) · Training phases (pre-training, SFT, RLHF/DPO) · Inference internals · Model landscape (GPT-4, Claude, Gemini, Llama, Mistral, Mixtral MoE)

### AI Agents
ReAct pattern (Think → Act → Observe) · Tool use and JSON schemas · Memory types (in-context, vector, episodic, procedural) · Multi-agent patterns · Live simulator (4 production scenarios) · Framework landscape (LangChain, AutoGen, CrewAI, Bedrock Agents)

### Model Context Protocol (MCP)
M×N integration problem · JSON-RPC 2.0 protocol · Primitives (Tools, Resources, Prompts) · Transport options (stdio, HTTP+SSE) · Building MCP servers in Python · Live protocol simulator

### AI Hallucination
Root cause (no truth anchor) · Six hallucination types · Token-level mechanics · Confidence calibration problem · RAG grounding · Eight mitigation strategies · Risk assessment by use case

### How ACH Works
Credit vs debit transactions · Four ACH participants (Originator, ODFI, ACH Operator, RDFI) · Full transaction lifecycle · NACHA 94-character file format (interactive field viewer) · Return codes (R01–R29, NOC) · Same Day ACH windows · Rules and compliance (NACHA, Reg E, OFAC, FFIEC)

### How Databases Work
Storage engine internals · MVCC and row versioning · SQL query planner and EXPLAIN ANALYZE · B-Tree index structure · Index types (composite, partial, BRIN, expression) · ACID guarantees · Write-Ahead Log · WAL simulator · NoSQL types (Document, Key-Value, Column-Family, Graph, Time-Series, Search)

### Red Hat OpenShift
OpenShift vs vanilla Kubernetes · RHCOS and MCO · Full architecture stack · Pod lifecycle (oc apply → running container) · Core objects (Pod, Deployment, Service, Route, PVC, HPA) · Networking and TLS termination modes · Operator pattern and AMQ Streams · Tekton + ArgoCD CI/CD · OC CLI lab (7 live scenarios) · Compliance and RBAC

---

## 🛠 Built With

- Vanilla HTML, CSS, and JavaScript — zero build toolchain
- Canvas API for data visualizations
- CSS animations for interactive elements
- Fonts via Google Fonts (Rajdhani, IBM Plex, Playfair Display, and more)

---

## 📋 Roadmap

Upcoming topics in the HAS IT Learning Series:

- [ ] How DNS Works
- [ ] How SSL/TLS Works
- [ ] How TCP/IP Works
- [ ] How CI/CD Works
- [ ] How Docker and Containers Work
- [ ] How Kubernetes Works
- [ ] How Zero Trust Security Works
- [ ] How API Design Works (REST + GraphQL)
- [ ] How Cloud Architecture Works
- [ ] How Microservices Work
- [ ] How DevSecOps Works
- [ ] How Observability Works

---

## 📄 License

© HAS — Helping Achieve Success. All rights reserved.

---

*HAS Infrastructure Academy — Helping Achieve Success through high-fidelity IT education.*
