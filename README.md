# E-Commerce Funnel Analysis & Revenue Impact

> 885K events. 407K users. 5 months. The problem isn't demand — it's decision friction at add-to-cart.

## Overview

End-to-end product analytics on a real e-commerce dataset — mapping the full conversion funnel, identifying where users drop off, and quantifying the revenue opportunity from fixing it.

**Dataset:** E-Commerce Events Data · 885K events · 407K users · Sep 2020 – Feb 2021

## Key Results

| Funnel Stage | Sessions | Conversion Rate |
|---|---|---|
| View | 490,000 | — |
| Cart | 41,650 | 8.5% of views |
| Purchase | 24,574 | 59% of carts |

- **91.5% drop at View → Cart** — the single biggest lever
- Cart → Purchase rate of 59% is structurally healthy — not the problem
- **~15% revenue uplift** achievable through moderate cart rate improvement

## Category Analysis

| Category | Cart Rate | Purchase Rate |
|---|---|---|
| Computers | 12.7% | 63% |
| Kids | 11.2% | 65% |
| Electronics | 6.7% | 58% |
| Furniture | 4.3% | 55% |

Cart rate varies from 4% to 13% across categories. Purchase rate stays in a tight 55–65% band — confirming this is a **discovery and decision problem, not a checkout problem.**

## Brand vs Price Analysis (Electronics)

| Brand | Avg Price | Cart Rate |
|---|---|---|
| Sirius | $23 | 10.2% |
| Samsung | $72 | 4.3% |
| LG | $218 | 0.9% |
| Sony | $313 | 0.7% |

Clear inverse relationship: higher price → more comparison browsing → lower cart rate.

## Revenue Uplift Scenarios

| Scenario | Gap Closure | Revenue Uplift |
|---|---|---|
| Conservative | 30% | ~9.2% |
| Moderate | 50% | ~15.3% |
| Aggressive | 100% | ~30.6% |

## Tech Stack

- **Python** — Pandas, NumPy, Plotly
- **SQL** — session-based funnel construction
- Category, brand, and temporal segmentation analysis

## Project Structure
├── ECommerce_Data.ipynb    # Main notebook
├── events.csv   # Dataset
└── README.md

## Key Recommendations

1. Fix the Unknown category metadata — 27% of traffic is unclassified
2. Add comparison tools for Electronics — premium brand users are browsing, not committing
3. Use pricing cues for high-price products — reduce hesitation at add-to-cart
4. Promote high-converting sub-categories — Telephones convert at ~7% within Electronics

## Live Portfolio

View the full interactive case study: [mandiv-analytics.netlify.app/project-ecomm.html](https://mandiv-analytics.netlify.app/project-ecomm.html)
