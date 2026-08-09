# Yingzuo Liu

**I like building AI agents — and then trying to break them. 🧪**

My recent work focuses on runtime reliability, safe tool execution, recovery, memory, and evaluation.

### 🛠️ Right now I'm mostly working on

* reliable Agent runtimes: state, recovery, validation, and memory
* safe tool use and human-in-the-loop execution
* evaluation that catches “looks successful, actually wrong” behavior
* retrieval / search systems when I need a break from Agent runtimes

---

## 🚀 Featured Projects

### [Agent Runtime Reliability Platform](https://github.com/YingzuoLiu/agent-runtime-platform)

A production-oriented Agent runtime for reliable multi-step execution.

It includes typed Planner decisions, policy-governed tools, durable execution, restart recovery, multi-tenant authorization, and governed cross-thread memory.

A result I particularly like: removing the Validator increased nominal completion from **50% to 75%** — because invalid plans were being counted as successful. The runtime treats visible failure as better than silent success.

**Built with:** Python · FastAPI · Pydantic · SQLite · Docker

---

### [OpenClaw DataOps Guardian](https://github.com/YingzuoLiu/openclaw-dataops-guardian)

A safety-focused Agent/DataOps prototype that turns an Alertmanager incident into an evidence-gated, human-approved, restart-safe Kubernetes rollback.

The rule is simple:

> **The LLM may investigate and propose. It never gets authority to mutate infrastructure.**

The workflow combines durable incident state, Prometheus evidence, resumable approval, allowlisted Kubernetes mutation, restart reconciliation, and post-rollback recovery verification.

The repository also includes a reproducible safety matrix on disposable `kind` clusters covering denial, replay, RBAC rejection, restart ambiguity, recovery failure, and cleanup.

**Built with:** TypeScript · Node.js · Prometheus · Kubernetes · OpenClaw · Vitest

---

## 🔎 Also interested in

Agent systems are where I spend most of my time lately, but I also enjoy:

* RAG and retrieval evaluation
* search and recommendation systems
* multimodal retrieval
* LLM application infrastructure
* ML systems where the interesting part starts after `model.predict()`

---

## 🧭 Other things I've built along the way

Retrieval systems, recommendation systems, multimodal search, NLP experiments, quantitative research agents, and a probably unreasonable number of small ML projects.

A few repos worth browsing:

* [ReAct Quant Research Agent](https://github.com/YingzuoLiu/react-quant-research-agent)
* [Rec & Search Engineering](https://github.com/YingzuoLiu/rec-search-engineering)
* [Multimodal Search](https://github.com/YingzuoLiu/multimodal-search)
* [RAG Pipeline with LlamaIndex](https://github.com/YingzuoLiu/RAG-Pipeline-with-LlamaIndex)

---

### What I care about

I like systems where failures are observable, decisions are inspectable, and “the demo worked once” is not the definition of reliability.

If a system can retry, recover, explain why it acted, and refuse unsafe work, I'm probably interested in it.

