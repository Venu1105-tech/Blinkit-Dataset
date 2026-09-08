# 📊 Blinkit Data Analysis Project

A comprehensive end-to-end data analysis project focused on Blinkit (formerly Grofers), leveraging **Excel**, **SQL**, **Power BI**, and **Python** to extract insights, visualize KPIs, and support data-driven decision-making.

---

## 📁 Dataset Used

- [Blinkit Grocery Data.xlsx](Blinkit%20Grocery%20data.xlsx)

---

## 🚀 Project Overview

The objective of this project is to analyze Blinkit's retail sales, outlet metrics, and inventory distribution to identify revenue patterns, measure performance across outlet types, and generate actionable business insights through an interactive Power BI dashboard.

---

## 🧰 Tools & Technologies Used

* **Excel**: Data inspection, raw dataset preprocessing, and validation.
* **SQL**: Analytical queries, aggregations, window functions, and KPI generation.
* **Power BI**: Interactive KPI cards, donut charts, funnel charts, and custom visual breakdowns.
* **Python**: Exploratory Data Analysis (EDA), missing value handling, and distribution analysis.

---

## 📈 Dashboard Preview

![Blinkit Dashboard](Blinkit%20Grocery%20data.png)

---

## 📊 Key Performance Indicators (KPIs)

Based on the dashboard analysis:
* **Total Sales**: **$1.20M**
* **Average Sales**: **$141**
* **Number of Items Sold**: **8,523**
* **Average Customer Rating**: **3.9 / 5.0**

---

## 💡 Key Business Insights

* **Top Revenue Drivers**: **Fruits and Vegetables** ($0.18M) and **Snack Foods** ($0.18M) are the highest-selling categories, followed by **Household** ($0.14M) and **Frozen Foods** ($0.12M).
* **Fat Content Contribution**: Regular fat items represent the majority of sales volume compared to low-fat options ($776.32K vs. $425.36K).
* **Outlet Performance**:
  * **Supermarket Type 1** generates the highest total sales ($787.55K across 5,577 items).
  * **Medium-sized outlets** account for the largest revenue share ($507.90K), followed by **Small** ($444.79K) and **High** ($248.99K).
* **Location Demographics**: **Tier 3 locations** lead revenue generation at $472.13K, followed by **Tier 2** ($393.15K) and **Tier 1** ($336.40K).
* **Growth Peak**: Outlet establishment analysis highlights a significant peak in sales for outlets established around **2018** ($205K).

---

## 📂 Repository Structure

```text
├── Blinkit Grocery data.xlsx     # Cleaned dataset (8,523 rows, 12 features)
├── Blinkit Grocery data.png      # Power BI dashboard screenshot
├── blinkit_data.sql              # SQL queries for analysis and KPIs
├── blinkit_data_analysis.ipynb   # Python EDA and visualizations
└── README.md                     # Project documentation
