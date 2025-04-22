# Unlocking-Customer-Insights-with-PySpark---Retail-Sales-Analysis


A big data project that analyzes and transforms retail sales data using Apache Spark and PySpark on Google Colab. It performs advanced data engineering operations such as joins, nested JSON creation, denormalization, and revenue analysis by month.

---

## Project Overview

This project demonstrates how to process large-scale retail transaction data using Apache Spark in a cloud-based Python environment. The focus is on combining customer, order, and item-level data to:

- Generate nested JSON views for easy API or reporting use
- Flatten complex data for analytics
- Aggregate monthly revenues for business insights

---

## Datasets Used

Three input CSV files are used, each representing a normalized retail schema:

- `customers.csv`: Customer personal and address information
- `orders.csv`: Orders made by customers with status and dates
- `order_items.csv`: Item-level details per order including subtotal and product info

---

##  Tech Stack

- [Apache Spark 3.4.1](https://spark.apache.org/)
- PySpark (Python API for Spark)
- Google Colab (cloud notebook environment)
- OpenJDK 11
- JSON and CSV file handling

---

## Key Features

1.  Load and parse structured CSV data using predefined schemas  
2.  Join customer, order, and item data into a unified view  
3.  Generate nested JSONs for customers with their order and item details  
4.  Create a fully denormalized structure to mimic NoSQL-style records  
5.  Filter and flatten JSON for transactional insights  
6.  Perform revenue aggregation by month using Spark SQL functions

