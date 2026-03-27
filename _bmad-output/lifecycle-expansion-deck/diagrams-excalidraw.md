# Lifecycle Expansion Vision — Excalidraw Diagram Specifications
**Companion file to:** exec-deck.md · full-deck.md · slides-outline.md
**Usage:** Open Excalidraw (excalidraw.com or VS Code extension), create one frame per diagram below.

---

## Diagram 1: Coverage Map

**Used in:** Slide 3 (exec) · Slide 15 (full depth)
**Frame size:** 1200 × 280px
**Purpose:** Show current Convoke lifecycle coverage vs. gaps at a glance.

### Layout

A horizontal bar divided into 9 equal segments. Two visual states:
- **Covered segments** (bright fill `#3730A3`, white text, solid border)
- **Gap segments** (light fill `#F1F5F9`, grey text `#94A3B8`, dashed border `#CBD5E1`)

```
┌──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┬──────────┐
│ STRATEGY │DISCOVERY │  DESIGN  │  BUILD   │READINESS │ DELIVERY │  GROWTH  │OPERATIONS│  SUNSET  │
│          │          │          │          │          │          │          │          │          │
│   GAP    │  VORTEX  │  WDS +   │  BMM +   │  GYRE    │   GAP    │   GAP    │   GAP    │   GAP    │
│  (dashed)│  7 agents│   BMM    │   TEA    │ 4 agents │  (dashed)│  (dashed)│  (dashed)│  (dashed)│
└──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┴──────────┘
```

Below the bar — three horizontal bands labeled:
- `KNOWLEDGE ENGINEERING` — dashed border, full width, `#FEF3C7` fill, amber text
- `DOCUMENTATION` — same style
- `GOVERNANCE & CHANGE MANAGEMENT` — same style

### Excalidraw Element Properties

**Covered segment rectangles:**
- `backgroundColor: "#3730A3"` · `strokeColor: "#3730A3"` · `fillStyle: "solid"`
- Text: `fontFamily: 2` · `fontSize: 14` · `textAlign: center` · `fontColor: "#FFFFFF"`

**Gap segment rectangles:**
- `backgroundColor: "#F1F5F9"` · `strokeColor: "#CBD5E1"` · `strokeStyle: "dashed"` · `fillStyle: "solid"`
- Text: `fontColor: "#94A3B8"`

**Cross-cutting bands:**
- `backgroundColor: "#FEF9C3"` · `strokeColor: "#FCD34D"` · `strokeStyle: "dashed"` · `fillStyle: "solid"`
- Text: `fontColor: "#92400E"` · `fontSize: 12`

---

## Diagram 2: Three-Axis Architecture

**Used in:** Slide 5 (exec) · Full depth synthesis
**Frame size:** 1200 × 700px
**Purpose:** Visualize the three-axis platform concept — Lifecycle, Domain Mesh, Cross-cutting.

### Layout

Three distinct horizontal layers stacked vertically, connected by vertical lines.

**LAYER A — AXIS 1: LIFECYCLE** (top, full width)
A left-to-right horizontal flow with arrows:
```
Strategy → Discovery → Design → Build → Readiness → Delivery → Growth → Operations → Sunset
```
Boxes: `#3730A3` fill for covered (Discovery, Design, Build, Readiness), `#E0E7FF` for gaps, `#C7D2FE` border.

**LAYER B — AXIS 2: DOMAIN MESH** (middle, four equal columns)
```
┌───────────┐  ┌───────────┐  ┌───────────┐  ┌─────────────┐
│  DataOps  │  │   MLOps   │  │ AgentOps  │  │ PlatformOps │
│  Domain   │  │  Domain   │  │  Domain   │  │   Domain    │
│           │  │           │  │           │  │             │
│  assess   │  │  assess   │  │  assess   │  │   assess    │
│  build    │  │  build    │  │  build    │  │   build     │
│  monitor  │  │  monitor  │  │  monitor  │  │   monitor   │
│  advise   │  │  advise   │  │  advise   │  │   advise    │
└───────────┘  └───────────┘  └───────────┘  └─────────────┘
```
Boxes: `#EEF2FF` fill · `#6366F1` stroke · `#4338CA` text
Label above: `MESH INFRASTRUCTURE (Discovery · Routing · Capability Registry · Governance)` — full width, `#1E1B4B` fill, white text.

**LAYER C — AXIS 3: CROSS-CUTTING** (bottom, four equal segments)
```
┌─────────────────────┐  ┌──────────────────┐  ┌───────────────┐  ┌─────────────────────┐
│ Knowledge Engineering│  │ Security &       │  │ Documentation │  │ Governance & Change │
│                      │  │ Compliance       │  │               │  │                     │
└─────────────────────┘  └──────────────────┘  └───────────────┘  └─────────────────────┘
```
Boxes: `#FEF9C3` fill · `#FCD34D` stroke · `#78350F` text

**Connecting elements:**
- Vertical arrows from Layer A down into Layer B (bidirectional `↕`)
- Vertical arrows from Layer B down into Layer C (bidirectional `↕`)
- Layer C has a leftward arrow pointing back up to Layer A (cross-cutting feeds back)

**Labels (right side, rotated 90°):**
- "AXIS 1 — LIFECYCLE" (aligned with Layer A)
- "AXIS 2 — DOMAIN MESH" (aligned with Layer B)
- "AXIS 3 — CROSS-CUTTING" (aligned with Layer C)

---

## Diagram 3: Knowledge Engineering Flow

**Used in:** Slide 6 (exec) · Slide 21 (full depth)
**Frame size:** 1100 × 420px
**Purpose:** Show the flow from knowledge sources through extraction/elicitation/curation to consumers.

### Layout

Three vertical columns connected by arrows.

**COLUMN 1 — KNOWLEDGE SOURCES** (left)
Five stacked boxes:
- Codebases
- Existing docs
- Team expertise
- Decision history
- Incident reports

Boxes: `#F1F5F9` fill · `#94A3B8` stroke · `#475569` text · `fontSize: 13`

**COLUMN 2 — KNOWLEDGE ENGINEERING** (center, taller, dominant)
One large box containing three inner rows:
- Extract (top row)
- Refine (middle row)
- Expose (bottom row)

Box: `#3730A3` fill · white text · bold label "KNOWLEDGE ENGINEERING" · `fontSize: 16`
Inner rows: `#4338CA` fill · white text

**COLUMN 3 — KNOWLEDGE CONSUMERS** (right)
Five stacked boxes:
- Discovery (Vortex)
- Design & Build
- Readiness (Gyre)
- Any perimeter
- Human teams

Boxes: `#EEF2FF` fill · `#6366F1` stroke · `#3730A3` text

**Arrows:**
- Source boxes → Column 2: labeled `extract →` (solid) or `elicit →` (dashed) or `mine →` (dotted)
- Column 2 → Consumer boxes: all labeled `expose →` (solid, `#3730A3` color)
- A circular arrow on Column 2 labeled `refine · validate · structure`

---

## Diagram 4: Domain Mesh Pattern (Detailed)

**Used in:** Slide 23 (full depth)
**Frame size:** 1200 × 600px
**Purpose:** Show the hexagonal port interface pattern across domain modules.

### Layout

**TOP BAND:** Mesh Infrastructure Layer
Full-width rectangle: `#1E1B4B` fill · white text · `fontSize: 14`
Label: `MESH INFRASTRUCTURE LAYER — Discovery · Routing · Capability Registry · Governance Contracts`

**MIDDLE SECTION:** Four domain columns, equal width
Each column is a box with:
- Header: domain name (e.g., `DataOps Domain`) — `#3730A3` fill · white text
- Body: four port rows — `assess / build / monitor / advise` — `#EEF2FF` fill · `#3730A3` text

Vertical connectors from Mesh band down into each domain box.

**BOTTOM BAND:** Lifecycle Perimeters (consumers)
Full-width rectangle: `#E0E7FF` fill · `#3730A3` text
Label: `LIFECYCLE PERIMETERS — Strategy · Discovery · Design · Build · Readiness · Delivery · ...`

Vertical connectors from each domain box down into the bottom band (bidirectional arrows `↕`).

**Right margin note:**
Small annotation box: `"Gyre can call MLOps.assess(codebase) without understanding ML internals"` — italic, `#6B7280` text, light border.

---

## Diagram 5: Roadmap Waves

**Used in:** Slide 9 (exec) · Slide roadmap (full depth)
**Frame size:** 1200 × 480px
**Purpose:** Show the four-wave expansion roadmap as building blocks.

### Layout

Four horizontal rows (waves), each containing labeled perimeter boxes.

**WAVE 0 — Foundation** (row 1, darkest)
One box spanning 1/4 width: `Knowledge Engineering`
Fill: `#1E1B4B` · white text · `fontSize: 15` · bold
Right label: `"Enables everything else. Activate first."`

**WAVE 1 — Core Loop** (row 2)
Three equal boxes: `Delivery` · `Operations` · `Security`
Fill: `#3730A3` · white text
Right label: `"Bridge 'ready' to 'live' to 'stable'"`

**WAVE 2 — Extension** (row 3)
Three equal boxes: `Strategy` · `Growth` · `Documentation`
Fill: `#6366F1` · white text
Right label: `"Upstream vision. Downstream adoption."`

**WAVE 3 — Full Picture** (row 4, lightest)
Three equal boxes: `Sunset` · `Governance & Change` · `Domain Mesh`
Fill: `#A5B4FC` · `#1E1B4B` text
Right label: `"Complete lifecycle closure."`

**Vertical connecting arrow** on far left, pointing downward through all four waves.
Label: `"Build sequence →"` rotated 90°, `#3730A3` color.

**Wave labels** on far left, one per row:
- `Wave 0` · `Wave 1` · `Wave 2` · `Wave 3`
Bold, `#1A1A2E` text.

---

## Diagram 6: Organizational Transformation — Human-AI Collaboration Models

**Used in:** Slide 8 (exec) · Slide 25 (full depth)
**Frame size:** 1100 × 340px
**Purpose:** Show the three collaboration models with their outcomes.

### Layout

Three equal columns with a connecting spectrum arrow beneath.

**COLUMN 1 — Centaur**
Box with header: `CENTAUR`
Icon suggestion: two distinct shapes side by side (human + agent)
Body: `Clear human/agent task division`
Outcome badge: `Domain expertise deepens` — `#D1FAE5` fill · `#065F46` text

**COLUMN 2 — Cyborg**
Box with header: `CYBORG`
Icon suggestion: overlapping/merged shapes
Body: `Fluid, integrated task blending`
Outcome badge: `AI-native skills develop` — `#EEF2FF` fill · `#3730A3` text

**COLUMN 3 — Self-Automator**
Box with header: `SELF-AUTOMATOR`
Icon suggestion: one shape alone, arrow pointing away
Body: `Delegation with minimal engagement`
Outcome badge: `⚠ Autonomy risk` — `#FEF3C7` fill · `#92400E` text

**Bottom:** A horizontal spectrum arrow from left to right
Label: `← increasing AI delegation →`
Color gradient: `#D1FAE5` → `#EEF2FF` → `#FEF3C7`

**Source annotation:** `Harvard Business School / Wharton · Randazzo, Lifshitz-Assaf, Mollick et al., 2024` — small, `#9CA3AF` text, bottom right.

---

## Excalidraw Import Notes

1. All diagrams are designed for **Excalidraw's frame feature** — create a named frame for each diagram (Diagram 1–6).
2. Recommended font: `Nunito` (Excalidraw's handwriting font) for informal/exploratory feel, OR `Inter/Helvetica` for polished executive presentation.
3. Color palette summary:
   - **Primary:** `#3730A3` (indigo-700)
   - **Light primary:** `#EEF2FF` (indigo-50)
   - **Dark:** `#1E1B4B` (indigo-950)
   - **Accent:** `#6366F1` (indigo-500)
   - **Gap/neutral:** `#F1F5F9` (slate-100)
   - **Warning:** `#FEF3C7` (amber-100)
   - **Success:** `#D1FAE5` (emerald-100)
4. Export each frame as **SVG** for embedding in Google Slides (scales without pixelation).
5. Export the full canvas as a single `.excalidraw` file for version control.
