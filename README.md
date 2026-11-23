# Retail Customer Sales: Data Analytics Mini Projects

Three mini projects on one simulated retail dataset (7,000 transactions, 2023-2024, four regions of India).

| Project | Notebook | Report |
|---|---|---|
| 1. Exploratory Data Analysis | `Project1_EDA.ipynb` | `Project1_EDA_Insights_Report.docx` |
| 2. Data Visualization | `Project2_Data_Visualization.ipynb` | `Project2_Visual_Report.docx` |
| 3. Advanced Statistics | `Project3_Advanced_Statistics.ipynb` | `Project3_Statistical_Findings_Report.docx` |

## Data files
- `retail_customer_sales_dataset.csv`: original raw dataset (needed only for Project 1; add it to the folder).
- `retail_customer_sales_cleaned.csv`: cleaned dataset produced by Project 1 and used by Projects 2 and 3.

## How to run
```
pip install pandas numpy matplotlib seaborn scipy
```
Run Project 1 first (it creates the cleaned CSV), then Projects 2 and 3. Keep the CSV files in the same folder as the notebooks.

## Main cleaning steps (Project 1)
Standardised Region/Gender labels, parsed four mixed date formats explicitly, removed 84 duplicate transactions, rebuilt invalid discounts from the Sales formula, replaced impossible ages and missing Age/Income from the same customer's other orders, and flagged every changed value.
