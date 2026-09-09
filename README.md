# Seasonal Agriculture Performance Analysis

**VOIS AICTE Batch1 2026-2027 — Major Project**
Track: AI-Assisted Full Stack Web Development (Data Analytics Major Project)
Student: Rishav

## Overview

This project analyzes seasonal agricultural performance using a 4,000-record dataset spanning 8 Indian states, 8 crops, 3 seasons (Kharif, Rabi, Zaid) and 4 irrigation methods. It investigates how environmental conditions, resource usage, yield and profitability change across seasons, and translates the findings into data-driven recommendations for seasonal agricultural planning.

## Objective

- Explore and understand the dataset
- Clean and prepare the data for analysis (missing values, outliers)
- Examine how agricultural performance varies across seasons
- Identify seasonal patterns, trends and relationships between variables
- Apply statistical testing (ANOVA, Pearson correlation) and visualization
- Develop evidence-based conclusions and recommendations

## Key Findings

- **Yield does not differ significantly across seasons** (ANOVA p = 0.28)
- **Profit differs significantly by season** (ANOVA p < 0.001) — Kharif is most profitable, Zaid the least
- **Rainfed and Drip irrigation are the most water-efficient** methods across all seasons; Flood is the least efficient
- Yield correlates only weakly with rainfall or fertilizer alone — no single input drives yield in isolation
- Sugarcane is the most profitable crop in every season, though with a higher water/cost footprint
- Disease/pest risk is highest in Kharif, consistent with its higher humidity and rainfall

## Repository Contents

| File | Description |
|---|---|
| `Seasonal_Agriculture_Performance_Analysis.ipynb` | Full analysis notebook — cleaning, EDA, statistical tests, visualizations, insights |
| `seasonal_agriculture_performance_dataset.csv` | Raw dataset |
| `seasonal_agriculture_cleaned_data.csv` | Cleaned dataset used for analysis |
| `VOIS_Major_Project_Seasonal_Agriculture_Performance_Analysis.pptx` | Submission presentation |

## How to Run

1. Open [Google Colab](https://colab.research.google.com).
2. File → Open notebook → **GitHub** tab → paste this repo's URL, or upload `Seasonal_Agriculture_Performance_Analysis.ipynb` directly.
3. When prompted, upload `seasonal_agriculture_performance_dataset.csv` (or use the file-upload cell at the top of the notebook).
4. Run all cells (Runtime → Run all).

### Requirements

The notebook uses standard libraries pre-installed in Colab: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`.

## Tools & Technology

Google Colab · Python 3 · Pandas & NumPy · Matplotlib & Seaborn · SciPy (stats)
