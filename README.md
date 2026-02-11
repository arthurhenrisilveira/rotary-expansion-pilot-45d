# Rotary Expansion Pilot (Brazil) — 45-day plan

## Context
Brazil has ~2,500 Rotary clubs and ~52k members, with a strategic goal of reaching 60k members by Jan/2027.

## Problem
"Brazil still has many cities without a Rotary Club."  
Where should we prioritize expansion to maximize impact and execution feasibility?

## Approach
**Act 1 — Data foundation (Python):**
- Consolidated a municipal-level dataset combining population (IBGE) + Rotary footprint by city/district
- Standardized municipality identifiers and produced a clean output for BI analysis
- Built key coverage metrics

**Act 2 — Decision layer (Power BI):**
- District overview (coverage gap)
- Zero-club cities ranked by population (greenfield prioritization)

## Key metrics
- **Population**
- **Members**
- **Clubs**
- **Hab per Member** (population / members)
- **Clubs per 100k**
- **Rotarians per 1k**

## Pilot decision
Pilot districts: **D4571, D4751, D4440**  
Within each district, we prioritized **Top 10 zero-club municipalities by population** (anchor cities) to maximize near-term potential.

## 45-day execution plan
- **Days 1–7 (Setup):** validate target list with district leaders, define owners, set weekly cadence
- **Days 8–30 (Execution):** lead generation + meetings in target cities (pipeline build)
- **Days 31–45 (Conversion):** confirm founders and advance to “club formation” pipeline (pre-club / charter readiness)

## Measurement
**Leading indicators (weekly):**
- # target cities activated
- # leads generated
- # meetings held
- # founders confirmed

**Lagging indicators (by day 45 / following cycle):**
- # clubs in formation pipeline
- # new members added (when applicable)

## Artifacts (in progress)
- Brazil overview (Power BI) (zero-club top cities): `pdfs/BR_overview_zero_club_top10.pdf`
- Pilot districts (Power BI) (Top 10 zero-club by population):
  - D4571: `pdfs/D4571_zero_club_top10.pdf`
  - D4751: `pdfs/D4751_zero_club_top10.pdf`
  - D4440: `pdfs/D4440_zero_club_top10.pdf`

- Monitoring template (xlsx) — TBD
- Data pipeline notebook/script — TBD


## Notes on data privacy
This repository does not include sensitive/raw Rotary data. Samples are provided as schemas only.
