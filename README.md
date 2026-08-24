# 📊 Customer Churn & Revenue Impact Analysis

An end-to-end **customer churn analysis project** for an OTT subscription platform, using SQL and Python to analyze customer behavior, subscription patterns, churn risk, and revenue impact.

The project covers the complete analytical workflow:

**SQLite Database → SQL Extraction → Data Cleaning → Feature Engineering → EDA → Visualization → Business Insights**

---

## 🎯 Project Objective

The objective of this project was to understand:

* How many customers are churning?
* Which subscription/contract segments have higher churn?
* Which customer segments contribute most to revenue loss?
* How does churn affect customer lifetime value?
* Which customer groups should be prioritized for retention?

---

## 🛠️ Tech Stack

| Technology           | Purpose                        |
| -------------------- | ------------------------------ |
| **SQLite**           | Relational database            |
| **SQL**              | Data extraction and querying   |
| **Python**           | Data analysis                  |
| **Pandas**           | Data manipulation and analysis |
| **NumPy**            | Numerical calculations         |
| **Matplotlib**       | Data visualization             |
| **Seaborn**          | Statistical visualization      |
| **Jupyter Notebook** | Analysis environment           |

---

## 🔄 Analysis Workflow

```text
SQLite Database
      ↓
SQL Queries
      ↓
Import into Python
      ↓
Data Cleaning & Quality Checks
      ↓
Feature Engineering
      ↓
Exploratory Data Analysis
      ↓
Visualization
      ↓
Churn & Revenue Analysis
      ↓
Business Insights
```

---

## 📈 Key Business Metrics

| KPI                    |         Result |
| ---------------------- | -------------: |
| Overall Churn Rate     |      **28.6%** |
| Retention Rate         |      **71.4%** |
| Monthly Contract Churn |      **55.6%** |
| Annual Contract Churn  |       **8.3%** |
| Revenue Loss           |        **18%** |
| Total Revenue          |       **₹395** |
| Revenue Lost to Churn  |        **₹74** |
| CLTV Lost              |     **₹2,047** |
| Average Tenure         | **1,451 days** |

---

## 🔍 Key Findings

### 1. Monthly vs Annual Churn

The largest churn disparity was observed between monthly and annual subscribers.

* Monthly churn: **55.6%**
* Annual churn: **8.3%**
* Monthly subscribers had approximately **6.7× higher churn**

This suggests that contract structure may be an important retention lever.

### 2. Revenue Impact

Churned customers accounted for approximately **18% of total revenue**, highlighting the financial impact of customer attrition.

### 3. Geographic Pattern

**Karnataka** had the highest churn in the analyzed dataset.

### 4. Time-Based Churn

The highest churn concentration was observed in **September 2024**, indicating a potential period for further investigation.

### 5. Customer Lifetime Value

The analysis estimated approximately **₹2,047 in CLTV lost** from churned customers, helping quantify the longer-term impact beyond immediate revenue loss.

---

## 🧹 Data Preparation

The dataset was prepared using Pandas and NumPy.

Key activities included:

* Inspecting data types
* Renaming columns
* Selecting required columns
* Checking duplicate records
* Identifying missing/null values
* Performing data quality checks
* Filtering records
* Transforming existing fields

---

## ⚙️ Feature Engineering

Additional analytical fields were created to support churn analysis, including:

* Customer tenure
* Churn indicators
* Revenue-related metrics
* Contract/plan segmentation
* Customer-level risk indicators

These features were then used for aggregation and segmentation.

---

## 📊 Exploratory Data Analysis

The analysis used:

* `groupby()`
* Aggregations
* Pivot tables
* Filtering
* Customer segmentation
* Churn-rate calculations
* Revenue analysis
* Contract-level comparisons
* Geographic analysis
* Time-based analysis

---

## 📉 Visualizations

The project uses Matplotlib and Seaborn to visualize:

* Overall churn vs retention
* Monthly vs annual churn
* Churn by subscription plan
* Churn by state
* Churn trends over time
* Revenue impact
* Customer segmentation

---

## 💡 Business Recommendation

The strongest finding from the analysis was the significant difference between monthly and annual churn.

A potential retention strategy would be to:

> **Identify high-risk monthly subscribers and encourage migration toward annual plans through targeted retention offers.**

This strategy could potentially improve retention and increase long-term customer value.



## 🚀 Skills Demonstrated

This project demonstrates practical experience with:

**SQL**

* Data extraction
* Filtering
* Aggregation
* Joins
* Relational data analysis

**Python**

* Pandas
* NumPy
* Data cleaning
* Feature engineering
* EDA

**Visualization**

* Matplotlib
* Seaborn
* Business-oriented charts

**Analytics**

* Churn analysis
* Customer segmentation
* Revenue impact analysis
* CLTV analysis
* Business recommendations

---

## 📌 Conclusion

This project helped demonstrate how raw relational customer data can be transformed into actionable business insights using **SQL and Python**.

The analysis identified a major churn disparity between monthly and annual subscribers and quantified the resulting revenue and CLTV impact, providing a foundation for targeted retention strategies.

---
