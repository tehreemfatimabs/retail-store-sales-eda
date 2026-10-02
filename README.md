# Retail Store Sales — Exploratory Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a cleaned retail store sales dataset as part of the VEDA Technology Data Analytics Internship.

## Objective

The objective is to explore distributions, categorical patterns, relationships, and potential outliers in the dataset and identify meaningful insights through statistical analysis and visualization.

## Tools & Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

- Dataset inspection
- Summary statistics
- Univariate analysis
- Categorical analysis
- Distribution analysis
- Outlier detection using the IQR method
- Correlation analysis
- Key insight identification

## Key Findings

- `Total Spent` is positively skewed.
- `Quantity` shows a noticeable concentration around 6 units.
- Transaction volumes are relatively balanced across categories.
- `Quantity` has a positive correlation with `Total Spent` (r = 0.71).
- `Price Per Unit` has a positive correlation with `Total Spent` (r = 0.60).
- Several high-value observations were identified in `Total Spent`.

## Approach

The cleaned dataset from Task 1 was loaded into Python and inspected using Pandas. Statistical summaries and visualizations were then used to understand numerical distributions, categorical patterns, potential outliers, and relationships between numerical variables.

## Outcome

The EDA provides an initial understanding of the dataset and highlights important patterns that can support further analysis and business interpretation.

## Deployment Configuration

This project is primarily a Jupyter Notebook-based EDA project and does not require a web deployment. The notebook and analysis files are provided directly in this repository for reproducibility.

## Rollback / Version Evidence

Project changes are tracked through Git/GitHub version history. Previous versions of the notebook can be restored using GitHub commit history if required.

## Project Files

- `Retail_Store_Sales_EDA.ipynb` — Complete EDA notebook
- `cleaned_retail_store_sales.csv` — Cleaned dataset used for analysis
- `README.md` — Project documentation
