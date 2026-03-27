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
    font-size: 2.2rem;
    font-weight: 700;
    color: #1A1A2E;
    margin-bottom: 0.4em;
    line-height: 1.15;
  }
  h2 {
    font-size: 1.0rem;
    font-weight: 500;
    color: #4A5568;
    margin-bottom: 1.2em;
    letter-spacing: 0.08em;
    text-transform: uppercase;
  }
  h3 {
    font-size: 1.1rem;
    font-weight: 600;
    color: #3730A3;
    margin: 0.8em 0 0.4em;
  }
  p, li {
    font-size: 0.95rem;
    line-height: 1.65;
    color: #2D3748;
  }
  strong { color: #3730A3; }
  em { color: #6B7280; }
  table {
    width: 100%;
    border-collapse: collapse;
    font-size: 0.85rem;
  }
  th {
    background: #3730A3;
    color: white;
    padding: 8px 12px;
    text-align: left;
  }
  td { padding: 8px 12px; border-bottom: 1px solid #E2E8F0; }
  tr:nth-child(even) td { background: #EEF2FF; }
  section.title-slide {
    background: #1A1A2E;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  section.title-slide h1 { color: white; font-size: 2.8rem; }
  section.title-slide h2 { color: #818CF8; }
  section.title-slide p { color: #C7D2FE; }
  section.divider {
    background: #3730A3;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  section.divider h1 { color: white; font-size: 2.4rem; }
  section.divider p { color: #C7D2FE; }
  section.refs { font-size: 0.72rem; }
  section.refs h3 { font-size: 0.85rem; margin-top: 0.8em; }
  section.refs li { font-size: 0.72rem; line-height: 1.5; }
  blockquote {
    border-left: 3px solid #3730A3;
    padding-left: 1em;
    color: #4A5568;
    font-style: italic;
  }
---

<!-- _class: title-slide -->

# Convoke Agents
## Lifecycle Expansion Vision — Full Depth

From module ecosystem to full-lifecycle agentic platform

---

**Amalik Amriou** · Agentic Product Lead · March 2026
<span style="color: #818CF8; font-size: 0.85rem;">Exploratory / Pre-specification · Theoretical Foundations Document</span>

---

<!-- _class: divider -->

# Part 1
## Where Convoke Stands Today

---

## Discovery & Validation — Vortex

**7 agents · 22 workflows · Innovation Vortex pattern (Appelo, 2022)**

Non-linear flow governed by a compass routing system:

| Agent | Stream | Role |
|-------|--------|------|
| **Emma** | Contextualize | Problem framing, strategic context |
| **Isla** | Empathize | User research, empathy mapping |
| **Mila** | Synthesize | JTBD-framed problem definitions |
| **Liam** | Hypothesize | Testable hypotheses, assumption maps |
| **Wade** | Externalize | Lean experiments, MVPs, PoCs, PoVs |
| **Noah** | Sensitize | Production signals, behavioral patterns |
| **Max** | Systematize | Validated learning, pivot/patch/persevere |

*Theoretical foundations: Innovation Vortex (Appelo) · Lean Startup (Ries) · JTBD (Christensen) · Empathy Mapping (Gray) · Build-Measure-Learn · Signal Detection Theory*

---

## Design & Planning — WDS + BMM Phases 1–3

**WDS — 10-step design workflow:**
Project alignment → Trigger mapping → UX scenarios → UX design → Agentic development → Asset generation → Design system → Product evolution

**BMM Phases 1–3:**
- Phase 1: Requirements analysis, PRD creation
- Phase 2: UX and product planning
- Phase 3: Architecture, epics, and story breakdown

*Agents: Freya (UX), Saga (analysis)*
*Theoretical foundations: Design Thinking (Brown) · Human-Centered Design (d.school) · ADRs (Nygard)*

---

## Build, Quality & Readiness — BMM 4 + TEA + Gyre

**BMM Phase 4:** Dev · QA · Scrum Master · Code Review · Sprint Planning · Retrospectives · Course Correction

**TEA — 8 test workflows:**
Test strategy · ATDD automation · Traceability matrix · CI/CD pipeline · NFR assessment · Test framework · E2E automation · Test review
*Agent: Murat (Test Architect)*

**Gyre — 4-stage readiness pipeline:**
Scout (stack detection) → Atlas (capabilities manifest) → Lens (gap identification) → Coach (review + feedback loop)

*Theoretical foundations: Agile/Scrum · ATDD · Continuous Integration · DORA (Forsgren) · Google PRR (Beyer) · OpenTelemetry · SLSA · Continuous Delivery (Humble & Farley)*

---

<!-- _class: divider -->

# Part 2
## Lifecycle Model & Gap Analysis

---

## The Full Lifecycle vs. Current Coverage

```
  Strategy    Discovery    Design    Build    Readiness    Delivery    Growth    Operations    Sunset
  ┌───────┐  ┌─────────┐ ┌──────┐ ┌───────┐ ┌─────────┐ ┌────────┐ ┌───────┐ ┌──────────┐ ┌───────┐
  │  GAP  │  │ VORTEX  │ │ WDS  │ │  BMM  │ │  GYRE   │ │  GAP   │ │  GAP  │ │   GAP    │ │  GAP  │
  │       │  │ 7 agents│ │ BMM  │ │  TEA  │ │ 4 agents│ │        │ │       │ │          │ │       │
  └───────┘  └─────────┘ └──────┘ └───────┘ └─────────┘ └────────┘ └───────┘ └──────────┘ └───────┘

  CROSS-CUTTING GAPS:
  ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
  │ KNOWLEDGE ENGINEERING (tacit knowledge is trapped, not extracted)                           │
  ├──────────────────────────────────────────────────────────────────────────────────────────────┤
  │ DOCUMENTATION (partial in WDS — no systematic Diátaxis-based approach)                     │
  ├──────────────────────────────────────────────────────────────────────────────────────────────┤
  │ GOVERNANCE, CHANGE MANAGEMENT & ORGANIZATIONAL TRANSFORMATION                               │
  └──────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## Gap Summary

| Gap | Current State | Impact |
|-----|--------------|--------|
| **Strategy & Vision** | Emma frames problems; no strategic positioning | Discovery starts without strategic grounding |
| **Delivery & Release** | Gyre assesses readiness; no release management | Gap between "ready" and "live" |
| **Growth & Adoption** | Noah reads signals; no activation/retention workflows | Post-launch evolution is blind |
| **Operations** | Gyre identifies gaps; no incident management | Readiness without operational follow-through |
| **Sunset & Tech Debt** | Not addressed | No lifecycle end management |
| **Security & Compliance** | Gyre detects; no threat modeling or DevSecOps | Assessment without remediation |
| **Documentation** | WDS covers design docs; no systematic strategy | Knowledge loss across lifecycle |
| **Governance & Change** | Not addressed | No framework for governing the transformation |

---

<!-- _class: divider -->

# Part 3
## Theoretical Foundations for New Perimeters

---

## Strategy & Vision Perimeter

**Gap:** Emma frames problems. No one frames the *space* in which problems are worth finding.

**Potential agents:** Strategic Analyst · Business Model Architect · Wardley Mapper

**Core theoretical foundations:**

- **Porter's Five Forces** *(Porter, 1980)* — industry structure analysis: supplier power, buyer power, substitutes, new entrants, rivalry
- **Blue Ocean Strategy** *(Kim & Mauborgne, 2005)* — value innovation over Red Ocean competition
- **Strategy Choice Cascade** *(Lafley & Martin, 2013)* — winning aspiration, where to play, how to win, capabilities, management systems
- **Good Strategy/Bad Strategy** *(Rumelt, 2011)* — coherent strategy: diagnosis + guiding policy + coherent actions
- **Wardley Mapping** *(Wardley, 2018)* — value chain positioning, component evolution, situational awareness
- **Business Model Canvas** *(Osterwalder & Pigneur, 2010)* — shared language for business model design and iteration

---

## Delivery & Release Perimeter

**Gap:** No release management, feature flagging, or progressive delivery between "ready" and "live."

**Potential agents:** Release Strategist · Feature Flag Manager · Rollback Analyst

**Core theoretical foundations:**

- **Continuous Delivery** *(Humble & Farley, 2010)* — deployment pipeline patterns, infrastructure as code, release management
- **Progressive Delivery & Feature Flags** *(Hodgson & Echagüe, 2020)* — decouple deployment from release; eight flag best practices
- **Trunk-Based Development** *(Forsgren et al., 2018)* — empirical correlation with elite delivery performance; short-lived branches, small batch sizes
- **Deployment Strategies** — canary deployments, blue-green, rolling updates, traffic shifting; formalized in Kubernetes patterns
- **Release Engineering** *(Beyer et al., 2016)* — Google's approach to release management as an engineering discipline

---

## Growth & Adoption Perimeter

**Gap:** Noah interprets production signals. No activation, retention, or growth workflows post-launch.

**Potential agents:** Growth Analyst · Onboarding Architect · Retention Strategist

**Core theoretical foundations:**

- **Product-Led Growth** *(Bush, 2019)* — the product itself as the primary growth engine; shift from sales-driven to product-driven acquisition
- **Pirate Metrics AARRR** *(McClure, 2007)* — Acquisition · Activation · Retention · Referral · Revenue; measurement framework for each stage
- **North Star Metric** *(Ellis, 2013)* — single metric capturing core value delivered; input metrics driving it
- **Activation & Onboarding** *(Reforge, 2020–ongoing)* — Setup → Aha Moment → Habit Loop; most critical AARRR conversion point
- **JTBD for Growth** *(Traynor et al., 2016)* — applies JTBD to product marketing, onboarding design, feature adoption
- **Experimentation at Scale** *(Kohavi et al., 2020)* — statistical rigor in A/B testing and online experimentation for growth optimization

---

## Operations & Resilience Perimeter

**Gap:** Gyre identifies operational gaps. No incident management, runbooks, or SLO workflows.

**Potential agents:** Incident Commander · Runbook Engineer · Resilience Analyst

**Core theoretical foundations:**

- **Site Reliability Engineering** *(Beyer et al., 2016 + 2018)* — SLOs, SLIs, error budgets, incident management, postmortems
- **Incident Management** *(PagerDuty, 2015–ongoing)* — incident response best practices, runbook automation, escalation patterns
- **Chaos Engineering** *(Rosenthal et al., 2020)* — proactive resilience testing through controlled failure injection; hypothesis → vary events → run in production → automate
- **Learning from Incidents** *(Woods, 2017 — STELLA)* — complex systems thinking; beyond root cause to systemic understanding
- **SLO Implementation** *(Hidalgo, 2020)* — detailed SLO methodology linking reliability targets to business outcomes through error budgets

---

## Security & Compliance Perimeter

**Gap:** Gyre detects security gaps. No threat modeling, DevSecOps, or compliance workflows.

**Potential agents:** Threat Modeler · Compliance Analyst · Supply Chain Auditor

**Core theoretical foundations:**

- **Threat Modeling / STRIDE** *(Shostack, 2014)* — Spoofing · Tampering · Repudiation · Information Disclosure · DoS · Elevation of Privilege
- **DevSecOps** *(OWASP, 2021)* — embedding security throughout the development pipeline; NIST SSDF (SP 800-218)
- **Software Supply Chain Security** *(NTIA, 2021)* — SBOM minimum elements; extends SLSA referenced in Gyre
- **EU AI Act** *(European Union, 2024)* — risk-based regulatory framework; Convoke agents may themselves fall under AI governance requirements
- **NIST AI Risk Management Framework** *(NIST, 2023)* — voluntary framework for responsible AI across the system lifecycle
- **ISO/IEC 42001** *(ISO/IEC, 2023)* — first international standard for organizational AI governance; enables audit and certification

---

## Documentation & Sunset Perimeters

**Documentation gap:** WDS covers design docs. No systematic documentation strategy across the lifecycle.

**Potential agents:** Documentation Strategist · Knowledge Curator · Learning Librarian
- **Diátaxis** *(Procida, 2017–ongoing)* — Tutorials · How-to Guides · Reference · Explanation
- **Docs-as-Code** *(Gentle, 2017/2022)* — version control, CI/CD, automated publishing
- **ADRs** *(Nygard, 2011)* — lightweight decision documentation capturing context, decision, consequences
- **SECI Model** *(Nonaka & Takeuchi, 1995)* — Socialization → Externalization → Combination → Internalization
- **The Fifth Discipline** *(Senge, 1990)* — systems thinking as the integrating discipline for learning organizations

**Sunset gap:** Not addressed. No lifecycle end management.

**Potential agents:** Debt Analyst · Migration Planner · Sunset Coordinator
- **Technical Debt** *(Cunningham, 1992)* — origin of the metaphor; incomplete understanding, not sloppy code
- **Behavioral Code Analysis** *(Tornhill, 2018)* — complexity hotspots through code churn patterns
- **Strangler Fig Pattern** *(Fowler, 2004)* — incremental legacy modernization
- **Refactoring** *(Fowler, 2018)* — systematic design improvement under behavioral preservation

---

<!-- _class: divider -->

# Part 4
## Knowledge Engineering — From Documentation to Knowledge Assets

---

## The Knowledge Problem

> *"We can know more than we can tell."* — Michael Polanyi, 1966

Most organizational knowledge exists on a spectrum:

```
Fully Explicit          ←────────────────────────────→          Deeply Tacit
  API docs · ADRs          living in team memory          architectural rationale
                                                           edge case expertise
                                                           experiment learnings
```

**The distinction that matters:**
- Documentation *captures what is produced*
- Knowledge Engineering *extracts what already exists but isn't accessible*

**Cognitive Debt** *(Storey, 2026):* As AI generates more code, human understanding of the codebase erodes. Knowledge extraction becomes not just useful but **essential**.

---

## Knowledge Engineering: Theoretical Foundations

**Tacit and explicit knowledge:**
- **The Tacit Dimension** *(Polanyi, 1966)* — "We can know more than we can tell." Much organizational knowledge cannot be articulated through documentation alone.
- **SECI Model** *(Nonaka & Takeuchi, 1995)* — Knowledge Engineering operationalizes the *Externalization phase at scale* — converting tacit knowledge into explicit, consumable assets
- **Knowledge Elicitation** *(Cooke, 1994)* — structured techniques: interviews, protocol analysis, card sorting, repertory grids
- **Architecture as Design Decisions** *(Jansen & Bosch, 2005)* — architecture knowledge lives in *decisions and rationale*, not diagrams — usually undocumented in brownfield

**AI-augmented extraction (2024–2026):**
- **GraphRAG** *(Microsoft Research, 2024)* — hierarchical knowledge graph from unstructured text; multi-hop reasoning over organizational knowledge
- **Mining Software Repositories** *(Kagdi et al., 2007)* — version control, bug trackers, and code as knowledge repositories
- **Cognitive Debt** *(Storey, 2026)* — AI-generated code outpacing human comprehension; knowledge engineering as organizational survival capability

---

## Knowledge Engineering Perimeter

```
  KNOWLEDGE SOURCES              KNOWLEDGE ENG.            KNOWLEDGE CONSUMERS
  ┌──────────────────┐          ┌──────────────┐          ┌────────────────────┐
  │ Codebases        │─extract─▶│              │─expose──▶│ Discovery (Vortex) │
  │ Existing docs    │─extract─▶│   Extract    │─expose──▶│ Build (BMM/TEA)    │
  │ Team expertise   │─elicit──▶│   Refine     │─expose──▶│ Readiness (Gyre)   │
  │ Decision history │─mine────▶│   Expose     │─expose──▶│ Any perimeter      │
  │ Incident reports │─extract─▶│              │─expose──▶│ Human teams        │
  └──────────────────┘          └──────────────┘          └────────────────────┘
```

**Three capabilities:**
- **Extract** — architecture recovery, dependency mapping, decision archaeology, evolution patterns
- **Elicit** — structured conversations: architectural rationale, edge case expertise, tribal knowledge, unwritten rules
- **Curate** — structured knowledge assets, versioned knowledge graph with provenance, contradiction detection, knowledge decay monitoring

**Brownfield rule:** In brownfield projects, Knowledge Engineering activates *first* — before discovery, before readiness, before anything.

---

<!-- _class: divider -->

# Part 5
## Domain Mesh — A Reference Pattern

---

## The Problem: Centralization vs. Domain Ownership

Products spanning multiple technical disciplines face a recurring tension:

- Lifecycle activities need **domain-specific expertise** (discovery needs data analysis, readiness needs ML evaluation)
- Centralizing that expertise creates **bottlenecks and violates domain ownership**

This mirrors exactly the problems that **Data Mesh, Service Mesh, and Agentic Mesh** patterns were designed to solve.

**The insight:** Specialized disciplines should be organized as **decentralized, self-serve, federated capabilities** — not as centralized teams or monolithic modules.

> *Note: This is a reference pattern for the organizations Convoke supports — not a commitment to build mesh infrastructure within Convoke itself.*

---

## Mesh Pattern Foundations

**Data Mesh** *(Dehghani, 2022):*
Four principles: domain-oriented data ownership · data as a product · self-serve infrastructure · federated computational governance
*The foundational analogy: treat specialized capabilities as products owned by domains.*

**Service Mesh** *(Istio/Linkerd, 2017–ongoing):*
Sidecar proxy pattern separates infrastructure concerns from business concerns.
*The insight: how modules communicate is separated from what modules do.*

**Agentic Mesh** *(Broda, 2025):*
Decentralized agent discovery, capability advertisement, dynamic routing, federated governance.
*The most directly relevant pattern for Convoke's expansion.*

**Domain-Driven Design** *(Evans, 2003):*
Bounded Contexts with explicit interfaces. Each specialized discipline is a Bounded Context.

**Hexagonal Architecture** *(Cockburn, 2005/2024):*
Ports (abstract interfaces) and Adapters (concrete implementations). Each domain module exposes capabilities through standard ports.

---

## The Domain Mesh Pattern

```
  ┌──────────────────────────────────────────────────────────────────────────┐
  │             MESH INFRASTRUCTURE LAYER                                    │
  │   Discovery · Routing · Capability Registry · Governance Contracts       │
  └──────────────────────────────────────────────────────────────────────────┘
        │              │              │              │
  ┌─────▼────┐   ┌─────▼────┐  ┌─────▼────┐  ┌─────▼────┐
  │ DataOps  │   │  MLOps   │  │ AgentOps │  │PlatformOps│
  │          │   │          │  │          │  │          │
  │ assess   │   │ assess   │  │ assess   │  │ assess   │
  │ build    │   │ build    │  │ build    │  │ build    │
  │ monitor  │   │ monitor  │  │ monitor  │  │ monitor  │
  │ advise   │   │ advise   │  │ advise   │  │ advise   │
  └─────┬────┘   └─────┬────┘  └─────┬────┘  └─────┬────┘
        └──────────────┴──────────────┴──────────────┘
  ┌──────────────────────────────────────────────────────────────────────────┐
  │              LIFECYCLE PERIMETERS (consumers of domain capabilities)     │
  │   Strategy · Discovery · Design · Build · Readiness · Delivery · ...    │
  └──────────────────────────────────────────────────────────────────────────┘
```

**Standard port interface** — uniform across all domain modules:
`assess(context)` → assessment artifact · `build(spec)` → implementation artifact
`monitor(target)` → monitoring config · `advise(question)` → domain guidance

---

<!-- _class: divider -->

# Part 6
## Organizational Transformation

---

## Classical Change Management

**Macro-level change leadership:**

- **Kotter's 8-Step Model** *(Kotter, 1996/2014)* — urgency → coalition → vision → volunteers → action → wins → acceleration → institutionalization
- **Lewin's Model** *(Lewin, 1947)* — Unfreeze → Change → Refreeze; frames each module adoption as a distinct transition
- **McKinsey 7-S** *(Peters & Waterman, 1982)* — Structure · Strategy · Systems · Skills · Staff · Style · Shared Values; all seven must shift together

**Individual-level adoption:**

- **ADKAR** *(Hiatt, Prosci)* — Awareness · Desire · Knowledge · Ability · Reinforcement; organizational change succeeds only when individuals change
- **Bridges' Transition Model** *(Bridges, 1991)* — Ending → Neutral Zone → New Beginning; addresses the emotional journey of teams whose roles evolve alongside agents

**Organizational design:**

- **Team Topologies** *(Skelton & Pais, 2019/2024)* — stream-aligned, enabling, platform, complicated-subsystem teams; restructure around value streams where agents participate
- **Conway's Law & Inverse Conway Maneuver** — restructure teams deliberately to produce the desired agent ecosystem architecture
- **Sociotechnical Systems Theory** *(Trist & Bamforth, 1951)* — joint optimization of social (human teams) and technical (agents) subsystems

---

## Agentic Transformation: What Makes This Different

**Role transformation research (2024):**

Three human-AI collaboration models *(Randazzo, Lifshitz-Assaf, Mollick et al., Harvard/Wharton):*

| Model | Pattern | Learning Outcome |
|-------|---------|-----------------|
| **Centaur** | Clear task division: human does X, agent does Y | Domain expertise deepens |
| **Cyborg** | Fluid integration: tasks blended in real time | AI-native skills develop |
| **Self-Automator** | Delegation with minimal engagement | Autonomy risk; skill atrophy |

**Live organizational case study:**
*Anthropic (2025–2026)* — engineers self-describe as "managers of AI agents"; 70%+ time on code review/revision rather than net-new code.

**Empirical evidence:**
*Brynjolfsson & Li (2023–2024, NBER)* — 15% average productivity gain; less experienced workers benefit most (speed and quality). Heterogeneous effects demand differentiated organizational responses.

---

## Governance Frameworks

**Decision governance:**
- **Cynefin Framework** *(Snowden, 2007)* — Clear/Complicated: agents can handle autonomously · Complex/Chaotic: require human judgment · Disorder: triage first
- **DACI** *(Atlassian)* — Driver · Approver · Contributors · Informed; needs extension to clarify agent roles and accountability

**Technology & AI governance:**
- **TOGAF** *(The Open Group)* — Architecture Development Method; governance processes for technology decisions; 80% Fortune 500 adoption
- **IEEE 7000 Series** — Human Rights · Well-being · Accountability · Transparency · Minimizing Misuse; responsible AI governance
- **EU AI Act** *(European Union, 2024)* — risk-based framework; Convoke agents may fall under regulatory scope as they participate in product decisions
- **ISO/IEC 42001** *(2023)* — first international standard for AI management systems; enables formal audit and certification

**Adoption & diffusion:**
- **Diffusion of Innovations** *(Rogers, 2003)* — Innovators → Early Adopters → Early Majority → Late Majority → Laggards
- **Crossing the Chasm** *(Moore, 2014)* — the visionary-to-pragmatist gap; requires different messaging and whole-product strategy
- **Psychological Safety** *(Edmondson)* — the strongest predictor of successful AI adoption across all literature reviewed

---

<!-- _class: divider -->

# Part 7
## Synthesis — Towards a Full-Lifecycle Agentic Platform

---

## The Three-Axis Architecture

**Not a pipeline. A platform.**

```
  AXIS 1 — LIFECYCLE (when)
  Strategy → Discovery → Design → Build → Readiness → Delivery → Growth → Operations → Sunset

  AXIS 2 — DOMAIN MESH (what expertise — reference pattern)
  DataOps · MLOps · AgentOps · PlatformOps
  ↕ assessed/advised/built/monitored through standard ports ↕

  AXIS 3 — CROSS-CUTTING (what sustains it)
  Knowledge Engineering · Security & Compliance · Documentation · Governance & Change
```

**The conceptual shift:**

- **Lifecycle axis** — *when* things happen; modules are sequential or cyclical, connected by handoff contracts
- **Domain Mesh axis** — *what expertise* is needed; reference pattern for supported organizations; informs future domain-specialized Convoke perimeters
- **Cross-cutting axis** — spans the entire platform; Knowledge Engineering feeds every perimeter; Governance governs the transformation itself

---

## The Governance & Change Perimeter: The Meta-Layer

Among all proposed perimeters, one stands apart:

**A governance, change management, and adoption perimeter** — specifically designed to facilitate the organizational transformation that Convoke's own expansion creates. It is a *meta-perimeter*: it helps organizations adopt the other perimeters.

**Potential capabilities:**

- **Change architecture** — adoption strategies using Kotter, ADKAR, diffusion theory; organizational readiness mapping; phased rollout plans for new perimeters
- **Governance design** — structuring decision rights using Cynefin and DACI; defining where agents operate autonomously vs. where human oversight is required; EU AI Act and ISO 42001 compliance mapping
- **Adoption facilitation** — behavioral design (Fogg, Eyal, Thaler) to maximize perimeter adoption; psychological safety monitoring; nudges and habit loops for agent-augmented workflows

**This perimeter runs from day one — not as an afterthought.**

---

## Priorities and Sequencing

| Wave | Perimeters | Rationale |
|------|-----------|-----------|
| **Wave 0 — Foundations** | Knowledge Engineering | In brownfield, activates first. Extracts the knowledge every other perimeter needs. |
| **Wave 1 — Core Loop** | Delivery · Operations · Security | Bridges Gyre to production. Operationalizes readiness. Elevates security from assessment to discipline. |
| **Wave 2 — Lifecycle Extension** | Strategy · Growth · Documentation | Upstream grounding (strategy). Downstream adoption (growth). Prevents knowledge loss (documentation). |
| **Wave 3 — Full Picture** | Sunset · Governance & Change · Domain Mesh | Full lifecycle closure. The organizational meta-layer. Domain capabilities as demand dictates. |

**Each wave:** Specified via Team Factory workflow · Agents grounded in theoretical foundations · New handoff contracts for adjacent modules

---

## Open Questions: The Research Agenda

1. **Agent-to-agent governance** — How should inter-module handoff contracts be governed *across* teams? Data Mesh federated governance is the starting point.

2. **Emergent behavior at scale** — With 40+ agents across 15+ modules, what guardrails are needed? AgentVerse (Chen et al., 2023) and Sociotechnical Systems offer starting points.

3. **Measuring transformation** — DORA covers delivery. What metrics capture discovery quality, knowledge asset health, adoption success, governance maturity?

4. **Agent autonomy spectrum** — How does an organization safely increase agent delegation over time? What model governs the progression?

5. **Convoke's own governance** — As a three-axis platform, how should the project itself be governed?

6. **Knowledge asset lifecycle** — How do knowledge assets age, decay, and retire? Storey's cognitive debt concept makes this increasingly urgent.

7. **Port interface evolution** — How do domain module interfaces evolve without breaking lifecycle consumers? API semver and consumer-driven contracts may apply.

8. **Mesh observability** — How do we observe the health of the mesh itself? Service mesh observability patterns (Istio, Linkerd) provide technical precedent.

---

<!-- _class: divider -->

# From Vision to Specification

**Each perimeter enters specification via Team Factory workflow.**
**Knowledge Engineering first. Governance from day one.**

---

<!-- _class: refs -->

## References

### Discovery & Design
- Appelo, J. (2022). Innovation Vortex. Happy Melly Express.
- Ries, E. (2011). The Lean Startup. Crown Business.
- Christensen, C. et al. (2016). Competing Against Luck. Harper Business.
- Brown, T. (2009). Change by Design. HarperCollins.
- Nygard, M. (2011). Documenting Architecture Decisions. Cognitect Blog.

### Strategy
- Porter, M.E. (1980). Competitive Strategy. Free Press.
- Kim, W.C. & Mauborgne, R. (2005). Blue Ocean Strategy. HBSP.
- Lafley, A.G. & Martin, R.L. (2013). Playing to Win. HBR Press.
- Rumelt, R.P. (2011). Good Strategy/Bad Strategy. Crown Business.
- Wardley, S. (2018). Wardley Maps. Creative Commons.
- Osterwalder, A. & Pigneur, Y. (2010). Business Model Generation. Wiley.

### Delivery & Operations
- Humble, J. & Farley, D. (2010). Continuous Delivery. Addison-Wesley.
- Forsgren, N. et al. (2018). Accelerate. IT Revolution Press.
- Beyer, B. et al. (2016). Site Reliability Engineering. O'Reilly.
- Beyer, B. et al. (2018). The Site Reliability Workbook. O'Reilly.
- Rosenthal, C. et al. (2020). Chaos Engineering. O'Reilly.
- Hidalgo, A. (2020). Implementing Service Level Objectives. O'Reilly.
- Woods, D.D. (2017). STELLA: Report from the SNAFUcatchers Workshop. Ohio State University.

<!-- _class: refs -->

### Growth
- Bush, W. (2019). Product-Led Growth. ProductLed Library.
- McClure, D. (2007). AARRR! Pirate Metrics for Startups.
- Ellis, S. (2013). Finding Your North Star Metric. Growth Hackers.
- Traynor, D. et al. (2016). Intercom on Jobs-to-be-Done. Intercom Books.
- Kohavi, R. et al. (2020). Trustworthy Online Controlled Experiments. Cambridge University Press.

### Security
- Shostack, A. (2014). Threat Modeling: Designing for Security. Wiley.
- OWASP Foundation. (2021). DevSecOps Guideline. owasp.org.
- NTIA. (2021). Minimum Elements for a Software Bill of Materials (SBOM). U.S. Dept. of Commerce.
- European Union. (2024). Regulation (EU) 2024/1689 on Artificial Intelligence.
- NIST. (2023). AI Risk Management Framework.
- ISO/IEC. (2023). ISO/IEC 42001 AI Management System Standard.

### Documentation & Knowledge Engineering
- Procida, D. (2017–ongoing). Diátaxis Framework. diataxis.fr.
- Gentle, A. (2022). Docs Like Code (3rd ed.). Just Write Click.
- Nonaka, I. & Takeuchi, H. (1995). The Knowledge-Creating Company. Oxford University Press.
- Polanyi, M. (1966). The Tacit Dimension. University of Chicago Press.
- Cooke, N.J. (1994). Varieties of Knowledge Elicitation Techniques. IJHCS, 41(6).
- Jansen, A. & Bosch, J. (2005). Software Architecture as a Set of Architectural Design Decisions. WICSA.
- Kagdi, H. et al. (2007). A Survey and Taxonomy of Approaches for Mining Software Repositories. JSME, 19(2).
- Microsoft Research. (2024). GraphRAG. microsoft.github.io/graphrag.
- Storey, M. (2026). How Generative and Agentic AI Shift Concern from Technical Debt to Cognitive Debt.
- Davenport, T.H. & Prusak, L. (1998). Working Knowledge. HBSP.
- Boisot, M.H. (1998). Knowledge Assets. Oxford University Press.

<!-- _class: refs -->

### Domain Mesh
- Dehghani, Z. (2022). Data Mesh. O'Reilly.
- Broda, B. (2025). Agentic Mesh. Medium / Data Science.
- Cockburn, A. (2005, 2024). Hexagonal Architecture Explained.
- Evans, E. (2003). Domain-Driven Design. Addison-Wesley.
- Vernon, V. (2013). Implementing Domain-Driven Design. Addison-Wesley.
- Martin, R.C. (2017). Clean Architecture. Prentice Hall.
- Huyen, C. (2022). Designing Machine Learning Systems. O'Reilly.
- Huyen, C. (2025). AI Engineering. O'Reilly.
- Sculley, D. et al. (2015). Hidden Technical Debt in Machine Learning Systems. NeurIPS 2015.
- Anthropic. (2024). Model Context Protocol (MCP). modelcontextprotocol.io.

### Organizational Transformation
- Kotter, J. (1996, 2014). Leading Change / Accelerate. HBSP.
- Lewin, K. (1947). Frontiers in Group Dynamics. Human Relations, 1(1).
- Peters, T. & Waterman, R. (1982). In Search of Excellence. Harper & Row.
- Bridges, W. & Bridges, S. (1991). Managing Transitions. Hachette.
- Skelton, M. & Pais, M. (2019, 2024). Team Topologies. IT Revolution Press.
- Appelo, J. (2021–ongoing). The unFIX Model. unfix.com.
- Trist, E. & Bamforth, K. (1951). Some Social and Psychological Consequences of the Longwall Method. Tavistock Institute.
- Mollick, E. (2024). Co-Intelligence. Penguin Random House.
- Brynjolfsson, E. & Li, D. (2023–2024). Generative AI at Work. NBER Working Paper.
- McKinsey & Company. (2025–2026). The Agentic Organization.
- Google Cloud. (2026). AI Agent Trends 2026.
- Snowden, D. & Boone, M. (2007). A Leader's Framework for Decision Making. HBR.
- Teece, D. et al. (1997). Dynamic Capabilities and Strategic Management. SMJ.
- Edmondson, A. (1999). Psychological Safety and Learning Behavior in Work Teams. ASQ, 44(2).
- Rogers, E. (2003). Diffusion of Innovations (5th ed.). Free Press.
- Moore, G. (2014). Crossing the Chasm (3rd ed.). HarperCollins.
- Fogg, B.J. (2019). Tiny Habits. Houghton Mifflin Harcourt.
- Thaler, R. & Sunstein, C. (2008). Nudge. Yale University Press.

### Sunset & Technical Debt
- Cunningham, W. (1992). The WyCash Portfolio Management System. OOPSLA 1992.
- Tornhill, A. (2018). Software Design X-Rays. Pragmatic Programmers.
- Fowler, M. (2004). Strangler Fig Application. martinfowler.com.
- Fowler, M. (2018). Refactoring (2nd ed.). Addison-Wesley.
