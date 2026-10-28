# SQL Data Cleaning and Exploratory Data Analysis

## 📌 Project Overview

This project focuses on cleaning and analyzing a layoffs dataset using MySQL. The goal is to improve data quality, handle missing values, remove duplicate records, standardize inconsistent data, and perform exploratory data analysis (EDA) to identify meaningful insights.

## 🎯 Objectives

- Remove duplicate records from the dataset.
- Standardize inconsistent company and industry names.
- Handle missing and NULL values.
- Convert date columns into the correct data types.
- Perform exploratory data analysis using SQL queries.
- Identify layoff trends across companies, industries, countries, and years.

## 🛠️ Tools & Technologies

- **Database:** MySQL
- **Language:** SQL
- **Concepts:** CTEs, Window Functions, Self-Joins, Aggregate Functions, GROUP BY, ORDER BY, Data Cleaning, and EDA.

## 📂 Project Structure

```text
SQL-Data-Cleaning/
│
├── Data_Cleaning.sql
├── Exploratory_Data_Analysis.sql
└── README.md
```

## 🧹 Data Cleaning Process

### 1. Create a Staging Table
Created a staging table to preserve the original dataset and perform cleaning operations safely.

### 2. Remove Duplicates
Used `ROW_NUMBER()` and Common Table Expressions (CTEs) to identify duplicate records and remove them.

### 3. Standardize the Data
Cleaned inconsistent company names, industry values, and other text fields to improve data consistency.

### 4. Handle Missing Values
Identified NULL and blank values. Used self-joins to populate missing industry values when reliable matching records were available.

### 5. Convert Date Formats
Converted date columns into the appropriate MySQL date data type for accurate analysis.

### 6. Remove Unnecessary Records
Removed records where both `total_laid_off` and `percentage_laid_off` were NULL, as these records lacked essential layoff information for the analysis.

## 📊 Exploratory Data Analysis (EDA)

Performed SQL queries to explore the cleaned dataset and identify patterns, including:

- Companies with the highest number of layoffs.
- Companies that experienced complete workforce layoffs.
- Total layoffs by industry.
- Total layoffs by country.
- Layoff trends by year and date.
- Monthly layoff trends.
- Companies with the highest layoffs over time.
- Rolling totals of layoffs using window functions.

## 💡 Key SQL Concepts Practiced

- `SELECT`, `WHERE`, and `ORDER BY`
- Aggregate Functions: `SUM()`, `MAX()`, and `MIN()`
- `GROUP BY` and `HAVING`
- Common Table Expressions (CTEs)
- Window Functions: `ROW_NUMBER()` and `DENSE_RANK()`
- Self-Joins
- Date Functions
- Data Cleaning and NULL Handling
- Rolling Totals and Ranking

## 🚀 What I Learned

- How to clean a real-world dataset using MySQL.
- How to identify and remove duplicate records.
- How to handle missing values and standardize inconsistent data.
- How to use CTEs and window functions for data preparation.
- How to perform exploratory data analysis using SQL.
- How to extract meaningful insights from structured data.

## 👨‍💻 Author

**Khamruzzama**

B.Tech in Information Technology | 2026

**Skills:** SQL | MySQL | Data Cleaning | Exploratory Data Analysis
