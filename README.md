# 🛒 TCS Forage Online Retail Data Simulation – Business Insights Project

## 📌 Project Overview

This project is a business data analysis simulation provided by **Tata Consultancy Services (TCS)** through **Forage**. It focuses on exploring, cleaning, and analyzing online retail transaction data to generate meaningful business insights. The project simulates the role of a business analyst working with real-world e-commerce data.

Key Goals:
- Clean the raw transaction data.
- Build visualizations to answer strategic business questions.
- Identify trends and provide actionable insights to senior leadership (CEO and CMO).

---

## 🧹 Data Cleaning Process

The raw data included invalid records such as:
- **Negative quantities** indicating returns.
- **Negative unit prices** due to data entry errors.

### ✅ Cleaning Rules Applied:
- **Exclude transactions** where `Quantity < 1`
- **Exclude transactions** where `UnitPrice < 0`

These filters were implemented using **conditional logic** and **Power BI / Excel transformations** before building visuals.

---

## 📊 Visualizations

Each business question was addressed on a **separate tab/page**, named by **question number** for clarity:

| Tab Name   | Visual Description |
|------------|--------------------|
| Q1         | Monthly Revenue Time Series for 2011 |
| Q2         | Top 10 Countries by Revenue and Quantity (excluding UK) |
| Q3         | Top 10 Customers by Revenue |
| Q4         | Country-wise Customer Count (Demand Insights excluding UK) |

---

## 📈 Tools Used

- **Power BI Desktop** (`.pbix`) – used to clean data, build dashboards, and generate insights.
  
---

## 📝 Business Questions Answered

1. **Monthly Revenue Trends (2011)** – Identify seasonality and dip/surge periods.
2. **Top Performing Countries** – Based on sales quantity and revenue (excluding UK).
3. **Top Customers** – Ranked by total revenue.
4. **Customer Demand by Country** – Measure demand using unique customer count.

---

## ✅ How to Run

1. Download the `.pbix` or `.twbx` file depending on your tool.
2. Open it in **Power BI Desktop** or **Tableau Desktop**.
3. Navigate to each tab to view insights.
4. Use slicers/filters for interactivity (where applicable).

---
