# MSA 2026 Phase 2 — Data Science: Analysis and Preprocessing

This repository contains my submission for **Part 1 (Analysis and Preprocessing)**
of the MSA 2026 Phase 2 Data Science stream.

## Overview

The goal of this part is to perform exploratory data analysis (EDA) and preprocess
a sales dataset so that it is ready for modelling (weekly sales forecasting) in
later parts. I chose the **X-store sales dataset** (`store_sales.csv`), a furniture
sales dataset with 2,121 order-level records and 21 columns.

## Files

- `part1-submission.ipynb` — the main notebook containing all analysis,
  visualisations, preprocessing steps, and the summary.
- `store_sales.csv` — the raw dataset used in the notebook.

## What the notebook covers

1. **Understanding the variables** — loading the data, inspecting types and
   statistics, and confirming there are no missing values.
2. **Type conversion** — converting date columns to `datetime` and extracting
   numeric time features (year, month, week, weekday).
3. **Visualisation** — histograms, boxplots and bar charts to identify trends,
   skewness and outliers.
4. **Cleaning & encoding** — dropping non-predictive columns, One-Hot encoding
   categorical variables, handling outliers with a log transform, and standardising
   the continuous features.
5. **Correlation analysis** — a correlation heatmap and grouped summaries to
   identify related/redundant variables and perform feature selection.
6. **Summary** — key steps and findings.

## How to run

1. Install the dependencies:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
2. Open `part1-submission.ipynb` in Jupyter or VS Code.
3. Make sure `store_sales.csv` is in the same folder as the notebook.
4. Run all cells from top to bottom.
