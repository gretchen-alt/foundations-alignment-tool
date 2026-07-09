# ROSEI Foundation Alignment Tool
**Ralph O'Connor Sustainable Energy Institute · Johns Hopkins University**

A prototype researcher-to-foundation matching tool built for ROSEI business development.

🔗 **[Open the tool](https://gretchen-alt.github.io/foundations-alignment-tool/)**

---

## What this is

An interactive alignment tool that matches ROSEI's 83 researchers to philanthropic foundations based on research pillar, theory of change, and policy angle. Three views:

- **Researcher → Foundations** — select any researcher and see ranked foundation matches with alignment scores
- **Foundation → Researchers** — select any foundation and see which ROSEI researchers are the strongest fits
- **Alignment matrix** — a full dot-grid view of Core and Associate faculty across all foundations, filterable by theory of change and pillar

## What's in it

- 83 researchers across Core, Associate, and Affiliate tiers
- School, department, research pillars (6), theory of change, and funder-facing policy angle for every researcher
- 12 foundations with tier placement, grant range, theory of change, and priority pillars
- Alignment scoring based on pillar overlap, theory of change fit, and policy angle matching

## What's not in it yet (internal data needed)

- Active government and corporate grants by PI — needed to power fund stacking alerts
- Foundation engagement appetite — who is ready to talk to a funder
- Foundation relationship status and program officer contacts — held by the Foundations team
- Real-time grant data — pending integration with WSE Research Intelligence

## Status

**Prototype · June 2026**
This is a static proof-of-concept. All data is embedded in the HTML file. It does not connect to a live database. The next step is integration with WSE Research Intelligence (Chad Restrick) to enable live grant data and active matching.

## How to update the data

The researcher data lives in `ROSEI_Researcher_Foundation_Alignment_DB.xlsx`. When the database is updated, a new version of `index.html` can be generated and uploaded here to refresh the tool.

---

*ROSEI Business Development · Johns Hopkins Minds. Research to Real-world.*
