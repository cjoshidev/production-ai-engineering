# Production AI Engineering

> **Building AI is easy. Operating AI in production is engineering.**

An open-source handbook for building, observing, evaluating, and operating AI systems in production.

---

## 🎯 Our North Star

**Production AI Engineering** exists to help engineering teams build AI systems that are reliable, observable, measurable, and production-ready.

Every guide in this repository is backed by:

* Runnable code
* Production-grade tooling
* Architecture patterns
* Real-world engineering practices
* Hands-on examples
* Dashboards, traces, and evaluation pipelines

Our goal isn't to teach AI fundamentals.

Our goal is to help you build AI systems that survive production.

---

## Why this project exists

The AI ecosystem is full of tutorials that explain how to call an LLM API or write better prompts.

Production systems are different.

They involve orchestration, tool calling, evaluation, observability, memory, reliability, security, cost management, and operational excellence.

These are the engineering challenges that determine whether an AI system succeeds in production.

This repository explores those challenges through practical implementations and production-inspired examples.

---

## What this repository is **NOT**

This repository is **not**:

* ❌ Another prompt engineering tutorial
* ❌ A collection of disconnected AI demos
* ❌ Framework-specific documentation
* ❌ A benchmark repository
* ❌ A list of AI tools

Instead, it focuses on the engineering discipline required to operate AI systems in production.

---

## Philosophy

Every guide in this repository follows the same engineering lifecycle.

```text
Build
   ↓
Observe
   ↓
Evaluate
   ↓
Operate
```

### 🏗 Build

Design and implement production-ready AI systems.

Examples include:

* Agent runtimes
* Harness engineering
* Tool orchestration
* Retrieval pipelines
* Memory architectures
* Prompt management
* Multi-agent workflows

---

### 📊 Observe

Understand exactly what your AI system is doing.

Topics include:

* OpenTelemetry
* Distributed tracing
* Metrics
* Logging
* Token accounting
* Cost monitoring
* Prompt versioning
* AI-specific SLIs and SLOs

---

### 🧪 Evaluate

Measure quality continuously.

Topics include:

* Evaluation harnesses
* Golden datasets
* Regression testing
* LLM-as-a-Judge
* Continuous evaluation
* Human feedback loops

---

### 🚀 Operate

Run AI systems with confidence.

Topics include:

* Reliability engineering
* Guardrails
* Security
* Scaling
* Incident response
* Chaos engineering
* Production runbooks

---

## Project Atlas

This repository evolves around a single production-style reference application called **Project Atlas**.

Instead of isolated code samples, every guide extends the same system.

As the project evolves, Atlas will gradually grow into a fully instrumented production AI platform featuring:

* AI Agent Runtime
* OpenTelemetry instrumentation
* Distributed tracing
* Evaluation pipelines
* Production dashboards
* Alerting
* Cost analytics
* Memory systems
* CI/CD quality gates
* Reliability patterns

Every guide adds a new capability to the platform.

---

## Current Milestone

We're currently building the foundation of the platform.

Current focus:

* Production AI Runtime
* OpenTelemetry Instrumentation
* AI Agent Observability
* Evaluation Harness
* Production Dashboards

The long-term vision is documented in **ROADMAP.md**.

---

## Repository Structure

```text
production-ai-engineering/

├── apps/
├── packages/
├── dashboards/
├── infrastructure/
├── docs/
├── datasets/
├── examples/
└── .github/
```

---

## Technology Stack

The project is intentionally built using technologies commonly adopted in production environments.

### Runtime

* Node.js
* TypeScript

### AI

* OpenAI-compatible APIs
* Model Context Protocol (MCP)
* LangGraph (where appropriate)

### Observability

* OpenTelemetry
* Langfuse
* Helicone
* Prometheus
* Grafana
* Datadog
* AWS CloudWatch

### Infrastructure

* Docker
* GitHub Actions
* Terraform
* AWS

---

## Who is this for?

Production AI Engineering is intended for:

* Software Engineers
* Platform Engineers
* AI Engineers
* DevOps Engineers
* Site Reliability Engineers
* Engineering Leaders

If you're responsible for building, deploying, or operating AI systems, this repository is for you.

---

## Contributing

This project is open source and community driven.

Contributions are welcome in the form of:

* Documentation improvements
* Production patterns
* Examples
* Dashboards
* Evaluation datasets
* Tool integrations
* Architecture discussions

Please read **CONTRIBUTING.md** before opening a pull request.

---

## License

This project is licensed under the Apache 2.0 License.

---

## The Journey Starts Here

Production AI Engineering is not a finished framework.

It's a living engineering handbook.

Every guide, every example, and every release moves us one step closer to answering a simple question:

> **How do we build AI systems that are truly production-ready?**

If you're interested in that journey, welcome aboard.
