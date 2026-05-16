# E-Commerce Order Analytics & Customer Segmentation with PySpark

This project demonstrates an end-to-end E-Commerce data processing and analytics pipeline using PySpark on a large dataset. 
The focus is on data engineering, performance optimization, and actionable business insights.

## What I Did:

Data Processing & Cleaning

Loaded multiple order, customer, and product datasets.

Handled missing values and cleaned data for analysis.

Order Revenue & Customer Segmentation

Calculated order_revenue = price + freight_value.

Computed Average Order Value (AOV) per customer.

Segmented customers into High, Medium, and Low value.

Order Insights & Analytics

Hourly and weekday/weekend order distribution.

Order volume by customer state.

Freight value categorization (Low, Medium, High).

Spark Optimization & Performance Tuning

Configured Spark: executors, cores, memory, shuffle partitions, adaptive queries.

Implemented join optimizations: broadcast join, sort-merge join, bucket join.

Handled skewed data for faster join performance.

Data Storage & Retrieval

Saved processed datasets in Parquet, CSV, Hive tables, and Google Cloud Storage.

Ensured efficient storage and retrieval for downstream analytics.

Key Tools & Technologies

PySpark, Spark SQL, Hadoop HDFS, Google Cloud Storage, Hive


## Outcome / Insights:

Identified top-spending customers and segmented them for targeted marketing.

Analyzed order patterns by time and region.

Built a scalable Spark pipeline that can handle millions of orders efficiently.

Author

Ankit Sharma – Data Engineer | PySpark Enthusiast

