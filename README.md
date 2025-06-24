# cpi-inflation-case-study
An in-depth analysis of India's CPI inflation data, investigating trends, the impact of COVID-19, and correlation with global oil prices.
# CPI Inflation Analysis Case Study

## Overview

This repository presents a comprehensive case study on India’s Consumer Price Index (CPI) inflation, examining category contributions, year‑over‑year trends, food inflation dynamics, COVID‑19 impacts, and correlations with oil prices. All analysis has been conducted end‑to‑end in Microsoft Excel using Power Query for data transformation and charting.

## Table of Contents

* [Problem Statement](#problem-statement)
* [Data Description](#data-description)
* [Methodology](#methodology)
* [Key Insights](#key-insights)
* [Repository Structure](#repository-structure)
* [How to View](#how-to-view)
* [Author](#author)
* [License](#license)

## Problem Statement

Refer to the detailed brief in `data/India CPI Inflation Case Study Problem Statement.docx`. In summary, the study covers:

1. **Category Contributions**: Share of major baskets (Food, Fuel & Light, etc.) in the latest CPI.
2. **Year‑over‑Year Trends**: Annual urban+rural inflation rates from 2017–2022, identifying peak years and drivers.
3. **Food Inflation Dynamics**: Month‑on‑month food inflation over the past 12 months, highlighting extremes and top sub‑category contributors.
4. **COVID‑19 Impact**: Comparison of pre‑ and post‑March 2020 CPI changes for Food, Health, and Essential Services.
5. **Oil Price Correlation**: Pearson correlations between imported crude oil prices and CPI categories (2021–2023).

## Data Description

* **Analysis Workbook** (`analysis/CPI_CASE_STUDY_ANALYSIS_PREM.xlsx`): Contains Power Query transformations, pivot tables, and charts.
* **Raw CPI Data** (`data/All_India_Index_Upto_April23.csv`): Monthly CPI indices for rural and urban segments.
* **Problem Statement** (`data/India CPI Inflation Case Study Problem Statement.docx`)
* **Dashboard Image** (`visualizations/CPI_Dashboard.png`)

## Methodology

All analytical steps were performed in Excel:

1. **Data Import & Cleaning**: Used Power Query to load CSV data, handle missing values, and standardize date fields.
2. **Aggregation & Calculations**: Created measures for month‑on‑month and year‑on‑year inflation, and aggregated sub‑items into broader buckets.
3. **Visualization**: Built PivotCharts and slicers to visualize contributions, trends, and correlations.
4. **Correlation Analysis**: Calculated Pearson correlation coefficients in Excel between CPI changes and imported oil price series.

## Key Insights

* **Dominant Basket**: Food & Beverages contributed **49.6%** of the CPI basket in May 2023.
* **Peak Annual Inflation**: The highest YoY inflation of **6.62%** occurred in **2022**, driven by supply disruptions and currency depreciation.
* **Food Inflation Extremes**: Between June 2022 and May 2023, the biggest monthly rise (+0.76%) was in April–May 2023; the largest drop (−0.59%) was in January–February 2023.
* **Top Sub‑category**: **Spices** saw the greatest 12‑month increase (+16.52%) among food items.
* **Pandemic Effects**: Post‑March 2020, Essential Services inflation rose to **7.07%**, while Food inflation slowed from **8.43%** to **3.88%**.
* **Oil Price Link**: Oils & Fats and Meat & Fish exhibit strong correlations (0.8) with crude oil prices, suggesting pass‑through effects.

## Repository Structure

```plaintext
├── analysis                             # Excel workbook with Power Query, pivots, and charts
│   └── CPI_CASE_STUDY_ANALYSIS_PREM.xlsx
├── data                                 # Source datasets and problem statement
│   ├── All_India_Index_Upto_April23.csv
│   └── India CPI Inflation Case Study Problem Statement.docx
├── visualizations                       # Final dashboard image and charts
│   └── CPI_Dashboard.png
├── .gitignore
├── LICENSE
└── README.md                            # This file
```

## How to View

1. Open **analysis/CPI_CASE_STUDY_ANALYSIS_PREM.xlsx** in Microsoft Excel (2016 or later).
2. Enable **Data > Queries & Connections** to refresh Power Query steps if needed.
3. Navigate through sheets to explore raw tables, pivot summaries, and dashboard views.

## Author

**Prem kumar Gara**
Data Analyst & Economic Research Enthusiast
[GitHub](https://github.com/premkumar-1122) | [LinkedIn]([https://www.linkedin.com/in/prem-kumar-gara-4aa95b132])/

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
