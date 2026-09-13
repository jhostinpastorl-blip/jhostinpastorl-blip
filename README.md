# Jhostin Jhonatan Pastor Lliuya

### Senior Automation Engineer | RPA & Intelligent Automation | Python | APIs

I design and build **end-to-end automation solutions** for enterprise processes, combining RPA with software engineering, system integrations, APIs and data when the problem requires more than UI automation.

My background is rooted in enterprise RPA and intelligent automation, with hands-on experience across the automation lifecycle: process analysis, solution design, development, deployment, platform administration, production monitoring and incident support.

I am currently deepening the software-engineering side of automation through **Python, C#, APIs, SQL and AI-assisted workflows**, with a focus on building solutions that are maintainable, observable and resilient rather than treating RPA as the default answer to every problem.

**Professional profile:** [LinkedIn — Jhostin Jhonatan Pastor Lliuya](https://www.linkedin.com/in/jhostin-jhonatan-pastor-lliuya)

## Engineering focus

- **Automation Engineering:** transactional automation, reusable components, exception handling, logging, retries, idempotency and production support
- **RPA & Intelligent Automation:** UiPath, Automation Anywhere, Blue Prism and Rocketbot
- **Software & Integration:** Python, C#, REST APIs, SQL and enterprise system integrations
- **Enterprise environments:** SAP, web applications, Excel, Outlook, databases and API-based integrations
- **Platform operations:** orchestration, credential management, environment promotion, monitoring and incident handling
- **Architecture mindset:** choosing between RPA, APIs, services, code and hybrid approaches according to system constraints and maintainability

## Featured engineering project

### [Enterprise Automation Orchestrator](https://github.com/jhostinpastorl-blip/enterprise-automation-orchestrator)

A reference architecture for resilient enterprise automation built around an API-first control plane, durable state and asynchronous workers.

**Live API:** [Railway deployment](https://api-production-f93c7.up.railway.app)

The project explores a problem I consider central to modern automation engineering: **how to keep business orchestration, state and reliability controls outside the RPA workflow while using robots only where UI interaction is actually required.**

**Implemented concepts:**

`FastAPI` · `Python` · `SQLAlchemy` · `PostgreSQL` · `Alembic` · `Redis dispatch` · `HTTP integrations` · `UiPath Orchestrator boundary` · `asynchronous workers` · `idempotency` · `bounded retries` · `dead-letter handling` · `audit trail` · `structured logging` · `correlation IDs` · `operational HTTP metrics` · `Prometheus-style metrics` · `Docker` · `GitHub Actions CI` · `Railway` · `LLM document enrichment` · `human-review guardrails` · `evaluation harness`

The repository includes a low-friction local mode, managed schema migrations, distributed integration validation against PostgreSQL and Redis, and a live Railway deployment with separate API, worker, PostgreSQL and Redis services. Dependency-aware readiness verifies database and broker connectivity before the API is considered ready. The deployment demonstrates that the reference topology can run on a cloud platform; it is not presented as evidence of enterprise production scale, load-tested availability, live production UiPath credentials or enterprise identity controls.

## How I approach automation

I do not see RPA, APIs, custom code and AI as competing technologies. They solve different parts of the problem.

A UI robot can be the right integration mechanism when a system exposes no suitable interface. When an API exists, direct integration is usually more robust. When business logic becomes complex or reusable, it may belong in a service or software component instead of inside a workflow. AI becomes useful when the problem contains genuine ambiguity or unstructured information and its outputs can be controlled, evaluated and audited.

That decision-making layer is the direction in which I am developing my career: from building automations to **engineering automation systems**.

## Current direction

My professional path is evolving around:

**RPA → Automation Engineering → Intelligent / AI Automation → Technical Leadership → Automation & AI Solution Architecture**

The objective is not to accumulate tools, but to strengthen the engineering capabilities behind enterprise automation: system design, integrations, reliability, security, observability and technical decision-making.

---

**Core technologies:** Python · C# · SQL · REST APIs · UiPath · Automation Anywhere · Blue Prism · Rocketbot · Power Automate · SAP Automation
