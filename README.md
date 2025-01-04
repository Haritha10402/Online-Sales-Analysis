 # Online Sales Analysis

This repository contains the analysis of an online sales dataset to understand various aspects of the sales data, including categories, payment modes, and geographical distribution.

## Project Overview

The project is designed to perform exploratory data analysis (EDA) on an online sales dataset. The dataset contains information related to customer orders, payment modes, sales performance, and regional distribution. This analysis aims to uncover patterns, trends, and valuable insights from the data.

## Datasets
The project uses two datasets:

1. **Details.csv**: Contains details of individual transactions, including order information such as amount, profit, quantity, category, sub-category, and payment mode.
2. **Orders.csv**: Contains information related to customer orders such as order ID, customer name, location (state, city), and order date.

Both datasets are merged on the `Order ID` to create a comprehensive dataset for analysis.

## Analysis Steps

The analysis follows these steps:

1. **Data Loading and Cleaning**:
   - Load the two datasets into DataFrames.
   - Perform initial data cleaning to handle missing values and ensure consistency.

2. **Data Exploration**:
   - Display basic information about the dataset, including shape, data types, and missing values.
   - Generate descriptive statistics for both numeric and categorical columns.

3. **Data Merging**:
   - Merge the two datasets (`Details.csv` and `Orders.csv`) based on the `Order ID`.

4. **Data Visualization**:
   - Visualize the distribution of different categories of products (`Category`, `Sub-Category`).
   - Analyze the payment modes used for transactions.
   - Explore the geographical distribution of sales across states and cities.

## Key Insights

- **Categories**: The most frequent product category is `Clothing`, followed by `Electronics` and `Furniture`.
- **Payment Modes**: Most customers prefer the `COD` (Cash on Delivery) payment option, followed by `UPI`, `Debit Card`, and `Credit Card`.
- **Regional Distribution**: The states with the highest number of orders are `Madhya Pradesh`, `Maharashtra`, and `Uttar Pradesh`.

## Code Walkthrough

1. **Data Loading and Merging**:
   - Load `Details.csv` and `Orders.csv` datasets and merge them on `Order ID`.
   
2. **Visualization**:
   - Visualize product categories, payment methods, and regional sales using bar and pie charts.

## Requirements

- Python 3.x
- pandas, numpy, matplotlib, seaborn, plotly

Install with:

```bash
pip install pandas numpy matplotlib seaborn plotly


## CONCLUSION 
This analysis provides valuable insights into the online sales data. It helps identify which categories are most popular, the preferred payment methods, and regional patterns in sales. This can be used to make data-driven decisions regarding inventory management, marketing strategies, and payment system optimization.

## License
MIT License
This version focuses on key sections and gives a brief overview of the project.
