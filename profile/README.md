# ZeroHuman

**An open protocol for structured AI operations.**

We are a research collective of industry experts from startups and institutions, united by one goal: standardizing how AI agents discover, install, and execute reproducible work.

We maintain the **ZeroHuman Protocol** — an open-source initiative that defines how agents operate with typed tools, versioned skills, composable capabilities, and governed profiles.

---

## Why ZeroHuman

AI agents are proliferating across tools and platforms, but there is no common operational standard. Every team reinvents how agents find tools, follow procedures, and stay auditable. ZeroHuman addresses this with a small, composable protocol that any agent runtime can adopt.

**Core principles:**

- **Progressive disclosure** — metadata first, full instructions only when needed
- **Typed and permissioned tools** — schemas, approval gates, and network controls
- **Everything is testable** — skills are evaluated like software, not vibes
- **Every run is auditable** — traces, artefacts, and usage accounting are first-class
- **Governance is built in** — publishing, moderation, and trust tiers are part of the protocol

---

## Ecosystem

| Repository | Description |
|------------|-------------|
| [`protocol`](https://github.com/zerohuman-labs/protocol) | The ZeroHuman specification — primitives, schemas, and resolution rules |
| [`cli`](https://github.com/zerohuman-labs/cli) | Command-line tool for installing, validating, and managing ZeroHuman packages |
| [`runtime`](https://github.com/zerohuman-labs/runtime) | Reference runtime implementation |

---

## The Protocol at a Glance

ZeroHuman defines **8 primitives** that together describe the complete operational model for any agent:

| Primitive | Purpose |
|-----------|---------|
| **Tool** | Typed integration surface — API schema, auth, permissions, approval gates |
| **Skill** | Reusable procedural knowledge — YAML frontmatter + markdown instructions |
| **Capability** | Versioned composition of tools + skills + policies + evals |
| **Profile** | Role configuration — model, runtime, budgets, concurrency, memory |
| **Heartbeat** | Run-loop checklist that prevents drift and ensures consistent routines |
| **Soul** | Identity, values, and boundaries that change rarely |
| **Policy** | Enforceable rules — permissions, approvals, network policy, data sensitivity |
| **Artefact** | Immutable record of what was produced, with trace IDs and lineage |

Every package starts with a `zerohuman.yaml` manifest that declares what's inside and how to find it.

Read the full specification: [`protocol/zerohuman-v0.1.0.md`](https://github.com/zerohuman-labs/protocol/zerohuman-v0.1.0.md)

---

## Get Involved

ZeroHuman is built in the open. We welcome contributions from anyone working on agent infrastructure, tooling, or operations.

- **Discuss** — Join conversations in the [community](https://github.com/orgs/zerohuman-labs/discussions) repository
- **Propose** — Submit protocol changes via community Discussions → Proposals
- **Build** — Create and publish your own ZeroHuman packages
- **Review** — Help review community submissions and listings

---

## License

This project is open source. See individual repositories for specific license terms.
