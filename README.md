# Customer Shopping Behavior Data Analytics Project

## Overview

This project delivers an **end-to-end data analytics solution** focused on customer shopping behavior. It covers the complete analytics lifecycle — from raw data ingestion and exploration to SQL-driven insights, interactive dashboard creation, and business reporting.

The main objective is to uncover customer purchasing patterns, identify key sales drivers, and provide actionable insights to support data-driven decision-making.

---

## Dataset

**File:** `customer_shopping_behavior.csv`

### Description

The dataset contains transactional and demographic information related to customer purchases. It includes:

* Customer demographics (age, gender, location)
* Purchase behavior (product category, frequency, spending amount)
* Transaction details (payment method, seasonality, discounts)
* Behavioral indicators (loyalty patterns and preferences)

### Data Source

Provided as part of the business case scenario for customer behavior analysis.

---

## Tools & Technologies

* **Python** (Pandas, NumPy, Matplotlib, Seaborn)
* **PostgreSQL**
* **Power BI**
* Jupyter Notebook
* SQL
* Microsoft PowerPoint

---

## Project Workflow

### 1️. Data Loading

* Imported the CSV dataset into Python using Pandas.
* Validated schema, column types, and basic statistics.

---

### 2️. Exploratory Data Analysis (EDA)

Performed EDA to understand data distribution and customer behavior patterns:

* Purchase frequency trends
* Revenue distribution across categories
* Seasonal sales patterns
* Customer segmentation insights

Visualizations were created to identify correlations and anomalies.

---

### 3️. Data Cleaning

Key cleaning steps included:

* Handling missing values
* Removing duplicates
* Standardizing categorical values
* Outlier detection and treatment
* Formatting date and numeric columns

---

### 4️. SQL Analysis using PostgreSQL

**File:** `customer_behavior_sql_queries.sql`

The cleaned dataset was imported into PostgreSQL for advanced querying.

Sample analyses included:

* Top-selling product categories
* Monthly and seasonal revenue trends
* High-value customer identification
* Average order value by region
* Repeat customer behavior analysis

---

### 5️. Power BI Dashboard

**File:** `customer_behavior_dashboard.pbix`

An interactive dashboard was built to visualize KPIs and trends.

### Key Features

*  Sales and revenue overview
*  Customer segmentation by demographics
*  Product category performance
*  Time-based trend analysis
*  Interactive filters (gender, region, category, season)

The dashboard allows stakeholders to drill down into specific business questions dynamically.

---

### 6️. Business Report

**File:** `Customer Shopping Behavior Analysis.pdf`

The report includes:

* Business problem definition
* Data preparation methodology
* Analytical approach
* Visual insights
* Key findings
* Strategic recommendations

---

### 7️. Presentation Deck

**File:** `Business Problem Document.pdf`

A concise PowerPoint presentation summarizing:

* Project objectives
* Analytical workflow
* Dashboard insights
* Business impact
* Recommendations

---

##  Key Results & Insights

The analysis revealed:

* Strong seasonal purchasing patterns influencing revenue
* Specific product categories driving the majority of sales
* Clear differences in spending behavior across customer segments
* High-value customers contributing disproportionately to total revenue
* Opportunities for targeted promotions and loyalty strategies

---

##  How to Run the Project

### 1️. Clone the Repository

```bash
git clone <your-repository-url>
```

---

### 2️. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 3️. Run Python Analysis

Open and execute:

```bash
Customer_Shopping_Behavior_Analysis.ipynb
```

or

```bash
python analytics.py
```

(if converted to script)

---

### 4️. Run PostgreSQL Queries

1. Import the CSV file into PostgreSQL
2. Execute:

```sql
customer_behavior_sql_queries.sql
```

---

### 5️. Open Power BI Dashboard

Open:

```
customer_behavior_dashboard.pbix
```

in Power BI Desktop.

---

### 6️. View Reports & Presentation

*  Report: `Customer Shopping Behavior Analysis.pdf`
*  Presentation: `Business Problem Document.pdf`

---

## Conclusion

This project demonstrates a **full-cycle analytics workflow**, integrating Python, SQL, and Power BI to transform raw data into actionable business insights.

It highlights:

* Strong data preparation practices
* Effective visualization techniques
* Business-focused storytelling
* End-user dashboard usability

The solution provides a scalable framework that can be adapted to real-world retail and e-commerce analytics use cases.

---
