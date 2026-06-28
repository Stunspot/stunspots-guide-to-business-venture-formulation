# How to Use This Canon

*Stunspot's Guide to Business Venture Formulation* is written as model-facing knowledge substrate first and human reference second.

That means the best use is usually not casual reading from the GitHub UI. The best use is to load the right slice of the corpus into an AI workspace, RAG system, long-context session, project knowledge base, or local search tool and use it to ground venture reasoning.

---

## Recommended Default

For most AI/RAG systems, start with the **compiled packs** in `knowledge-packs/compiled-packs/`.

They provide three coherent files:

1. **Vol. 1 A-E — Foundational Reality Layers**: ontology, epistemology, market/customer reality, venture stages.
2. **Vol. 2 F-K — Core Operating Domains**: offer, business model, GTM, operating model, capital, organization.
3. **Vol. 3 L-N — Constraint, Legitimacy, and Control Layers**: governance, diagnostics, execution control.

This keeps upload count low while preserving the canon's conceptual architecture.

---

## Choose the Right Format

| Format | Path | Best For | Tradeoff |
|---|---|---|---|
| Source reports | `knowledge-packs/by-report/` | Precise retrieval, selective upload, citation, editing, and report-level indexing. | More files to manage. |
| Compiled packs | `knowledge-packs/compiled-packs/` | Recommended default for AI Projects, RAG systems, and long-context workspaces. | Less granular than source reports. |
| Omnibus | `knowledge-packs/omnibus/` | One-file import, local archive, broad synthesis, and robust long-context tools. | Large single file; weaker retrieval boundaries in some tools. |

---

## Human Reader Workflow

Use the canon as a diagnostic field manual rather than a motivational startup book. Enter through the layer where your current uncertainty lives.

### To clarify what you are building

Read:

- A. Venture Ontology and Enterprise Reality
- B. Operational Epistemology and Decision Logic
- D. Customer Reality, Demand Formation, and Opportunity Intelligence

Ask:

- What kind of venture object is this: product, service, firm, platform, coordination system, institutional actor, or some unstable hybrid?
- Which assumptions are fragile, important, observable, and reversible?
- What evidence is revealed behavior rather than stated preference?

### To design the commercial system

Read:

- F. Offer Architecture, Positioning, and Category Design
- G. Business Model Architecture and Economic Capture
- H. Go-to-Market Architecture and Commercial Motion
- I. Operating Model, Delivery Systems, and Capability Design

Ask:

- What comparison frame will customers use by default?
- Can the offer capture enough value to survive?
- Does the GTM motion fit the price point, buyer risk, channel structure, and sales complexity?
- Can the operating model actually deliver what positioning promises?

### To evaluate institutional viability

Read:

- C. Market Structure, Power, and Strategic Environment
- J. Capital Strategy, Resource Assembly, and Strategic Resourcing
- K. Organizational Design, Stakeholder Alignment, and Decision Rights
- L. Governance, Legitimacy, and Institutional Constraint

Ask:

- What market structures, incumbents, regulations, or social permissions constrain the venture?
- What capital logic is appropriate for the venture's risk, timing, and control needs?
- Who has decision rights, and how are conflicts resolved?
- What legitimacy debt is accumulating before anyone has named it?

### To diagnose and steer execution

Read:

- M. Venture Diagnostics, Failure Modes, and Corrective Intervention
- N. Execution Control, Measurement Systems, and Institutional Artifacts

Ask:

- What failure mode best explains the current symptoms?
- Is the venture observing itself with the right signals, thresholds, and review cadence?
- Which metric is ornamental, and which one actually creates steering leverage?
- What artifact, meeting rhythm, dashboard, or decision rule must exist for the venture to become manageable?

---

## AI/RAG Workflow

When using this canon inside an AI system, provide the model with both the corpus and an explicit job.

### Basic prompt pattern

```text
Use Stunspot's Guide to Business Venture Formulation as the governing knowledge substrate for this task.

Treat the canon as model-facing doctrine, not generic business advice. Ground your answer in its venture-architecture concepts: venture ontology, assumption architecture, customer reality, value creation/capture, market structure, offer architecture, GTM motion, operating model, capital strategy, organization, governance, diagnostics, and execution control.

Task: [describe the venture-analysis task]
Context: [paste venture notes, pitch, offer, model, customer evidence, constraints, or current problem]
Output: [request the format: diagnosis, memo, roadmap, risk table, rewrite, scorecard, etc.]
```

### Good AI tasks for this corpus

- critique a venture concept for conceptual incoherence
- decompose a pitch into assumptions and validation priorities
- evaluate customer evidence quality and identify false validation
- map market structure and competitive alternatives
- improve positioning and category framing
- audit business-model logic and value-capture failure risk
- diagnose GTM/channel-model fit
- review operating-model feasibility
- align capital strategy to stage and risk
- surface governance, legitimacy, compliance, or stakeholder risks
- create venture scorecards, review cadences, and execution-control artifacts

### Retrieval guidance

For precise RAG indexing, preserve these metadata fields per chunk whenever your system supports them:

- `canon_title`: `Stunspot's Guide to Business Venture Formulation`
- `report_code`: `A` through `N`
- `report_title`
- `volume`: `Vol. 1 A-E`, `Vol. 2 F-K`, or `Vol. 3 L-N`
- `source_path`
- `section_heading`

Prefer chunks that preserve tables, diagnostic checklists, and adjacent explanatory paragraphs together. Splitting a table from its interpretive paragraph makes the model dumber in a very avoidable way. Rude to everyone involved.

---

## What Not To Do

Do not treat the canon as a source of generic startup slogans. Do not ask an AI to summarize the whole thing unless your goal is orientation. The value is in applying the doctrine to a specific venture, decision, artifact, or failure mode.

Do not upload both compiled packs and the omnibus into the same small knowledge base unless your retrieval system deduplicates well. That creates redundant retrieval and can dilute citation quality.

Do not treat the reports as legal, financial, or investment advice. They are a knowledge canon for reasoning, design, diagnosis, and structured analysis. High-impact decisions still require qualified professional review.
