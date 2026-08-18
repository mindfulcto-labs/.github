# mindfulcto-labs

Small, working tools for building and governing AI systems. I write these in my own time and publish the ones that turn out useful.

## What is here

Governed agent runtimes, tools for auditing what agents actually did, infrastructure for running LLMs across providers, and the operational tooling around both. Each repository runs offline, ships tests, and says plainly what it does not do.

## Repositories

| Repository | What it is |
|---|---|
| [agentic-os](https://github.com/mindfulcto-labs/agentic-os) | An ontology-driven agentic operating system, as a reference implementation |
| [agent-governance-kit](https://github.com/mindfulcto-labs/agent-governance-kit) | Audits agent run traces against their governance claims, mapped to EU AI Act and ISO/IEC 42001 references |
| [llm-gateway](https://github.com/mindfulcto-labs/llm-gateway) | Multi-provider LLM gateway: routing, fallback chains, budgets and usage accounting |
| [sre-copilot](https://github.com/mindfulcto-labs/sre-copilot) | Alert triage and runbook execution with approval gates and an audit trail |
| [confighub](https://github.com/mindfulcto-labs/confighub) | Schema-validated configuration service with environment overlays and audit history |
| [apiloom-ce](https://github.com/mindfulcto-labs/apiloom-ce) | Open-source API management platform |
| [agentic-harness](https://github.com/mindfulcto-labs/agentic-harness) | A runtime harness pattern for agentic systems |
| [compliance-as-code](https://github.com/mindfulcto-labs/compliance-as-code) | Compliance controls as code, with AIBOM |
| [agentic-engineer-path](https://github.com/mindfulcto-labs/agentic-engineer-path) | Onboarding path and roadmap for engineers joining an agentic AI team |
| [aidlc](https://github.com/mindfulcto-labs/aidlc) | AI-driven development lifecycle playbooks |
| [engineering-standards](https://github.com/mindfulcto-labs/engineering-standards) | Engineering standards and checklists |
| [awesome-ai-governance](https://github.com/mindfulcto-labs/awesome-ai-governance) | Curated AI governance list |
| [awesome-rust-ai-governance](https://github.com/mindfulcto-labs/awesome-rust-ai-governance) | Curated Rust crates for governance-flavoured work |

## How I work on these

- Personal time only. No employer material of any kind: no internal designs, no client data, no proprietary architecture. Examples use synthetic or public data.
- Everything runs offline. If a tool needs an API key to demonstrate anything, it also ships a deterministic path that does not.
- Plain English in the READMEs, including about what each tool cannot do.
- Small on purpose. These are reference implementations and working tools, not products.

## Maintained by

[@venkat-uk](https://github.com/venkat-uk). I lead engineering teams building AI platforms, and I write about that at [themindfulcto.com](https://themindfulcto.com).

## Licence

Unless a repository says otherwise, code here is Apache 2.0 and documentation is CC BY-SA 4.0.
