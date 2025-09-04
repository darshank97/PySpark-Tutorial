# PySpark DataFrame Transformations 🚀

This repository contains a Jupyter Notebook (`PySpark_DF_Transformations.ipynb`) showcasing **PySpark DataFrame operations**.  
It demonstrates how to load data, define schemas, and apply common DataFrame transformations in PySpark.

---

## 📂 Dataset Used
- **drivers.json** → JSON data with inferred schema
- **BigMart Sales.csv** → Retail sales dataset

---

## ⚡ Features & Transformations Covered

1. **Data Ingestion**
   - Reading JSON files with schema inference
   - Reading CSV files with:
     - Inferred schema
     - DDL-based schema
     - StructType schema

2. **Schema Exploration**
   - `printSchema()`
   - Handling nullable fields

3. **Column Operations**
   - `select()` and `alias()`
   - Adding new columns with `withColumn`
   - Renaming columns with `withColumnRenamed`

4. **Filtering & Conditional Logic**
   - `filter()` with equality and multiple conditions
   - Using `isin()` and `isNull()`

5. **Data Cleaning**
   - Handling missing values
   - Basic transformations for categorical columns

6. **Display & Exploration**
   - `.display()` for visual exploration
   - Viewing subsets of columns

---

## 🔧 Requirements

- Python 3.x
- [Apache Spark](https://spark.apache.org/) with PySpark
- Jupyter Notebook
- Databricks account

