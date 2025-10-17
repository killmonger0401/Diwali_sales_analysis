# Diwali Sales Data Analysis

## Overview
This repository contains an exploratory data analysis (EDA) project on sales data collected during the Diwali festival. The analysis uses Python and focuses on understanding customer demographics, purchasing patterns, and key insights from the dataset. The goal is to identify trends in sales by gender, age, marital status, occupation, location, and product categories.

The project is implemented in a Jupyter Notebook (`Diwali_Sales_Analysis.ipynb`), which includes data loading, cleaning, visualization, and conclusions.

## Dataset
- **Source**: Diwali Sales Data CSV file (included in this repo as `Diwali Sales Data.csv`).
- **Description**: Contains 11,251 records of sales transactions with columns including User_ID, Customer Name, Product_ID, Gender, Age Group, Age, Marital Status, State, Zone, Occupation, Product Category, Orders, and Amount.
- **Key Stats** (from the analysis):
  - Total records: 11,251 (after cleaning: 11,239).
  - Average order amount: ₹9,453.61.
  - Average age: 35.41 years.
  - Most sales from Western and Southern zones.

**Note**: If you don't want to include the raw CSV in the repo (e.g., for privacy reasons), replace the local path in the notebook with a public link (e.g., from Kaggle) and update the loading code accordingly.

## Technologies Used
- **Language**: Python 3.x
- **Libraries**:
  - Pandas (data manipulation)
  - NumPy (numerical operations)
  - Matplotlib & Seaborn (visualizations)
  - Plotly (interactive plots)

## Key Findings
The EDA reveals several insights about customer behavior during Diwali sales:

- **Gender**: Females contribute ~70% of total sales (₹57M+ vs. ₹25M for males).
- **Age Group**: The 26-35 age group drives the highest sales (~₹39M).
- **Marital Status**: Married customers account for ~58% of sales.
- **Occupation**: IT sector leads with ~₹12M in sales, followed by Healthcare and Aviation.
- **State**: Uttar Pradesh, Maharashtra, and Karnataka are top contributors.
- **Zone**: Western zone has the highest sales (~₹36M).
- **Product Category**: Food, Clothing, and Electronics dominate, with Food leading at ~₹21M.

### Visualizations
The notebook includes bar plots for:
- Sales by Gender
- Sales by Age Group
- Sales by Marital Status
- Sales by Occupation
- Sales by State
- Sales by Zone
- Top 10 Product Categories by Sales

## Conclusion
Married women aged 26-35 from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, or Aviation, are the primary buyers. They prefer products in Food, Clothing, and Electronics categories. This can inform targeted marketing strategies for future festive seasons.



