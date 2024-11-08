# ETL Pipeline for World Bank Data Analysis

## Project Summary

This notebook is all about building an ETL (Extract, Transform, Load) pipeline using real data from the World Bank. The end goal? To create a unified dataset that we can use to predict the total costs of World Bank projects. We’ll pull in data from various sources, clean and transform it, and finally load it into a database—setting the foundation for powerful predictive models.

## Data Sources

For this project, I’m using two main datasets from the World Bank:

1. **World Bank Indicator Data:**  
   Socio-economic indicators for countries around the world, such as population, arable land, and government debt levels.

2. **World Bank Project Data:**  
   Information about World Bank-funded projects dating back to 1947, with details like project names, sectors, costs, and country information.

## Project Outline

This notebook guides you through each phase of the ETL process, outlined as follows:

### 1. **Data Extraction**

   Pulling data from a variety of sources:
   - CSV files
   - JSON files
   - APIs (application programming interfaces)

### 2. **Data Transformation**

   Cleaning and preparing data through a series of processing steps:
   - **Combining** multiple datasets
   - **Cleaning** for missing values, data consistency, and standard formats
   - **Handling Data Types** for accurate processing
   - **Parsing Dates** for standardized date formats
   - **File Encoding** for compatibility
   - **Handling Missing Data** by either filling or dropping gaps
   - **Removing Duplicates** to avoid data redundancy
   - **Creating Dummy Variables** to handle categorical data
   - **Outlier Removal** to enhance model robustness
   - **Feature Scaling** to normalize data ranges
   - **Feature Engineering** to create additional insights from the raw data

### 3. **Data Loading**

   Finally, the transformed data is loaded into a database for easy access and further analysis.

## Building the ETL Pipeline

The ETL pipeline is programmed to:
1. **Extract** data from various sources
2. **Transform** it using various cleaning and processing techniques
3. **Load** it into a single, consolidated database— all in one step.

## Project Objective

The ultimate aim of this notebook is to merge these datasets into a single, high-quality table, ready for machine learning models to predict World Bank project costs. Along the way, we tackle real-world data wrangling challenges, demonstrating how to build a clean, structured data pipeline for long-term, scalable use.

---

This project is a snapshot of my progress and learnings in data engineering, applying concepts to real-world data and building a solid foundation for data-driven insights and predictive modeling.