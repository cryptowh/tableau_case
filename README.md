# Retail Executive Dashboard — Prototype

Static HTML/CSS/SVG prototype for the Aldar BI case study. Mirrors the four required sections of the case brief:

1. Executive Summary — KPI tiles vs previous period
2. Sales & Performance Analysis — trend, departments, stores, traffic by hour
3. Customer Insights — income × age, household composition, high-value HH deciles
4. Product & Basket Analysis — top commodities, basket size, items per basket

## Data

Numbers are anchored to the EDA report where the source provided breakdowns (KPIs, departments, top stores, top commodities, hour-of-day, HH composition Sales/HH, basket quartiles). Cells where the source provided only marginals (income × age matrix, brand split per department, day-of-week × hour, LTV deciles) are interpolated to be directionally correct.

## Run locally

```bash
open index.html
```

Single static file; no build, no dependencies.

## Deploy

Auto-deployed via Vercel from the `main` branch.
