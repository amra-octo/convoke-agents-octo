---
marp: true
theme: default
paginate: true
style: |
  section {
    font-family: 'Inter', 'Helvetica Neue', sans-serif;
    background: #FAFAFA;
    color: #1A1A2E;
    padding: 48px 64px;
  }
  h1 {
    font-size: 2.4rem;
    font-weight: 700;
    color: #1A1A2E;
    margin-bottom: 0.5em;
    line-height: 1.15;
  }
  h2 {
    font-size: 1.1rem;
    font-weight: 500;
    color: #4A5568;
    margin-bottom: 1.5em;
    letter-spacing: 0.08em;
    text-transform: uppercase;
  }
  p, li {
    font-size: 1.05rem;
    line-height: 1.7;
    color: #2D3748;
  }
  strong {
    color: #3730A3;
  }
  table {
    width: 100%;
    border-collapse: collapse;
    font-size: 0.95rem;
  }
  th {
    background: #3730A3;
    color: white;
    padding: 10px 14px;
    text-align: left;
    font-weight: 600;
  }
  td {
    padding: 10px 14px;
    border-bottom: 1px solid #E2E8F0;
  }
  tr:nth-child(even) td { background: #EEF2FF; }
  section.title-slide {
    background: #1A1A2E;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  section.title-slide h1 { color: white; font-size: 3rem; }
  section.title-slide h2 { color: #818CF8; font-size: 1.2rem; }
  section.title-slide p { color: #C7D2FE; }
  section.divider {
    background: #3730A3;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  section.divider h1 { color: white; font-size: 2.8rem; }
  section.divider p { color: #C7D2FE; font-size: 1.1rem; }
  .accent { color: #3730A3; font-weight: 700; }
  .tag {
    display: inline-block;
    background: #EEF2FF;
    color: #3730A3;
    border: 1px solid #C7D2FE;
    border-radius: 4px;
    padding: 2px 10px;
    font-size: 0.8rem;
    font-weight: 600;
    letter-spacing: 0.05em;
    margin-bottom: 1.5rem;
  }
---

<!-- _class: title-slide -->

# Convoke Agents
## Lifecycle Expansion Vision

From module ecosystem to full-lifecycle agentic platform

---

**Amalik Amriou** · Agentic Product Lead · March 2026
<span style="color: #818CF8; font-size: 0.85rem;">Exploratory / Pre-specification</span>

---

## The Window Is Open

Three forces are converging:

- **Agentic AI** is shifting from tool to organizational participant
- Products built *with* AI agents need AI agents *across their lifecycle*
- The window for establishing full-lifecycle tooling is open — **now**

Convoke covers the critical middle.
This deck maps the edges — and how to close them.

---

## Strong Core. Clear Edges.

**5 lifecycle phases** · 7 modules · 30+ agents · 40+ workflows

| Phase | Module | Scope |
|-------|--------|-------|
| Discovery | **Vortex** | 7 agents, 22 workflows — Innovation Vortex pattern |
| Design & Planning | **WDS + BMM 1–3** | UX, PRD, architecture, epics |
| Build & Quality | **BMM 4 + TEA** | Dev, sprint ops, ATDD, traceability, CI/CD |
| Production Readiness | **Gyre** | 4 agents, 7 workflows — readiness pipeline |
| Creative & Extension | **CIS + BMB** | Innovation, custom agent/workflow creation |

> The core is solid. The gaps are meaningful *precisely because* the core is solid.

---

## Six Gaps. Three Blind Spots.

**Lifecycle gaps:**

| Gap | Current State |
|-----|--------------|
| **Strategy & Vision** | No competitive analysis or business model design upstream |
| **Delivery & Release** | No feature flagging, progressive delivery, or release management |
| **Growth & Adoption** | No activation, retention, or post-launch growth workflows |
| **Operations** | No incident management, runbooks, or SLO workflows |
| **Security & Compliance** | Assessment only — no remediation or DevSecOps |
| **Sunset & Technical Debt** | Not addressed |

**Cross-cutting blind spots:** Knowledge Engineering · Systematic Documentation · Governance & Change

---

## A Three-Axis Platform

Not a pipeline. A **platform**.

**Axis 1 — Lifecycle** *(when)*
Strategy → Discovery → Design → Build → Readiness → Delivery → Growth → Operations → Sunset

**Axis 2 — Domain Mesh** *(what expertise)*
DataOps · MLOps · AgentOps · PlatformOps
*Reference pattern for supported organizations — not a centralized service*

**Axis 3 — Cross-cutting** *(what sustains it)*
Knowledge Engineering · Security & Compliance · Documentation · Governance & Change

> Each axis is independent. All three are interlocked.

---

## Knowledge Engineering: Wave Zero

Every perimeter operates on knowledge. **Most of it is trapped.**

In brownfield: tacit expertise, undocumented decisions, buried architectural rationale.

**Three capabilities:**

- **Extract** — mine codebases, documentation, repository history
- **Elicit** — structured conversations to externalize team expertise
- **Curate** — maintain a knowledge graph; expose assets to every perimeter

**The rule:** Knowledge Engineering activates *first* — before discovery, before readiness, before anything else.

> *"We can know more than we can tell."* — Michael Polanyi, 1966

---

## Seven New Perimeters, Four Waves

| Wave | Perimeters | Strategic Logic |
|------|-----------|-----------------|
| **0 — Foundation** | Knowledge Engineering | Enables everything else |
| **1 — Core Loop** | Delivery · Operations · Security | Bridge "ready" to "live" to "stable" |
| **2 — Extension** | Strategy · Growth · Documentation | Upstream vision + downstream adoption |
| **3 — Completion** | Sunset · Governance & Change · Domain Mesh | Full lifecycle closure |

Each wave is specified via Team Factory workflow — grounded in the theoretical foundations in the companion document.

---

## Tooling Is the Easy Part

Agentic AI is creating a **new organizational participant**, not just a new tool category.

Three emerging human-AI collaboration models (Harvard/Wharton, 2024):

| Model | Pattern | Outcome |
|-------|---------|---------|
| **Centaur** | Clear human/agent task division | Domain expertise deepens |
| **Cyborg** | Fluid, integrated task blending | AI-native skills develop |
| **Self-Automator** | Delegation with minimal engagement | Autonomy risk increases |

Adoption fails without:
- **Change architecture** (Kotter, ADKAR, Bridges)
- **Governance design** (Cynefin, EU AI Act, ISO 42001)
- **Psychological safety** — the strongest predictor of successful AI adoption

---

## Waves, Not Sprints

```
Wave 0    ██████████░░░░░░░░░░░░░░░░░░░░  Knowledge Engineering
          Start now. Activate in every brownfield engagement.

Wave 1    ░░░░░░░░░░██████████░░░░░░░░░░  Delivery · Operations · Security
          Bridge Gyre to production. Operationalize readiness.

Wave 2    ░░░░░░░░░░░░░░░░░░░░██████████  Strategy · Growth · Documentation
          Upstream grounding. Downstream adoption. Knowledge capture.

Wave 3    ░░░░░░░░░░░░░░░░░░░░░░░░░░████  Sunset · Governance · Domain Mesh
          Full lifecycle closure. The organizational meta-layer.
```

Each wave: specified via Team Factory → new agents → new handoff contracts.

---

## From Vision to Specification

**Immediate actions:**

1. **Begin Knowledge Engineering specification** — Team Factory workflow, Wave 0
2. **Stand up Governance & Change framework** — runs alongside every subsequent wave, from day one

**Research agenda:**
Seven open architectural questions covering agent-to-agent governance, autonomy spectrum, transformation measurement, emergent behavior at scale, and port interface evolution.

**Principle:**
Each perimeter enters specification when theoretical foundations are validated.
*This document is the input — not the output.*

---

<!-- _class: divider -->

# Thank You

**Amalik Amriou** · Agentic Product Lead

*Convoke Agents — Lifecycle Expansion Vision*
March 2026
