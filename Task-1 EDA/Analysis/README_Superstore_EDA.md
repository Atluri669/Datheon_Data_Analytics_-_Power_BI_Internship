# Superstore Retail Sales – EDA

## Files
- `Superstore_Retail_Sales_EDA.ipynb` – Jupyter Notebook containing data cleaning, KPI calculations, customer/segment analysis, monthly seasonality, category and regional performance, discount sensitivity, visualizations, and executive findings.
- `superstore_sales.csv` – Source dataset (keep it in the same folder as the notebook).

## Requirements
Install the required packages:

```bash
python -m pip install pandas numpy matplotlib seaborn jupyter
```

## Run the notebook
1. Place `Superstore_Retail_Sales_EDA.ipynb` and `superstore_sales.csv` in the same folder.
2. Open a terminal in that folder.
3. Run:

```bash
jupyter notebook
```

4. Open `Superstore_Retail_Sales_EDA.ipynb`.
5. Select **Kernel → Restart & Run All**.

## Data-cleaning note
The supplied CSV contains 10,800 rows. Only 9,994 rows have valid order dates and required numeric sales fields. The notebook parses dates and numeric columns, removes exact duplicates, and excludes incomplete/non-transaction rows from the sales analysis.

## Main analysis
- Data quality and missing-value profiling
- Customer purchase volume and segment performance
- Monthly sales trend and seasonality
- Category and sub-category sales/profit
- Regional performance
- Discount versus profit analysis
- Evidence-based executive findings
