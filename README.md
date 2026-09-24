# Superstore Returns Analysis

**[View the live Tableau Story on Tableau Public →](https://public.tableau.com/views/S5Project-StorytellingwithData-RICE3v2_2/Story2)**

**[Watch the 4-minute presentation walkthrough →](https://www.loom.com/share/07b7fb4384264c61a624148723168403)**

![Dashboard design process — pen-and-paper mockup](docs/dashboard-mockup-sketch-1.jpg)

## Business Question

What's causing the high number of returned orders at the Superstore, and how can the business reduce it? Built as an analysis for a CEO-level audience.

## Tools & Skills

- **Tableau** — calculated fields (converting a raw Yes/null "Returned" field into a usable return-rate metric), joins, maps, and a multi-page Tableau Story for presenting findings in sequence
- **Dashboard design** — started from pen-and-paper mock-ups (`docs/dashboard-mockup-sketch-1.jpg` through `-3.jpg`) before building in Tableau, to plan layout around the findings rather than the data
- **Root-cause analysis** — tested returns against sales, product category, customer order history, geography, and season to isolate real drivers vs. noise
- **Presenting to a non-technical audience** — built the walkthrough for a CEO, not a data team

## Analysis Approach

Six views were built to test different possible causes of returns:
1. Sales vs. returns correlation, by product subcategory
2. Return rate by product category
3. Return rate by repeat customers only (single-order customers filtered out)
4. Return rate by geography (map)
5. Return rate by time (seasonality)
6. Composite views combining multiple factors at once

## Data

Tableau's public "Superstore" sample dataset (Orders + Returns tables, left-joined) — a widely used practice dataset, not real business data.

## Documentation

- [`docs/rubric.pdf`](docs/rubric.pdf) — the grading rubric this project was built against
- [`docs/dashboard-mockup-sketch-1.jpg`](docs/dashboard-mockup-sketch-1.jpg), [`-2`](docs/dashboard-mockup-sketch-2.jpg), [`-3`](docs/dashboard-mockup-sketch-3.jpg) — hand-drawn dashboard mock-ups from the design phase
- [`tableau/superstore-returns-analysis.twbx`](tableau/superstore-returns-analysis.twbx) — packaged Tableau workbook (opens directly in [Tableau Desktop or Tableau Public](https://www.tableau.com/products/public/download), data included)
