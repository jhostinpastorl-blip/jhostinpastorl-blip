# Jhostin Jhonatan Pastor Lliuya

### Senior Automation Engineer | Intelligent Automation | Python · APIs · RPA

I design **end-to-end enterprise automation solutions**, combining RPA with software engineering, APIs, data and controlled AI capabilities according to the problem rather than defaulting to UI automation.

My professional background is rooted in enterprise RPA, with hands-on experience across process analysis, solution design, development, deployment, platform administration, production monitoring and incident support. I am extending that foundation into automation engineering through Python, APIs, SQL, distributed execution patterns, observability and AI-assisted workflows.

[LinkedIn](https://www.linkedin.com/in/jhostin-jhonatan-pastor-lliuya)

## Engineering focus

- **Automation engineering:** transactional processing, reusable components, retries, idempotency, exception handling and recoverability
- **Integration design:** choosing between direct APIs, RPA, code and hybrid approaches based on system constraints
- **RPA platforms:** UiPath, Automation Anywhere, Blue Prism and Rocketbot
- **Software & data:** Python, REST APIs, SQL, PostgreSQL and Redis
- **Operations:** orchestration, credential controls, environment promotion, structured logging, monitoring and incident handling
- **Intelligent automation:** bounded LLM workflows, structured outputs, deterministic policy, human review and evaluation

## Featured engineering work

### [Enterprise Automation Orchestrator](https://github.com/jhostinpastorl-blip/enterprise-automation-orchestrator)

Reference implementation for resilient enterprise automation where orchestration state and reliability controls remain outside the robot workflow.

`FastAPI` · `Python` · `PostgreSQL` · `Redis` · `SQLAlchemy` · `Alembic` · `Docker` · `GitHub Actions` · `OpenTelemetry`

Key engineering concerns include asynchronous execution, atomic work claiming, idempotency, bounded retries, dead-letter handling and replay, API/RPA adapter boundaries, rate-limit handling, operational metrics and auditable lifecycle state.

A reference deployment is available on Railway. It demonstrates the topology, not enterprise production scale or production-grade cloud durability.

### Intelligent Automation Case Orchestrator — portfolio project

A guarded document-driven automation architecture that separates probabilistic interpretation from deterministic authorization and execution:

`Document → LLM structured extraction → schema validation → policy → human review when required → controlled tool → API/RPA orchestration`

The central design rule is **LLM recommendation != authorization != execution**. The project explores function calling, typed outputs, deterministic policy, HITL, persisted audit state, token/cost accounting, evaluation and a controlled handoff to the automation execution layer.

The repository will be published after its standalone CI/deployment validation is complete; I do not present unvalidated portfolio code as production evidence.

## Engineering principles

**Prefer a supported API over UI automation when it provides a more reliable integration boundary.** Use RPA when UI interaction is genuinely required. Move complex or reusable logic into code/services when it improves maintainability. Use AI when ambiguity or unstructured information justifies probabilistic interpretation—and place deterministic controls around its outputs.

That is the direction of my career: moving from developing individual bots toward **engineering automation systems**.

## Current development direction

`RPA → Automation Engineering → Intelligent / AI Automation → Technical Leadership → Automation & AI Solution Architecture`

The goal is not to accumulate tools or titles. It is to strengthen system design, integrations, reliability, security, observability and technical decision-making until broader technical ownership is supported by real evidence.

---

**Current core:** Python · REST APIs · SQL · UiPath · Automation Anywhere · Blue Prism · Rocketbot · Power Automate · SAP automation

**Developing further:** C# · cloud architecture · AI/LLM engineering · system design
