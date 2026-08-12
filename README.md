# E-Commerce Sales Dashboard – Power BI

## 📊 Project Overview

This project is an interactive **E-Commerce Sales Dashboard built using Microsoft Power BI**. The dashboard provides a comprehensive view of sales performance, profitability, customer contribution, product categories, payment methods, and geographical sales distribution.

The dashboard is designed to help business users quickly understand key sales metrics and identify important trends and high-performing segments.

---

## 🎯 Project Objectives

The main objectives of this dashboard are to:

- Monitor overall sales and profitability performance
- Analyze monthly profit trends
- Identify the top-performing states by sales amount
- Identify the top customers by sales amount
- Understand quantity distribution across payment methods
- Analyze product category and sub-category performance
- Track key business KPIs
- Enable interactive analysis using quarter-level filtering

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **DAX (Data Analysis Expressions)**
- **Power Query**
- **Data Visualization**
- **Data Modeling**

---

## 📌 Dashboard Features

### 1. KPI Cards

The dashboard includes four key KPI cards to provide a quick overview of business performance:

- **Total Profit** – Displays the total profit generated.
- **Total Amount** – Displays the total sales amount.
- **Total Quantity** – Displays the total quantity of products sold.
- **Average Order Value (AOV)** – Calculates the average value of an order using a DAX measure.

These KPIs provide users with an immediate understanding of overall business performance.

---

### 2. Profit by Month

A monthly trend visualization shows the **sum of profit by month**.

This helps identify:

- Monthly profit trends
- High-performing months
- Low-performing months
- Changes in profitability over time

---

### 3. Sales Amount by State

A geographical sales analysis shows the **sum of sales amount by state**.

A **Top 3 filter** has been applied to highlight the three states generating the highest sales amount.

This allows users to quickly identify the strongest-performing geographical markets.

---

### 4. Sales Amount by Customer

The dashboard analyzes the **sum of sales amount by customer name**.

A **Top 3 filter** is applied to identify the customers contributing the highest sales amount.

This helps highlight high-value customers and understand customer-level sales contribution.

---

### 5. Quantity by Payment Mode

A visualization displays the **quantity of products sold by payment mode**.

This provides insight into customer payment preferences and helps compare transaction volumes across different payment methods.

---

### 6. Quantity by Category

The dashboard displays the **total quantity sold across different product categories**.

This helps identify which product categories have the highest sales volume.

---

### 7. Quantity by Sub-Category

A detailed analysis of **quantity sold by sub-category** provides deeper insight into product-level performance.

This can help identify:

- High-demand sub-categories
- Low-performing product segments
- Areas that may require further business analysis

---

## 🎛️ Interactive Quarter Slicer

A **Quarter slicer** has been added to the dashboard to allow users to filter the entire report by quarter.

Users can select different quarters to dynamically analyze:

- Sales amount
- Profit
- Quantity
- Average Order Value
- Customer performance
- State performance
- Category and sub-category performance
- Payment mode distribution

This makes the dashboard interactive and allows users to perform focused period-based analysis.

    DISTINCTCOUNT('Sales'[Order ID])
