<h1 align="center">Parth Rohit</h1>

<p align="center">
  <strong>Computing Systems student building reliable software at the boundary of AI, backends and security.</strong><br/>
  London, UK · graduating September 2026 · available full-time
</p>

<p align="center">
  <a href="https://parthrohit.vercel.app">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/parthrohit">LinkedIn</a> ·
  <a href="mailto:parthrohit60@gmail.com">Email</a>
</p>

<p align="center">
  <a href="https://github.com/parthrohit22"><img src="https://img.shields.io/badge/GitHub-parthrohit22-181717?style=flat-square&logo=github" alt="GitHub profile" /></a>
  <a href="https://lyta.parthrohit-dev.workers.dev"><img src="https://img.shields.io/badge/Live-LYTA-0f766e?style=flat-square" alt="LYTA live deployment" /></a>
  <a href="https://www.bestpractices.dev/projects/13618"><img src="https://img.shields.io/badge/OpenSSF-Best%20Practices%20Passing-2ea44f?style=flat-square" alt="OpenSSF Best Practices passing badge" /></a>
</p>

## What I build

I build systems for workflows where a stale record, an untraceable model answer or a silent failure creates real operational cost.

My projects share a few habits:

- **Ground the decision:** separate verified facts from model-generated interpretation.
- **Preserve the trail:** keep provenance, rejected alternatives and state transitions available for review.
- **Make limits visible:** expose capability, trust and failure boundaries instead of hiding them behind a polished interface.
- **Own the whole loop:** take work from an unclear problem through design, implementation, tests, documentation and deployment.

I am currently completing a **BSc (Hons) Computing Systems** at Ulster University, London, where I am predicted a First Class and have made the Dean's List in Years 1 and 2. I am available for full-time software engineering work from September 2026.

## Featured engineering work

### [PARTHA](https://github.com/Second-Origin/PARTHA) · Repository intelligence for engineers and AI tools

PARTHA parses a repository into one revision-addressed, provenance-tracked intelligence layer so every report, documentation view and AI feature starts from the same evidence instead of rediscovering the codebase.

- Owner and maintainer, leading a small team through architecture, issues, reviews and releases.
- Routes structured repository context to OpenAI, Anthropic, Gemini, OpenRouter and Ollama integrations.
- Distinguishes implemented, partial and roadmap capabilities so the product does not imply support it cannot provide.
- Ships through tests, GitHub Actions, static analysis, CodeQL, Dependabot and dependency audits.

**Python · FastAPI · PostgreSQL · Redis · Docker Compose · React · TypeScript**

### [LYTA](https://github.com/parthrohit22/lyta) · Live edge-native AI workspace

<a href="https://lyta.parthrohit-dev.workers.dev">Try LYTA live</a>

LYTA keeps documents, citations and conversation state reusable across chats instead of treating every model call as a blank slate.

- Uses Cloudflare Workers AI, Durable Objects, embeddings and retrieval to return cited source sections.
- Separates router, identity, workspace and conversation ownership so state does not leak across boundaries.
- Opens the SSE stream before the model call, turning provider or retrieval failures into clear product errors with request IDs for diagnosis.
- Keeps prompts, uploaded content, emails and tokens out of diagnostic logs.

**TypeScript · React · Cloudflare Workers · Workers AI · Durable Objects · SSE**

### [OpenShield](https://github.com/openshield-org/openshield) · Open-source Azure security posture management

OpenShield gives startups, universities and small teams an affordable way to find Azure configuration risk and connect each finding to a practical remediation path.

- CODEOWNER for tests and documentation on a project with an **OpenSSF Best Practices passing badge**.
- Officially migrating into **OWASP**; I am expected to become a maintainer under the OWASP umbrella once the transfer completes.
- Maps findings to CIS Azure Benchmarks, NIST, ISO 27001 and SOC 2, and includes a post-quantum cryptography scanner.
- Contributed across scanner rules, validation, PostgreSQL-backed APIs, CI and the project learning portal.

**Python · Azure SDK · Flask · PostgreSQL · Alembic · React · GitHub Actions · CodeQL**

### [KALYX](https://github.com/parthrohit22/kalyx) · Execution evidence integrity

KALYX answers a difficult incident-response question: after a breach, were the logs modified, deleted or reordered before anyone relied on them?

- Normalises accepted execution events into a canonical append-only hash chain.
- Replays the ledger deterministically and reports the exact valid boundary when trust breaks.
- Blocks new ingestion when existing evidence is already untrusted and anchors verified checkpoints to an independent Raspberry Pi.
- Uses explicit trust states and deterministic rules, while stating clearly that it does not prove the original event was truthful.

**Python · FastAPI · Angular · Raspberry Pi · eBPF · pytest**

### [ReturnProof](https://github.com/parthrohit22/ReturnProof) · Deterministic evidence reconciliation

ReturnProof reconciles conflicting warehouse and supplier records into explicit return, credit and exception decisions without trusting either source globally.

- Resolves authority per claim, so condition, batch identity, quantity and credit eligibility can follow different evidence policies.
- Preserves accepted, rejected, superseded and unresolved claims in an audit record rather than discarding the losing side.
- Uses eight documented rules, including quantity conservation, to prevent stock from silently disappearing or being duplicated.
- Exposes the same decision through a tested Python engine, CLI, typed API and React operator console.

**Python · Pydantic · Typer · Django · Django Ninja · React · TypeScript · pytest · Playwright**

## Other work

| Project | What it demonstrates |
| --- | --- |
| [FieldSight](https://github.com/parthrohit22/FieldSight-Cloud-Platform) | Azure REST APIs, Cosmos DB and Blob Storage for searchable field observations with photo evidence. |
| [SecureSense](https://github.com/parthrohit22/SecureSense) | Session-split on-device tamper detection with Python-to-generated-C++ parity on an Arduino Nano 33 BLE Sense. |
| [Payment Routing System](https://github.com/parthrohit22/Payment-Routing-System) | Provider-attempt visibility, server-side RBAC and lifecycle analytics for payment operations. |

## Toolbox

**Languages**  Python · TypeScript · JavaScript · SQL · C++

**Backend and data**  FastAPI · Django · Django Ninja · Flask · Express · REST APIs · Pydantic · PostgreSQL · Redis · MongoDB · SQLite · SQLAlchemy · Alembic

**Applied AI**  LLM integrations · OpenAI · Anthropic · Gemini · OpenRouter · Ollama · Workers AI · RAG · embeddings · retrieval · prompt and context engineering · output validation · model evaluation

**Cloud and delivery**  Azure · Cloudflare Workers · Durable Objects · Docker Compose · Git · GitHub Actions · CI/CD · Application Insights

**Quality and security**  pytest · Django tests · Vitest · Playwright · CodeQL · Dependabot · static analysis · dependency audits · failure-path testing · observability · RBAC

I am currently extending this toolkit through focused learning in **Go and AWS**, while keeping the same standard of testing and ownership across the work I ship.

## Experience and contribution

**Operations & IT Support Assistant · Kukreja & Associates · July 2021 to December 2023**

Supported more than 50 users across hardware, software and networks, translating unclear issues into practical fixes and automating recurring work that removed more than 10 hours of manual effort per month.

Outside the repositories, I have served as a Student Representative and Staff-Student Consultative Committee member, mentored 25+ peers on practical AI workflows, and delivered first-year sessions on time management, GitHub, LinkedIn, open-source contribution and internship preparation.

## How I work

I am most useful when the problem is still slightly unclear. I ask what must be true, what evidence can be trusted, what happens when a dependency fails and how another engineer will verify the result later. I use AI tools to accelerate exploration, implementation and documentation, but I remain accountable for the design, tests and code that leave the repository.

## Find me

- [LinkedIn](https://www.linkedin.com/in/parthrohit)
- [Email](mailto:parthrohit60@gmail.com)
