<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/arteamis-system/.github/main/profile/assets/logo-dark.svg">
  <img src="https://raw.githubusercontent.com/arteamis-system/.github/main/profile/assets/logo-light.svg" alt="Arteamis" width="76">
</picture>

# Arteamis

**The operating system for AI-native companies.**

One shared brain for your team, and your agents.

[Website](https://arteamis.space) · [Launch the app](https://app.arteamis.space) · [Contact](mailto:clientservice@arteamis.space)

</div>

---

## What Arteamis is

Arteamis helps a founder or small founding team design, launch, and operate a hybrid
human–agent company from day one.

Every member gets a **Personal Brain** that helps them think, capture, draft, remember,
and execute. The company gets a **Company Brain** that receives reviewed knowledge,
current beliefs, decisions, rules, skills, work, and traces from the whole team.

The bridge between them is intentional promotion — never silent publication:

```text
private thinking
  → proposed company update
  → review
  → shared belief, decision, skill, doc, task, or source
```

Product rule:

```text
Personal Brain is local-first.
Company Brain is cloud-collaborative.
Promotion is the bridge.
```

## Why it exists

A company brain is not valuable because it stores knowledge. It is valuable because it
turns memory into **governed execution loops**.

Arteamis connects the whole chain, and keeps it connected:

```text
memory → belief → decision → skill → context package
       → human / agent work → trace → evaluation → brain update
```

Agent platforms will own many inner-loop primitives. Arteamis owns the company-specific
**outer loop**: permissioned memory, source-backed context, human approval, vertical
skill files, traces, outcome learning, and governance.

## The daily loop

```text
Capture → Brain Delta → Strategic Advice → Decision
        → Tasks / Work Packages → Trace → Learning
```

For a company that does not exist yet, Arteamis starts one step earlier — founder
context, an AI cofounder interview, company design, brain initialization, human/agent
org setup, then the first execution sprint.

## Principles

| Principle | What it means |
| --- | --- |
| **First Brain before Second Brain** | Arteamis amplifies verified human understanding. It never encourages you to outsource understanding to AI. Important claims require sources. |
| **Capture is trust-gated** | User-curated input and editable recaps first. No invisible meeting recorder, no silent capture. |
| **Decision reality is recorded** | What the data showed, what AI recommended, what humans decided, why they overrode it, and what happened after. |
| **Dirty data is product reality** | Missing, ambiguous, or biased data gets diagnosed — not silently optimized over. |
| **Agents act with permission** | Every agent action carries role, goal, context, skill, permission, evaluation, audit, and escalation. |
| **Graph is infrastructure** | Everyday users see beliefs, deltas, decisions, work, and traces. Graph internals stay in admin surfaces. |
| **Bounded world knowledge** | What Arteamis does not know becomes assumptions and validation tasks, not confident automation. |

## What Arteamis is not

Not a Slack clone, a Notion clone, or a Jira clone. Not a chatbot over docs, not generic
enterprise search, not a graph visualization toy, not management surveillance, and not
an autonomous agent that acts without permission.

## Architecture

Arteamis keeps a hard boundary between the client and the brain.

```text
Desktop app   macOS shell around the web app: tray, private native
              notifications and a local Code host (internal builds).
              The local-first Personal Brain and Local Vault are planned

Web app       team workspace, Company Brain, review, decisions, work,
              dashboards, admin

Cloud backend accepted shared truth, permissions, audit, work handoffs,
              company search/index, sync, governed agent context
```

The web client is a thin client and holds no domain logic. Domain logic, ingestion, the
governed maker/checker loop, and the audit log live in the Python service, with
PostgreSQL as the source of truth.

## Status

Arteamis is in **early development**. The product direction is canonical; the surfaces
are still being built. Public repositories will appear here as they stabilize.

---

<div align="center">
<sub>© 2026 Arteamis · <a href="mailto:clientservice@arteamis.space">clientservice@arteamis.space</a></sub>
</div>
