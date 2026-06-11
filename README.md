# GM Tierless System

**Live:** https://rethink-gm-tierless-system.vercel.app

A clickable command center for the GM Canada × Rethink **tierless T1+T2 agency model** — pairing the pitch narrative (delivery model, workflow, staffing, roadmaps) with a live, interactive marketing-ops demo. Built in a single light "enterprise SaaS" layout (Archivo, cyan/black).

## Sections (left rail)

- **Delivery Model** — the Tierless Workflow T1→T2 landing: hero, key stats, the 8-phase loop, and the Legal/Finance pod.
- **Tierless Workflow** — two views via a toggle: a **Schematic** (the two-track T1 national / T2 regional production flow, brief → DAM merge → social → QA → delivery → insights loop, with the full tech stack) and a **Detail grid** (8-phase × 5-function matrix with Human / Craft / Delivery / Tech layer toggles, tool pills, BA moments, and the 50.5-FTE footer).
- **Staffing Plan** — all 65 roles across 8 departments with location/type/hours/FTE, FTE-by-brand, and totals (97,020 GM hrs · 132,000 all-in).
- **Roadmap** — 90-Day / 6-Month / 12-Month transition plans as phase × track milestone grids with gates, critical path, and the Year-1 scorecard.
- **Live Example** — the interactive DCO/CMP dashboard: role switcher (Exec / Account / Producer), portfolio health, live connected-sources rail, and an alerts feed.
- **Calendar (IMC)** — framed as the **Integrated Messaging Calendar** (single source of truth): Airtable/Opal context cards, owner/operator meta, and a "Powered by" rail above the gantt. Every GM campaign × week with drill-down: Campaign (flights, Smartsheet tasks, activity) → Flight → the Clinch DCO fan-out (1 Figma concept → 12 variants → 90 Celtra sizes). Includes the PDF-brief import flow.

Pitch data is ported faithfully from the GM Canada T1+T2 deck. Marked **Confidential**.

## Running locally

It's a single self-contained `index.html` with no build step or runtime dependencies. Either open the file directly, or serve the folder:

```bash
npx serve .
```

## Tech

Plain HTML/CSS/JS, Archivo type, no build step or runtime dependencies. A small vanilla render loop drives state via event delegation.
