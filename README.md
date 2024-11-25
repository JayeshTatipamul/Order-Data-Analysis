# Order Data Analysis Project (ETL)

This repository contains the analysis of sales data from an e-commerce platform. The data was extracted from Kaggle using the Kaggle API, transformed using Python with the help of NumPy and Pandas in Jupyter Notebook, and then loaded into MySQL for further analysis. 

## Project Overview

The analysis focuses on answering several business questions related to product sales and revenue generation. The key tasks involved in the project include:

1. **Data Extraction**: Extracted raw sales data from Kaggle using the Kaggle API.
2. **Data Transformation**: Transformed the raw data using Python libraries such as NumPy and Pandas.
3. **Data Loading**: Loaded the transformed data into MySQL for querying and analysis.

## Business Analysis

The analysis in MySQL was performed to answer the following questions:

- **Top 10 Highest Revenue-Generating Products**: Identify which products generate the highest revenue.
- **Top 5 Highest Selling Products in Each Region**: Find out which products are selling the most in different regions.
- **Month-Over-Month Growth Comparison (2022 vs 2023)**: Compare sales data for January 2022 vs January 2023, February 2022 vs February 2023, and so on.
- **Month with Highest Sales for Each Category**: Analyze which month had the highest sales for each product category.
- **Subcategory with Highest Growth by Profit in 2023 Compared to 2022**: Identify which product subcategory saw the highest growth in profit from 2022 to 2023.

## SQL Concepts Used

In MySQL, the following concepts and techniques were used to perform the analysis:

- **DDL (Data Definition Language)**: Used for defining database structures.
- **DML (Data Manipulation Language)**: Used for inserting, updating, and deleting data.
- **Joins**: Combined data from multiple tables using different types of joins (INNER, LEFT, etc.).
- **Subqueries**: Embedded queries to perform complex data retrievals.
- **Multiple Joins**: Combined data from more than two tables to answer business queries.
- **Case Statements**: Used for conditional logic in queries.
- **Logical Conditions**: Implemented various logical conditions to filter and segment data.
- **Nested Subqueries**: Used subqueries within other queries to calculate complex results.
- **Window Functions**: Applied window functions to analyze sales trends over different time periods.
- **CTE (Common Table Expressions)**: Used CTEs for simplifying complex queries.

## Technologies Used

- **Python**: NumPy, Pandas (for data transformation)
- **MySQL**: Data storage, analysis, and SQL queries
- **Kaggle API**: Data extraction from Kaggle

## Getting Started

To get started with this project, you will need the following:

1. **Install Required Libraries**:
   - Install the necessary Python libraries with the following command:
     ```bash
     pip install pandas numpy mysql-connector
     ```

2. **Set Up MySQL**:
   - Make sure you have MySQL installed and running. Set up the database to load the transformed data.

3. **Run the Notebook**:
   - Open the Jupyter notebook and execute the steps for data transformation and loading.

4. **Run SQL Queries**:
   - Use the provided SQL queries to perform the analysis in MySQL.
