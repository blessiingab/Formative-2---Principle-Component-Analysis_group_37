# Formative 2 — Principal Component Analysis
**Group 37**

## Overview

This project applies **Principal Component Analysis (PCA)** to the African Financial Crises dataset. The goal is to reduce the dimensionality of historical financial indicators across 13 African countries and uncover the underlying structure driving banking crises.

## Dataset

**`african_crises.csv`** — 1,059 records spanning the 1870s to the 2010s across 13 African countries (Algeria, Angola, Egypt, Nigeria, Zimbabwe, and more).

| Column | Description |
|---|---|
| `country` / `cc3` | Country name and ISO code |
| `year` | Year of observation |
| `systemic_crisis` | Whether a systemic crisis occurred (binary) |
| `exch_usd` | Exchange rate to USD |
| `domestic_debt_in_default` | Domestic debt default flag (binary) |
| `sovereign_external_debt_default` | External sovereign debt default flag (binary) |
| `gdp_weighted_default` | GDP-weighted default measure |
| `inflation_annual_cpi` | Annual inflation rate (CPI) |
| `currency_crises` | Currency crisis flag (binary) |
| `inflation_crises` | Inflation crisis flag (binary) |
| `banking_crisis` | **Target** — `crisis` or `no_crisis` |

## Project Structure

```
.
├── african_crises.csv
├── Template_PCA_Formative_1[Peer_Pair_Number].ipynb - Colab.pdf
└── README.md
```

## Methodology

1. Data Loading & Exploratory Data Analysis
2. Preprocessing — missing value handling, categorical encoding
3. Feature scaling & standardization
4. PCA implementation
5. Explained variance analysis (scree plot)
6. Visualization — biplots, component scatter plots
7. Interpretation of principal components

## Team

| Name | Role | Email |
|---|---|---|
| Blessing Ingabire | Group Leader | b.ingabire1@alustudent.com |
| Saad Byiringiro | Research | s.byiringir@alustudent.com |

## Task Allocation

Full task tracker (assignments, deadlines, completion status, and meeting log):
[View Task Sheet](https://docs.google.com/spreadsheets/d/1SJ3svzeebAA0DKuxUNT_ZJyasqTovUOEmVRra-bQOeA/edit?usp=sharing)
