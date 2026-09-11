# Nicholas Reid

### AI Integrator · Software Engineer · Operational Systems & Automation

I build software that turns fragmented data, repetitive workflows, and operational processes into reliable systems.

My work focuses on **AI integration, software engineering, automation, APIs, data platforms, and operational tooling**. I’m particularly interested in systems where understanding the underlying business process matters just as much as writing the code.

---

## Featured Projects

### [SignalForge](https://github.com/nickreid524-alt/SignalForge)

An MCP-powered AI operations investigation platform that lets models gather evidence from synthetic operational systems, revise hypotheses, and produce grounded reports with citations and a complete observable investigation trace.

**Python · MCP · Pydantic · Starlette · SQLite · React · TypeScript · Vite · SSE**

**15 synthetic incident scenarios · 9 MCP tools · 342 backend tests · 54 frontend tests**

SignalForge demonstrates:

- Real Model Context Protocol client/server integration
- Evidence-driven AI investigation workflows
- Structured model outputs and typed agent actions
- Hypothesis tracking and confidence revision
- Evidence IDs and structural citation validation
- Deterministic RAG over runbooks and historical incidents
- Anthropic and OpenAI provider adapters
- Scripted and replay providers for zero-cost deterministic demonstrations
- Prompt-injection and tool-boundary defenses
- SQLite-backed observable investigation traces
- Real-time investigation updates over Server-Sent Events
- Deterministic AI evaluation across 15 authored failure scenarios

The scripted benchmark completes all 15 scenarios with **100% citation validity, zero unsupported claims, 96.8% decisive evidence recall, and zero red-herring adoption**.

**[View SignalForge →](https://github.com/nickreid524-alt/SignalForge)**

---

### [OpsPilot](https://github.com/nickreid524-alt/OpsPilot)

A full-stack operational intake and exception-management platform built to process inconsistent supplier data through a controlled, auditable workflow.

**Python · FastAPI · PostgreSQL · Next.js · TypeScript · Docker · GitHub Actions**

**1,257 synthetic records · 88.1% automatically processed · 236-test suite**

OpsPilot:

- Detects incoming supplier formats
- Maps inconsistent records into a canonical domain model
- Normalizes and validates operational data
- Detects exact and ambiguous duplicates
- Routes exceptions for human review
- Supports controlled corrections and re-evaluation
- Maintains an auditable history of review decisions
- Preserves original source evidence through the ingestion pipeline
- Uses PostgreSQL migrations and regression coverage to validate production-like behavior
- Runs through a Dockerized multi-service environment with automated CI

**[View OpsPilot →](https://github.com/nickreid524-alt/OpsPilot)**

---

### [ServiceLens](https://github.com/nickreid524-alt/ServiceLens)

A local-first desktop work-order intelligence application that turns Excel maintenance exports into operational dashboards, exception queues, routing recommendations, and management reports.

**Python · tkinter/ttk · OOXML · PDF · CSV · GitHub Actions**

**2,084 synthetic work orders · 29 intelligence rules · 353-test suite · zero runtime dependencies**

ServiceLens:

- Reads `.xlsx` work-order exports using the Python standard library
- Resolves inconsistent column names through a canonical schema and alias layer
- Normalizes work-order data into a structured domain model
- Evaluates 12 integrity rules and 17 operational intelligence rules
- Routes exceptions into actionable review queues
- Explains the evidence, policy, thresholds, and fields behind each finding
- Provides dashboard, explorer, intelligence, reporting, and rules interfaces
- Generates PDF review packs, exception registers, and CSV exports
- Runs entirely locally with no database, server, or cloud dependency

**[View ServiceLens →](https://github.com/nickreid524-alt/ServiceLens)**

---

## Engineering Focus

I’m particularly interested in building:

- AI-enabled operational systems
- Agentic workflows with controlled tool use
- Model Context Protocol integrations
- Internal platforms and workflow automation
- Data-intensive applications
- API integrations and backend services
- Human-in-the-loop systems
- Operational intelligence and decision-support tools
- Systems that replace spreadsheet-heavy or repetitive manual processes

---

## Tech

**Languages**  
Python · TypeScript · SQL

**AI & Agent Systems**  
Model Context Protocol (MCP) · Tool Calling · RAG · Structured Outputs · AI Evaluations · Evidence Grounding · Provider Abstraction

**Backend & APIs**  
FastAPI · Starlette · REST APIs · SSE · Pydantic · SQLAlchemy · Alembic

**Frontend & Desktop**  
React · Next.js · Vite · tkinter · ttk

**Data & Processing**  
PostgreSQL · SQLite · Excel / OOXML · CSV · FTS5 · Data Validation · Data Normalization · Rule Engines

**Infrastructure & Engineering**  
Docker · GitHub Actions · Automated Testing · CI/CD · Git

---

## Engineering Approach

I care about software that solves real operational problems.

That means building systems that are:

- **Testable** — behavior is backed by automated validation
- **Auditable** — important decisions and transformations can be inspected
- **Grounded** — AI-generated conclusions can be traced back to evidence
- **Maintainable** — business logic is separated from presentation and infrastructure
- **Explainable** — users can understand why the system produced a result
- **Secure by design** — trust boundaries and tool permissions are explicit
- **Practical** — technology choices are driven by the operational problem rather than complexity for its own sake

---

## Current Focus

I’m continuing to build around:

**AI integration · operational software · agentic workflows · data platforms · workflow automation · API integrations · decision-support systems**
