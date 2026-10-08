# Health Facility Stockout Analysis

## Overview

This project analyzes health facility stockout data to identify patterns in medicine and health-supply availability.

The analysis examines stockout patterns across products, facility types, districts, inventory conditions, and time. The goal is to generate data-driven insights that can support better inventory management and help reduce situations where essential health products are unavailable.

## Research Question

What patterns can be identified in health facility stockouts, and which factors are associated with higher stockout frequency?

## Objectives

- Identify products with higher stockout rates.
- Examine stockout patterns across different facility types.
- Compare stockout rates across districts.
- Analyze how stockout rates vary over time.
- Examine the relationship between stockouts and inventory conditions.
- Generate insights that could support better inventory management decisions.

## Dataset

This project uses health facility-level consumption and stock data from Sierra Leone, obtained from the Dryad research dataset accompanying the study *Improving Access to Essential Medicines via Decision-Aware Machine Learning*.

The S2 dataset used in this analysis contains **457,225 records and 16 variables**.

### Data Source

Chung, Angel Tsai-Hsuan; Abdulai, Jatu; Bayoh, Patrick; et al. (2026). *Data from: Improving access to essential medicines via decision-aware machine learning*. Dryad.

DOI: 10.5061/dryad.h9w0vt4tw

## Key Findings

- The overall stockout rate was approximately **13.55%**.
- Among products with at least 100 records, **Ciprofloxacin 500mg** had the highest observed stockout rate at approximately **29.63%**.
- **Kono** recorded the highest observed district stockout rate among districts with at least 500 records, at approximately **19.49%**.
- **CHP** facilities had the highest observed stockout rate among facility types at approximately **14.27%**.
- Monthly stockout rates varied considerably, with **July 2022** recording one of the highest observed rates at approximately **22.52%**.
- Stockout records had substantially lower average closing balances than non-stockout records.

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Analysis

The project includes:

- Data loading and inspection
- Overall stockout rate analysis
- Product-level analysis
- Facility-level analysis
- District-level analysis
- Facility-type analysis
- Inventory condition analysis
- Monthly stockout trend analysis
- Findings and interpretation
- Limitations

## Limitations

This analysis is descriptive and identifies patterns and associations; it does not establish causal relationships.

The dataset represents the health facilities and products included in the source dataset and may not represent all health facilities.

Some products have considerably fewer records than others, so comparisons involving small numbers of observations should be interpreted cautiously.

The analysis does not yet predict future stockouts or determine exact replenishment quantities.

## How to Run the Project

1. Download the S2 dataset from the Dryad source.
2. Extract the dataset locally.
3. Place `S2_Dhis2Data.csv` inside the `S2.csv` folder.
4. Open `stockout_analysis.ipynb` in Jupyter Notebook or VS Code.
5. Run the notebook from beginning to end.

## Project Status

Completed exploratory data analysis.

Future work may include developing predictive models to identify factors associated with future stockouts and evaluating approaches for stockout prediction.

## Author

**Yaqub Hamisu**

This project was completed as part of my ongoing learning journey in data science and health data research.
