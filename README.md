<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0f172a,45:1d4ed8,75:0891b2,100:22c55e&text=Abhigyan%20Shekhar&fontColor=ffffff&fontSize=48&fontAlignY=38&desc=Building%20memory%20systems%2C%20AI%20infrastructure%2C%20and%20reliable%20software&descAlignY=59" alt="Abhigyan Shekhar — AI infrastructure and open-source developer" />

# Hi, I'm Abhigyan 👋

**Computer Science @ BMSCE · Open-source builder · AI infrastructure & systems**

I build software that remembers, reasons, and holds up outside a demo.

<p>
  <a href="mailto:abhishanu07@gmail.com"><img src="https://img.shields.io/badge/Email-abhishanu07%40gmail.com-0f172a?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/abhigyan-shekhar-4b3b8b344/"><img src="https://img.shields.io/badge/LinkedIn-Abhigyan%20Shekhar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://pypi.org/project/waggle-mcp/"><img src="https://img.shields.io/badge/PyPI-waggle--mcp-3775A9?style=for-the-badge&logo=pypi&logoColor=white" alt="waggle-mcp on PyPI" /></a>
</p>

<p>
  <img src="https://img.shields.io/badge/Bengaluru%2C%20India-14532d?style=flat-square&logo=googlemaps&logoColor=white" alt="Bengaluru, India" />
  <img src="https://img.shields.io/badge/Kubernetes-Contributor-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes contributor" />
  <img src="https://img.shields.io/badge/Focus-Agent%20Memory%20%26%20Developer%20Tools-0f766e?style=flat-square" alt="Agent memory and developer tools" />
</p>

</div>

## What I build

My work sits at the intersection of **AI agents, retrieval, developer tooling, and dependable backend systems**. I am especially interested in software that preserves context over time, exposes why it made a decision, and gives people a clear way to inspect or correct it.

Right now, that means building local-first memory infrastructure for AI agents, measuring retrieval systems instead of hand-waving about them, and contributing fixes to production open-source projects.

## Flagship project — [Waggle](https://github.com/Abhigyan-Shekhar/Waggle-mcp)

> Persistent, graph-backed memory for AI agents across sessions and tools.

<p>
  <a href="https://github.com/Abhigyan-Shekhar/Waggle-mcp/stargazers"><img src="https://img.shields.io/github/stars/Abhigyan-Shekhar/Waggle-mcp?style=flat-square&color=f59e0b" alt="Waggle GitHub stars" /></a>
  <a href="https://github.com/Abhigyan-Shekhar/Waggle-mcp/network/members"><img src="https://img.shields.io/github/forks/Abhigyan-Shekhar/Waggle-mcp?style=flat-square&color=0891b2" alt="Waggle GitHub forks" /></a>
  <a href="https://pypi.org/project/waggle-mcp/"><img src="https://img.shields.io/pypi/v/waggle-mcp?style=flat-square&color=3775A9" alt="waggle-mcp PyPI version" /></a>
  <a href="https://pepy.tech/projects/waggle-mcp"><img src="https://static.pepy.tech/personalized-badge/waggle-mcp?period=total&units=INTERNATIONAL_SYSTEM&left_color=grey&right_color=green&left_text=downloads" alt="waggle-mcp downloads" /></a>
  <a href="https://github.com/Abhigyan-Shekhar/Waggle-mcp/blob/main/LICENSE"><img src="https://img.shields.io/github/license/Abhigyan-Shekhar/Waggle-mcp?style=flat-square" alt="Waggle license" /></a>
</p>

Waggle is a local-first external memory layer for MCP-compatible agents. It stores decisions, reasons, contradictions, and changing project state as a knowledge graph so a new session can continue from durable context instead of starting from zero.

- graph and hybrid retrieval with temporal and supersession-aware memory
- SQLite by default, optional Neo4j, and local embeddings with no API key required
- MCP integrations for Codex, Claude, Cursor, Gemini CLI, Antigravity, and more
- Graph Studio for inspecting provenance, retrieval, and memory lineage
- portable `.abhi` graphs, cross-platform releases, a VS Code extension, and a Codex plugin
- benchmarked on LongMemEval with reproducible evaluation artifacts

```bash
pipx install waggle-mcp
waggle-mcp setup --yes
waggle-mcp doctor
```

[Repository](https://github.com/Abhigyan-Shekhar/Waggle-mcp) · [PyPI](https://pypi.org/project/waggle-mcp/) · [Live Workspace](https://waggle-webmcp.onrender.com/) · [Releases](https://github.com/Abhigyan-Shekhar/Waggle-mcp/releases)

## Selected projects

| Project | What it does | Built with |
| --- | --- | --- |
| **[Waggle SemCache](https://github.com/Abhigyan-Shekhar/waggle-semcache)** | Local-first semantic cache for LLM, RAG, and agent workloads with safe reuse gates, bounded SQLite storage, and inspectable match decisions. | Python, SQLite, MiniLM, OpenAI/LangChain/LiteLLM integrations |
| **[Waggle Recover](https://github.com/Abhigyan-Shekhar/waggle-recover)** | Auditable revenue-recovery agent that separates retrieved context from current authority and keeps deterministic policy in control of every action. | Python, FastAPI, React, LangGraph, Razorpay Test Mode, n8n |
| **[BorderBridge](https://github.com/Abhigyan-Shekhar/public-static-void-main)** | Humanitarian identity and case-management platform with explainable confidence scoring, evidence graphs, and self-service refugee workflows. | React, TypeScript, FastAPI, Supabase, custom graph visualization |
| **[IncidentResponseEnv](https://github.com/Abhigyan-Shekhar/incident-response-env)** | Deterministic OpenEnv benchmark for SRE agents investigating and remediating cascading production incidents under a bounded action budget. | Python, FastAPI, Pydantic, Docker, Hugging Face Spaces |
| **[OCR Q/A Segmentation](https://github.com/Abhigyan-Shekhar/ocr-qa-segmentation)** | End-to-end handwritten exam digitization with OCR, CRF sequence labeling, multi-page stitching, and structured Q/A extraction. | Python, TrOCR, CRF, OpenCV, Gradio |

## Open-source impact

I enjoy the part of open source where the bug is real, the codebase is unfamiliar, and the fix has to survive production review.

| Upstream | Merged contribution |
| --- | --- |
| [`kubernetes/kubernetes`](https://github.com/kubernetes/kubernetes/pull/135759) | Prevented a CEL composition data race by deep-copying mutable `MapType` state |
| [`kubernetes/minikube`](https://github.com/kubernetes/minikube/pull/22451) | Fixed Podman volume mounts on macOS with `host.containers.internal` support |
| [`kubernetes/minikube`](https://github.com/kubernetes/minikube/pull/22277) | Corrected nested-VM detection on macOS and removed unnecessary timeout inflation |
| [`containernetworking/cni`](https://github.com/containernetworking/cni/pull/1177) | Repaired a broken specification link in the CNI documentation |

## Highlights

- Founded and maintain **Waggle**, now a community project with **60+ contributors**, **900+ commits**, PyPI releases, and selection for **GirlScript Summer of Code** and **Social Summer of Code**.
- Landed **four merged upstream contributions** across Kubernetes, Minikube, and the Container Network Interface project.
- Won **1st place among 50 teams** at the BMSCE Mega Hackathon with BorderBridge, built in one day.
- Presented Waggle at the **Magicball Agentic Summit 2026** to founders and engineers working on AI infrastructure.
- Serve as an **AI mentor for the IEEE SIG at BMSCE**, teaching LangChain, RAG, agent workflows, and LangGraph.

## Toolbox

```text
Languages       Python · Go · Java · TypeScript · JavaScript · C
AI systems      MCP · RAG · knowledge graphs · embeddings · LangGraph · OCR · CRF
Backend         FastAPI · Node.js · REST APIs · auth · SQLite · PostgreSQL · MongoDB
Frontend        React · Vite · Tailwind CSS · data visualization
Infrastructure  Docker · Kubernetes · Minikube · GitHub Actions · Linux
Engineering     testing · benchmarks · retrieval evaluation · release automation
```

## Currently exploring

- memory systems that preserve authority, provenance, and change over time
- evaluation methods for long-context retrieval and agent behavior
- distributed systems and Kubernetes internals
- local-first AI products with transparent human control

## Let's talk

If you are working on agent memory, AI infrastructure, developer experience, or systems-oriented open source, I would love to compare notes.

**[Email](mailto:abhishanu07@gmail.com)** · **[LinkedIn](https://www.linkedin.com/in/abhigyan-shekhar-4b3b8b344/)** · **[GitHub](https://github.com/Abhigyan-Shekhar)**

<div align="center">
  <sub>Build the system. Measure it. Make it useful.</sub>
</div>
