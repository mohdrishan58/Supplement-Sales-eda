# 🏋️ Supplement Sales — Exploratory Data Analysis

## Overview
End-to-end exploratory data analysis (EDA) on weekly supplement sales data
covering revenue trends, product performance, return rates, and discount
impact across multiple platforms and locations.

## Tools & Libraries
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly

## Dataset
- Weekly supplement sales records
- Columns: Date, Category, Product Name, Price, Discount, Units Sold,
  Units Returned, Revenue, Location, Platform

## Key Findings
- Weight Loss category leads revenue (~26% of total sales)
- Amazon is the top sales platform (~38% revenue share)
- Discounts show weak correlation with revenue — volume drives growth
- Vitamins have the highest return rate (~6%)
- Revenue grew ~11–12% over the analysis period

## Analysis Performed
- Revenue trend over time (daily & monthly)
- Revenue by product category and platform
- Top 10 products by revenue
- Return rate analysis by category
- Discount vs Revenue correlation
- Net revenue calculation after returns
- Correlation heatmap of key variables

## How to Run
1. Clone the repo
   git clone https://github.com/mohdrishan58/Supplement-Sales-eda.git
2. Install dependencies
   pip install pandas numpy matplotlib seaborn plotly
3. Open the notebook in Jupyter
