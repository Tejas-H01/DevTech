# DevTech | Data Analyst Training

Welcome! This repository documents my training period at **DevTech**, where I am developing practical skills as a data analyst. It brings together hands-on learning materials and project work completed during the training.

## Project: Global Superstore Sales Analysis

The first project explores a retail sales dataset covering 2011–2015. It includes a Jupyter notebook for data inspection and cleaning, a Power BI dashboard, and a written report.

### What the project covers

- Inspecting a 51,290-row sales dataset and its fields
- Checking data quality, including missing values and duplicate rows
- Cleaning text, converting date and numeric fields, and removing duplicate records
- Creating a shipping-days field from order and ship dates
- Exploring the results in a Power BI dashboard and project report

### Project files

| Folder | Contents |
| --- | --- |
| [`notebooks/`](./Day1%20DataAnalytics/superstore-sales-analysis/notebooks/) | Jupyter notebook and project screenshot |
| [`data/raw/`](./Day1%20DataAnalytics/superstore-sales-analysis/data/raw/) | Original Global Superstore dataset |
| [`data/cleaned/`](./Day1%20DataAnalytics/superstore-sales-analysis/data/cleaned/) | Cleaned dataset exported from the notebook |
| [`dashboard/`](./Day1%20DataAnalytics/superstore-sales-analysis/dashboard/) | Power BI report (`.pbix`) and PDF export |
| [`Project Report/`](./Day1%20DataAnalytics/superstore-sales-analysis/Project%20Report/) | Written project report |

## Getting started

To explore the project:

1. Open the notebook at [`sales_analysis_cleaning.ipynb`](./Day1%20DataAnalytics/superstore-sales-analysis/notebooks/sales_analysis_cleaning.ipynb) in Jupyter Notebook, JupyterLab, or Google Colab.
2. If running it locally, make sure its data-loading cell points to the raw CSV at `../data/raw/superstore_dataset2011-2015.csv` (relative to the `notebooks` folder). The notebook was originally prepared with a Colab-style file path.
3. The notebook uses Python and pandas. Install pandas in your selected Python environment if needed:

   ```bash
   python -m pip install pandas
   ```

4. Open the `.pbix` file in Power BI Desktop to explore the dashboard, or view its PDF export and the project report.

## Repository structure

```text
.
├── .github/
├── Day1 DataAnalytics/
│   └── superstore-sales-analysis/
│       ├── Project Report/
│       ├── dashboard/
│       ├── data/
│       │   ├── cleaned/
│       │   └── raw/
│       └── notebooks/
└── README.md
```

This is a learning repository: projects and materials will grow as I progress through my data analyst training at DevTech.
