![SQL](https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=database&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=FFD43B)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

# 🛒 E-Commerce Product Analytics

## 📌 Executive Summary

Understanding customer behavior throughout the online shopping journey is essential for improving conversion rates, increasing revenue, and delivering better customer experiences. This project demonstrates an end-to-end Product Analytics workflow using **MySQL, SQL, Python, and Tableau**.

Starting from raw e-commerce event data, the project builds a complete analytics pipeline by importing data into MySQL, performing SQL-based business analysis, connecting the database to Python for exploratory analysis and feature engineering, and finally creating interactive Tableau dashboards for business reporting.

The project simulates how Product Analysts and Data Analysts transform raw customer interaction data into actionable business insights.

---

# 🎯 Business Problem

E-commerce platforms collect millions of customer interaction events such as product views, add-to-cart actions, and completed purchases. While this data is valuable, businesses often struggle to understand customer behavior, identify conversion bottlenecks, and optimize product performance.

This project aims to analyze customer interactions across the purchase funnel to uncover behavioral patterns, improve product performance, and support data-driven business decisions.

---

# 🎯 Business Objectives

The project aims to:

* Analyze customer behavior across the purchase funnel.
* Measure product conversion rates.
* Identify high-performing product categories.
* Evaluate customer engagement patterns.
* Analyze revenue and transaction trends.
* Build interactive dashboards for business reporting.
* Support product optimization using data-driven insights.

---

# 📂 Dataset Overview

The project uses a real-world e-commerce behavioral dataset consisting of customer interaction events.

### Files Used

* `events.csv`
* `category_tree.csv`
* `item_properties_part1.csv`
* `item_properties_part2.csv`

### Dataset Includes

* Customer Events
* Product Information
* Product Categories
* Product Properties
* Transaction History
* Event Timestamps

---

# 🏗 Project Architecture

```text
Raw CSV Files
(events.csv,
category_tree.csv,
item_properties_part1.csv,
item_properties_part2.csv)

            │
            ▼

      MySQL Database

            │
            ▼

      SQL Analysis

    • Database Design
    • Data Cleaning
    • Business Queries
    • Analytical Views

            │
            ▼

      Python Analysis

    • Pandas
    • Data Cleaning
    • Feature Engineering
    • Exploratory Data Analysis

            │
            ▼

     Processed Dataset

            │
            ▼

     Tableau Dashboards

            │
            ▼

Business Insights & Recommendations
```

---

# ❓ Business Questions

The project answers the following business questions:

* How many customers progress through each stage of the purchase funnel?
* Which product categories generate the highest transactions?
* Which products have the highest customer engagement?
* Which products experience the highest cart abandonment?
* Which customers generate the highest revenue?
* How does customer activity change over time?
* Which products perform best across categories?
* What business insights can improve customer conversion?

---

# 🛠️ Tech Stack

### Database

* MySQL

### Query Language

* SQL

### Programming

* Python

### Libraries

* Pandas
* NumPy
* SQLAlchemy
* Matplotlib

### Visualization

* Tableau

### Development Environment

* Jupyter Notebook

### Version Control

* Git
* GitHub

---

# 🔄 Project Workflow

### Phase 1 — Data Collection

* Import CSV files into MySQL.
* Create relational database tables.

### Phase 2 — SQL Analytics

* Data Cleaning
* Joins
* Views
* Business Queries

### Phase 3 — Python Analytics

* Database Connection
* Exploratory Data Analysis
* Feature Engineering
* Customer Analysis

### Phase 4 — Business Intelligence

* Tableau Dashboard Development
* KPI Reporting
* Business Storytelling

---

# 📊 Analysis Performed

The project includes:

* Customer Behavior Analysis
* Product Performance Analysis
* Purchase Funnel Analysis
* Category Performance Analysis
* Revenue Analysis
* Transaction Analysis
* Customer Engagement Analysis
* Product Analytics

---

# 📈 Dashboard Overview

The Tableau dashboard includes:

* Executive Summary
* Customer Funnel Analysis
* Product Performance
* Category Performance
* Revenue Trends
* Customer Activity
* Product Conversion Analysis

---

# 📈 Key Insights

* Product views significantly exceed completed purchases, indicating opportunities to improve conversion rates.
* Customer engagement varies across product categories.
* Certain categories consistently generate higher transaction volumes.
* Customer behavior analysis identifies important drop-off points in the purchase funnel.
* SQL and Tableau together provide comprehensive business reporting for product teams.

---

# 💡 Business Recommendations

Based on the analysis:

* Improve checkout flow to reduce cart abandonment.
* Optimize product recommendations for returning users.
* Increase visibility of high-converting products.
* Personalize promotions using customer behavior.
* Continuously monitor product performance using interactive dashboards.

---

# 📁 Project Structure

```text
ecommerce-product-analytics/
│
├── data/
│   ├── raw/
│
├── notebooks/
│
├── sql/
│   ├── create_tables.sql
│   ├── import_data.sql
│   ├── views.sql
│   └── business_queries.sql
│
├── tableau/
│   └── Ecommerce_Product_Analytics.twbx
│
├── images/
│
├── README.md
├── requirements.txt

```

---

# 💼 Skills Demonstrated

### Programming

* Python

### Database

* MySQL

### Query Language

* SQL

### Data Analysis

* Pandas
* NumPy
* Data Cleaning
* Feature Engineering
* Exploratory Data Analysis

### Product Analytics

* Customer Behavior Analysis
* Purchase Funnel Analysis
* Product Performance Analysis
* Business Analytics

### Visualization

* Tableau
* Dashboard Design
* Data Storytelling

---

# 🔮 Future Enhancements

* Customer Segmentation
* Cohort Analysis
* A/B Testing
* Customer Lifetime Value (CLV)
* Churn Prediction
* Recommendation System Analytics

---

# 👤 Author

**Ajay Mundari**

SQL | Python | Tableau | Product Analytics | Data Analytics

If you found this project useful, please consider giving it a ⭐ on GitHub.
