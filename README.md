# Diwali Sales Data Analysis

## Overview
This project involves the analysis of Diwali sales data to understand customer behavior and trends. The dataset contains information about customer demographics, products, orders, and sales amounts. The goal of this analysis is to uncover insights related to customer purchasing patterns, including the relationship between gender, age group, marital status, occupation, and product category.

## Dataset

The dataset used for this analysis is the **Diwali Sales Data** CSV file. It contains the following columns:
User_ID: Unique identifier for the customer
Cust_name: Customer name
Product_ID: Product identifier
Gender: Gender of the customer
Age Group: Age group of the customer
Age: Age of the customer
Marital_Status: Marital status of the customer (0 = Single, 1 = Married)
State: State where the customer resides
Zone: Geographical zone of the customer
Occupation: Occupation of the customer
Product_Category: Category of the product purchased
Orders: Number of orders made by the customer
Amount: Total amount spent by the customer
Status: (Blank column, dropped)
unnamed1: (Blank column, dropped)


## Project Structure

- **Data Preprocessing**: The dataset is cleaned by removing irrelevant columns, handling missing values, and converting data types where necessary.
- **Exploratory Data Analysis (EDA)**: Various visualizations are created to analyze the relationship between customer demographics and sales data.
- **Key Insights**: Analysis of gender, age group, marital status, state, occupation, product category, and most sold products.

## Steps Involved

1. **Data Cleaning**:
    - Removed blank columns (`Status` and `unnamed1`).
    - Dropped rows with missing values in the `Amount` column.
    - Renamed the `Marital_Status` column to `Shaadi`.
    - Changed the `Amount` column data type to `int`.

2. **Exploratory Data Analysis (EDA)**:
    - Visualized the distribution of sales by gender, age group, marital status, state, occupation, and product category.
    - Generated bar plots for the total amount and number of orders by gender, age group, marital status, state, and product category.
    - Identified the top 10 most sold products and the states with the highest sales.

3. **Key Findings**:
    - Married women in the 26-35 age group from Uttar Pradesh, Maharashtra, and Karnataka, particularly in the IT sector, tend to make more purchases.
    - The most popular product categories include **Food**, **Clothing**, and **Electronics**.

## Visualizations

- **Gender vs Total Amount**: A bar plot showing the total sales amount by gender.
- **Age Group vs Total Amount**: A bar plot showing the total sales amount by age group.
- **State-wise Analysis**: Bar plots for the total number of orders and total sales by state.
- **Marital Status vs Amount**: Sales amount grouped by marital status and gender.
- **Occupation vs Sales**: Bar plot showing the total sales by occupation.
- **Product Category vs Sales**: Analysis of sales by product category.

## Conclusion

The analysis reveals that **married women aged 26-35 years** from **UP**, **Maharashtra**, and **Karnataka**, working in **IT**, are more likely to purchase products. The most purchased products fall under the **Food**, **Clothing**, and **Electronics** categories.

## Requirements

Python 3.x pandas numpy matplotlib seaborn


## Installation
To install the required libraries, run:
pip install pandas numpy matplotlib seaborn


**Usage**
Clone the repository or download the dataset.
Run the Jupyter notebook or Python script to perform the analysis.
The visualizations will be displayed within the notebook.

