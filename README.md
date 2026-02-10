# DA TASK 5

# 📊 Customer Sales Analysis

## Overview
This project performs an end-to-end exploratory and analytical study of customer sales data to uncover purchasing patterns, top customers, regional performance, and product-level trends. The analysis integrates transactional sales data with customer profile and churn information to generate actionable business insights. The project follows a structured data analytics pipeline, including data loading, cleaning, merging, aggregation, visualization, and reporting.

## Project Structure
DA-TASK-5/
│
├── data/
│ ├── sales_data.csv
│ └── customer_churn.csv
│
├── notebooks/
│ └── customer_analysis.ipynb
│
├── visualizations/
│ ├── revenue_by_month.png
│ ├── top_customers.png
│ ├── sales_by_region.png
│ └── product_trends.png
│
├── analysis_report.md (or analysis_report.pdf)
├── README.md
└── requirements.txt


## Objectives
- Analyze customer purchasing behavior and identify high-value customers.
- Evaluate sales trends across time and regions.
- Identify top-performing products and potential cross-selling opportunities.
- Assess customer retention using churn indicators.
- Present insights through professional visualizations and a structured report.

## Tools & Technologies
- **Python**
- **Pandas** for data manipulation and aggregation  
- **Matplotlib / Seaborn** for visualization  
- **Jupyter Notebook** for interactive analysis  

## How to Run the Project

1. **Install dependencies**
```bash
pip install -r requirements.txt
Launch the notebook

jupyter notebook notebooks/customer_analysis.ipynb
Run all cells to reproduce the analysis and generate visualizations in the visualizations/ folder.

Key Features
Data cleaning and preprocessing (date parsing, numeric conversions, missing value handling)

Multiple aggregations (customer-level, regional, monthly, and product-level)

Dataset merging using customer identifiers

Pivot table for multi-dimensional sales analysis

Professional visualizations saved as PNG files

Business-oriented insights and recommendations

Outputs
Processed analysis and insights within the Jupyter Notebook

Saved charts in the visualizations/ directory

A structured analytical report summarizing findings and recommendations

Future Improvements
Incorporate predictive modeling for sales forecasting and churn prediction.

Add cohort analysis to study customer lifecycle behavior.

Extend cross-selling analysis using market basket techniques.

