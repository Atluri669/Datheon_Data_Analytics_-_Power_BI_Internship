# Task 3 - Telco Customer Churn Analysis

## Overview

This project analyzes customer churn for a telecommunications company. The analysis identifies churn patterns, evaluates retention by contract and payment method, calculates cohort retention, and highlights high-risk customer segments.

## Contents

- `Customer Cohort.docx` - Customer cohort analysis documentation.
- `database-upsert-engine/Data/telco_customer_churn.csv` - Source customer churn dataset.
- `database-upsert-engine/Note book/Telco Churn.ipynb` - Main analysis notebook.
- `database-upsert-engine/Note book/output/cleaned_telco_churn.csv` - Cleaned dataset.
- `database-upsert-engine/Note book/output/Telecom Customer Churn Dashboard.pbix` - Power BI dashboard.
- `database-upsert-engine/Note book/output/` - Churn heatmap and cohort retention outputs.
- `database-upsert-engine/Note book/outputs/` - CSV results for contract, payment, monthly charge, and high-risk segment analysis.

## Analysis

The project includes:

- Data cleaning and validation
- Overall churn and retention rates
- Churn analysis by contract type
- Churn analysis by payment method
- Monthly charge analysis
- Customer cohort retention
- High-risk customer segmentation
- Churn visualizations and an interactive Power BI dashboard

## Requirements

For the Jupyter notebook:

```bash
python -m pip install pandas numpy matplotlib seaborn jupyter
```

For the dashboard:

- Microsoft Power BI Desktop

## How to Run

1. Open `database-upsert-engine/Note book/Telco Churn.ipynb` in Jupyter Notebook.
2. Update the dataset path in the notebook if the project is stored in a different location.
3. Run all cells using **Kernel > Restart & Run All**.
4. Open `database-upsert-engine/Note book/output/Telecom Customer Churn Dashboard.pbix` in Microsoft Power BI Desktop to explore the dashboard.
