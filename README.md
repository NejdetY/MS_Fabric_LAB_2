# MS_Fabric_LAB_2
# Analyze and Visualize Data with Spark in Microsoft Fabric

This project demonstrates how to load, transform, partition, query, and visualize sales data using Apache Spark in Microsoft Fabric.

## 📌 Project Overview

In this hands-on exercise, I performed the following steps:

1. **Load Data**
   - Read order data from Parquet files into a Spark DataFrame.
   - Verified the correctness of the loaded data.

2. **Partition and Save Data**
   - Saved the DataFrame into partitioned Parquet files, organized by **Year** and **Month**.
   - Improved query performance by enabling efficient filtering based on partitions.

3. **Create Delta Table**
   - Created a Delta table named `salesorders` from the transformed data.
   - Enabled features like ACID transactions, time travel, and efficient schema management using the Delta format.

4. **Query with Spark SQL**
   - Ran SQL queries directly on the Delta table.
   - Calculated yearly gross revenue by aggregating sales data.

5. **Data Visualization**
   - Used the Fabric built-in chart tool for simple bar charts.
   - Created advanced visualizations using:
     - **Matplotlib** (bar plots, pie charts, subplots)
     - **Seaborn** (bar and line plots with aesthetic themes)

6. **Session Cleanup**
   - Properly ended the Spark session.
   - Deleted the workspace after the project was completed.

## 🛠️ Tools and Technologies

- **Apache Spark** (PySpark, Spark SQL)
- **Microsoft Fabric Lakehouse**
- **Delta Lake**
- **Python Visualization Libraries**: Matplotlib, Seaborn
- **Parquet File Format**

## 🎯 Key Learnings

- How to partition large datasets effectively for better query performance.
- How to use Delta tables to combine the flexibility of data lakes with the consistency of relational databases.
- How to work with Spark SQL inside Fabric notebooks for data exploration.
- How to visualize Spark DataFrames using powerful Python libraries.

## 📊 Sample Visualizations

- Revenue trends by year (bar charts)
- Order volume per year (pie charts)
- Yearly revenue trend lines (line charts)

## 🌟 Conclusion

This project enhanced my practical skills in working with big data using Spark in a modern Lakehouse architecture.  
It also strengthened my abilities in data querying and visualization, which are essential in any data engineering or analytics workflow.

---
🔗 *Follow my journey on [LinkedIn](https://www.linkedin.com/in/nejdet-yalcin/) or explore the project on GitHub!* 
