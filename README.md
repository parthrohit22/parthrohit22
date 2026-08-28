<h1 align="center">Parth Rohit</h1>

<p align="center">
  <strong>Engineer building AI-native products, backend systems and trustworthy software.</strong><br />
  London, UK · BSc (Hons) Computing Systems · Available full-time from September 2026
</p>

<p align="center">
  <a href="https://www.parthrohit.com">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/parthrohit">LinkedIn</a> ·
  <a href="mailto:parthrohit60@gmail.com">Email</a>
</p>

---

I build software for workflows where a model answer, system record or automated decision needs to remain explainable after it is produced.

Across my projects, I ground AI features in structured context, make state ownership explicit, preserve provenance and audit history, and design failure paths as deliberately as the happy path.

## Focus

| Area | What I work on |
| --- | --- |
| **AI-native systems** | Retrieval, cited responses, output validation and tool integrations that stay grounded in evidence. |
| **Backend and data** | Typed APIs, reconciliation logic, PostgreSQL-backed services and explicit state boundaries. |
| **Trust and reliability** | Provenance, deterministic verification, testing, observability and clear capability limits. |
| **Product delivery** | Interfaces, documentation, CI and review gates that make an engineering system usable by others. |

## Selected engineering work

### [LYTA](https://github.com/parthrohit22/lyta) · Live edge-native AI workspace

[Try LYTA live →](https://lyta.parthrohit-dev.workers.dev)

Keeps documents, citations and conversation state reusable across chats, so users do not rebuild their context from zero for every answer.

- Uses Cloudflare Workers AI, Durable Objects, embeddings and retrieval to return cited source sections.
- Separates router, identity, workspace and conversation ownership, keeping state boundaries explicit.
- Opens the SSE stream before model execution so provider or retrieval failures become controlled product errors.

`TypeScript` · `React` · `Cloudflare Workers` · `Workers AI` · `Durable Objects` · `SSE`

### [PARTHA](https://github.com/Second-Origin/PARTHA) · Repository intelligence for engineers and AI tools

Turns fragmented codebase knowledge into structured evidence, so engineers and downstream AI features do not re-derive repository context for every task.

- Owner and maintainer, coordinating a small project team through scope, pull requests, reviews and quality gates.
- Builds React, TypeScript, FastAPI and PostgreSQL services around one shared repository-intelligence model.
- Keeps repository revision, file path and line provenance with each supported fact, making reports and AI features checkable against their source.

`Python` · `FastAPI` · `PostgreSQL` · `Redis` · `Docker` · `React` · `TypeScript`

### [KALYX](https://github.com/parthrohit22/kalyx) · Execution-evidence integrity

Lets investigators verify whether execution logs were altered, deleted or reordered after a system compromise.

- Stores accepted events in a hash-linked ledger and replays the chain deterministically to locate the exact trust break.
- Refuses further appends once the trust boundary is broken and anchors verified checkpoints to an independent Raspberry Pi service.
- Uses explicit trust states and deterministic rules while clearly stating that it cannot prove the original event was truthful.

`Python` · `FastAPI` · `Angular` · `Raspberry Pi` · `eBPF` · `pytest`

### [ReturnProof](https://github.com/parthrohit22/ReturnProof) · Deterministic evidence reconciliation

Resolves conflicting warehouse and supplier records field by field, so return, stock and supplier-credit decisions are defensible.

- Applies documented rules to condition, batch identity, expiry, quantity and credit eligibility rather than choosing one source globally.
- Preserves accepted, rejected, superseded, corrupted and unresolved evidence with the rule behind every decision.
- Tests the reconciliation engine, Django API and React operator workflow, including quantity-conservation checks.

`Python` · `Pydantic` · `Django` · `Django Ninja` · `React` · `TypeScript` · `pytest` · `Playwright`

## Open source

### [OpenShield](https://github.com/openshield-org/openshield) · Azure cloud-security posture management

OpenShield gives teams practical visibility into Azure configuration risk and connects findings to remediation guidance.

- Hold merge access to `dev` and am a CODEOWNER for tests and documentation; I also built the OpenShield Learn contributor portal.
- Contributed to scanner correctness, compliance mappings, database reliability, CI validation, tests and documentation.
- Holds an [OpenSSF Best Practices passing badge](https://www.bestpractices.dev/projects/13618) and is progressing through OWASP governance. I will become a maintainer under OWASP once the migration completes.

`Python` · `Azure SDK` · `Flask` · `PostgreSQL` · `Alembic` · `React` · `GitHub Actions` · `CodeQL`

## Stack

**Languages**  
`Python` `TypeScript` `JavaScript` `SQL` `C++`

**Backend and data**  
`FastAPI` `Django` `Django Ninja` `Flask` `REST APIs` `Pydantic` `PostgreSQL` `Redis` `MongoDB` `SQLite` `SQLAlchemy` `Alembic`

**AI and LLM engineering**  
`LLM integrations` `Workers AI` `RAG` `Embeddings` `Retrieval` `Citations` `Output validation` `Model evaluation` `MCP`

**Cloud and delivery**  
`Cloudflare Workers` `Durable Objects` `Microsoft Azure` `Docker` `GitHub Actions` `CI/CD` `Application Insights`

**Testing and security**  
`pytest` `Django tests` `Vitest` `Playwright` `CodeQL` `Dependency audits` `Failure-path testing` `RBAC`

I use Codex and Claude Code to speed up exploration and implementation, while remaining accountable for the design, tests and code that leave the repository.

## Academic record and contribution

- **BSc (Hons) Computing Systems**, Ulster University, London · Expected September 2026 · Predicted First Class
- **Dean's List**, Years 1 and 2
- **Oracle Certified Foundations Associate – Agentic AI (2026)**
- Oracle SQL Explorer completion badge · Microsoft Learn: enterprise-grade MCP and Microsoft Foundry tool ecosystems
- Project owner and maintainer of PARTHA, coordinating a small project team
- Student Representative and Staff-Student Consultative Committee member, 2024–2026
- Mentored **15+ peers** on practical AI workflows and development tooling
- Delivered workshops and seminars for first-year students on settling into university life, academic awareness, job preparation, GitHub, LinkedIn, open source, ethical AI use and academic integrity

## Find me

[Portfolio](https://www.parthrohit.com) · [LinkedIn](https://www.linkedin.com/in/parthrohit) · [Email](mailto:parthrohit60@gmail.com)
