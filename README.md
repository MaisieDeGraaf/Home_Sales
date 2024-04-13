# Home Sales Data Analysis

This project involves data analysis of home sales data using PySpark, focusing on various SQL queries executed on a Spark DataFrame. The analysis includes tasks such as calculating average prices based on different criteria and optimizing query performance using caching and partitioning.

## Project Overview

The analysis is performed using PySpark, which is a Python API for Apache Spark, a distributed computing framework. The dataset used in this analysis is home_sales_revised.csv, containing information about home sales, including price, bedrooms, bathrooms, square footage, and more.

## Files and Setup

- Home_Sales.ipynb: Jupyter Notebook containing PySpark code for data analysis. To use in Colab

## Tasks and Queries

1. Average Price Analysis:

- Calculating average prices for four-bedroom houses per year.
  
- Calculating average prices for homes with specific criteria (bedrooms, bathrooms, square footage) per year.

2. Query Optimization:

- Caching the DataFrame to improve query performance.
  
- Partitioning the data by the "date_built" field and storing in parquet format.

3. Performance Evaluation:

- Comparing query runtimes between cached DataFrame and parquet-formatted data.
  
- Verifying table caching and uncaching.

## Instructions

1. Environment Setup:

- Install necessary dependencies including Spark and Java.
  
- Initialize Spark session using PySpark.
  
2. Data Loading and Preparation:

- Read the CSV data into a Spark DataFrame.

- Create a temporary view of the DataFrame for SQL queries.

3. Data Analysis:

- Execute SQL queries to analyze average prices based on specific criteria.
  
4. Query Optimization:

- Cache the DataFrame for performance optimization.

- Partition the data and save in parquet format.

5. Performance Evaluation:

- Measure query runtimes before and after optimization.

- Verify table caching and uncaching.

## Conclusion

This project demonstrates how to leverage PySpark and Spark SQL for data analysis tasks on large datasets. By optimizing queries through caching and partitioning, we can improve performance and scalability of data processing operations.
