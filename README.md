# GM Tierless System

**Live:** https://rethink-gm-tierless-system.vercel.app

A clickable DCO/CMP command center for the GM × Rethink advertising pitch — a single integrated marketing calendar fed by Smartsheet, Figma, Clinch, Celtra and imported PDF briefs, with high-level and drilled-down views across roles.

## Features

- **Overview** — role switcher (Executive / Account / Producer) reshapes the dashboard; portfolio health, live connected-sources rail, and an alerts feed.
- **Integrated marketing calendar** — every GM campaign × week as a gantt, status-colored flight bars, division/source dots, a live "Today" line, and division filters.
- **Drill-down (4 levels)** — Portfolio → Campaign (flights, Smartsheet tasks, activity) → Flight → the Clinch DCO fan-out (1 Figma concept → 12 variants → 90 Celtra sizes).
- **Workflow** — Human / Craft / Delivery swimlanes from the GM MAS brief through Tier 1 / Tier 2 / Tier Social, with a tap-to-open role panel.
- **PDF brief import** — parses a media plan and drops a new campaign onto the calendar.

## Running locally

It's a single self-contained `index.html` with no build step or runtime dependencies. Either open the file directly, or serve the folder:

```bash
npx serve .
```

## Tech

Plain HTML/CSS/JS, Archivo type. A small vanilla render loop drives state; all UI is reproduced from the original design prototype.
