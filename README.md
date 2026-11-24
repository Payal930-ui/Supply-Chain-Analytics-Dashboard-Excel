# 📊 Supply Chain Analytics Dashboard | Excel Data Analysis Project

![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-Data%20Analytics-green)
![Project](https://img.shields.io/badge/Project-Supply%20Chain%20Analysis-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 1. Project Overview

The **Supply Chain Analytics Dashboard** is an end-to-end data analysis project developed using Microsoft Excel to evaluate supply chain operations, shipment performance, supplier expenditure and delivery efficiency.

The project analyzes **1,000 shipment records across 2024–2025**, transforming raw operational data into meaningful business insights through data preparation, exploratory data analysis (EDA), KPI development and interactive visualization.

The primary objective is to understand how different factors, such as suppliers, product categories, shipping modes and carriers, influence overall supply chain performance.

Rather than simply visualizing data, this project focuses on following a structured Data Analytics workflow to identify patterns, evaluate performance and support data-driven business decisions.

---

## 🎯 2. Business Objectives

The analysis focuses on answering the following business questions:

- What is the overall shipment volume and supply chain expenditure?
- Which suppliers contribute the highest expenditure?
- Which product categories account for the highest costs?
- How efficiently are different shipping modes performing?
- Which shipping carriers demonstrate better delivery performance?
- What percentage of shipments are delivered on time?
- What are the average delivery days?
- How do shipment volumes and trends vary across months and years?

---

## 📂 3. Dataset Description

**Dataset Name:** Supply Chain Dataset

| Dataset Information | Details |
|---|---|
| Total Records | 1,000 |
| Original Columns | 11 |
| Calculated Columns | 4 |
| Total Columns After Preparation | 15 |
| Time Period | 2024–2025 |
| File Format | Excel (.xlsx) |

### Original Dataset Columns

The dataset initially contained 11 columns:

| Column Name | Description |
|---|---|
| Shipment ID | Unique identifier for each shipment |
| Order Date | Date when the order was placed |
| Supplier Name | Name of the supplier |
| Product Category | Category of the supplied product |
| Quantity | Quantity of products shipped |
| Total Cost | Total cost associated with the shipment |
| Ship Date | Date when the shipment was dispatched |
| Delivery Date | Actual date of delivery |
| Shipping Carrier | Carrier responsible for transportation |
| Shipping Mode | Transportation method used |
| On-Time Delivery | Indicates whether the shipment was delivered on time (Yes/No) |

### Calculated Columns Created

To support deeper analysis, I created four additional columns.

| Calculated Column | Calculation | Purpose |
|---|---|---|
| Delivery Days | Delivery Date - Ship Date | Measures transportation and delivery duration |
| Order to Delivery Days | Delivery Date - Order Date | Measures total order fulfillment time |
| Order Year | YEAR(Order Date) | Enables yearly analysis |
| Order Month | TEXT(Order Date,"yyyy-mm") | Enables monthly trend analysis |

These calculated fields helped make the dataset more suitable for time-based analysis and delivery performance evaluation.

---

## 🔄 4. Data Analytics Roadmap / Project Workflow

The project follows a structured Data Analytics lifecycle.

### Step 1: Data Understanding

- Explored the dataset structure and its 11 original columns.
- Identified important business variables.
- Understood supplier, product, shipment and delivery-related information.
- Identified relevant metrics for supply chain performance analysis.

### Step 2: Data Cleaning & Preparation

- Reviewed the dataset for consistency.
- Checked the structure and data types of relevant columns.
- Worked with date fields to support time-based analysis.
- Created calculated columns for delivery duration, order fulfillment time, year and month.
- Prepared the data for further analysis.

### Step 3: Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand different dimensions of supply chain operations.

**Areas explored:**

- Shipment distribution.
- Supplier-wise expenditure.
- Product category expenditure.
- Shipping mode performance.
- Shipping carrier performance.
- Monthly shipment trends.
- Delivery efficiency.

### Step 4: KPI Development

Developed five key performance indicators to monitor overall supply chain performance.

| KPI | Calculation / Logic |
|---|---|
| Total Shipments | Count of Shipment IDs |
| Total Cost | Sum of Total Cost |
| Total Quantity | Sum of Quantity |
| On-Time Delivery % | On-Time Shipments / Total Shipments × 100 |
| Average Delivery Days | Average of Delivery Days |

### Step 5: Data Visualization

Created five interactive analytical visualizations to communicate findings effectively.

The dashboard covers:

1. Supplier-wise expenditure analysis.
2. Product category expenditure analysis.
3. Shipping mode performance analysis.
4. Shipping carrier performance analysis.
5. Monthly shipment trend analysis.

### Step 6: Interactive Dashboard Development

Developed an interactive Excel dashboard using Pivot Tables, Pivot Charts and Slicers.

Implemented five slicers:

- Supplier Name
- Product Category
- Shipping Mode
- Shipping Carrier
- Order Year

These slicers allow users to filter the dataset dynamically and explore different business dimensions.

### Step 7: Insights & Business Interpretation

Analyzed the results to identify operational patterns, expenditure distribution and delivery performance gaps.

The final dashboard provides a consolidated view of supply chain performance and supports data-driven decision-making.

---

## 📈 5. Key Performance Indicators (KPIs)

The dashboard includes five major KPIs.

| KPI | Result |
|---|---:|
| Total Shipments | 1,000 |
| Total Cost | 8,275,966.82 |
| Total Quantity | 2,398,051 |
| On-Time Delivery | 79.7% |
| Average Delivery Days | 9.51 Days |

These indicators provide an overview of shipment volume, expenditure, product quantity and delivery efficiency.

---

## 💡 6. Key Insights & Findings

Based on the analysis, the following insights were identified:

### 1. Delivery Performance
- Overall on-time delivery rate was 79.7%.
- 203 shipments were identified as late.
- This highlights an opportunity to improve delivery reliability.

### 2. Product Category Analysis
- Machinery recorded the highest expenditure among the analyzed product categories.
- Category-wise expenditure analysis helps understand where supply chain spending is concentrated.

### 3. Shipping Mode Analysis
- Air shipping recorded 100% on-time delivery.
- Sea shipping recorded 61.4% on-time delivery.
- This indicates a considerable difference in delivery performance across transportation modes.

### 4. Shipping Carrier Analysis

On-time delivery performance by carrier:

| Shipping Carrier | On-Time Delivery |
|---|---:|
| DHL | 77.22% |
| FedEx | 81.19% |
| Local | 80.26% |
| UPS | 79.87% |

FedEx recorded the highest on-time delivery percentage among these carriers.

### 5. Supplier Analysis
- Compared expenditure across different suppliers.
- Identified the supplier contributing the highest expenditure.
- Supplier-level analysis provides visibility into purchasing and spending patterns.

### 6. Monthly Trend Analysis
- Analyzed shipment trends across months and years.
- Used the Order Month and Order Year fields to explore changes in shipment activity over time.

---

## 📊 7. Dashboard Features

The final dashboard brings together important supply chain metrics and visualizations.

**Key Features:**

- Five KPI cards.
- Five analytical charts.
- Five interactive slicers.
- Supplier performance analysis.
- Product category expenditure analysis.
- Shipping mode and carrier analysis.
- Monthly shipment trend analysis.
- Dynamic filtering and interactive reporting.

The dashboard allows users to explore the data from different perspectives without manually modifying the source dataset.

---

## 🛠️ 8. Tools & Technologies

| Tool / Feature | Application |
|---|---|
| Microsoft Excel | Data analysis and dashboard development |
| Excel Formulas | Calculated columns and KPI calculations |
| Pivot Tables | Data summarization and analysis |
| Pivot Charts | Data visualization |
| Slicers | Interactive filtering |
| KPI Cards | Performance monitoring |
| Data Visualization | Presenting analytical findings |

---



## 🎓 9. Key Learnings

Working on this project strengthened my practical understanding of:

- Data Understanding and Preparation.
- Exploratory Data Analysis (EDA).
- Calculated Columns and Excel Formulas.
- KPI Development and Performance Monitoring.
- Supplier and Product Category Analysis.
- Time-Based Trend Analysis.
- Data Visualization and Dashboard Design.
- Interactive Reporting.
- Translating analytical findings into business insights.

### Final Takeaway

This project reinforced my understanding that Data Analytics is not just about creating charts or dashboards.

It involves understanding business requirements, preparing data, exploring patterns, analyzing performance and communicating insights that can support better decisions.

**Strong fundamentals build the foundation for advanced analytical skills.**

---

## 👩‍💻 Author

**Payal Kumari**

Data Analytics | Python | SQL | Microsoft Excel | Data Visualization

- LinkedIn: [Payal Kumari](https://www.linkedin.com/in/payalkumari101)
- GitHub: [Payal930-ui](https://github.com/Payal930-ui)

---

⭐ If you find this project interesting, feel free to explore the repository!
