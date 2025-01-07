
# Apple Product Analysis

This project focuses on analyzing customer purchasing patterns for Apple products using the `transaction_updated.csv` dataset.

## Objective

1. Identify customers who bought AirPods after purchasing an iPhone.
2. Find customers who have purchased both AirPods and iPhones.
3. List all products bought by customers after their initial purchase.

## Data Source

The dataset used in this analysis is named `transaction_updated.csv`. It contains transaction details such as customer ID, product details, purchase date, and more.

## Process

### 1. Extract
Data is extracted from the `transaction_updated.csv` file. The factory design pattern is implemented to handle various file types (e.g., CSV, Parquet, Delta Tables).

### 2. Transform
Data transformation and analysis are performed using PySpark and Spark SQL to identify patterns in customer purchasing behavior.

### 3. Load
The processed data is stored in:
- Data Lakes for further processing and scalability.
- Delta Tables for incremental data updates and versioning.

## Tools and Frameworks

- PySpark and Spark SQL for data transformation and querying.
- Data stored in Delta Lake and Delta Tables.

