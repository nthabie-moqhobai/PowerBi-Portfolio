# 📊 Supply Chain & Inventory Analytics Dashboard

## 🔷 Project Summary
This project delivers a comprehensive Power BI solution designed to analyze retail sales performance, optimize inventory management, and surface demand-driven insights.
Rather than focusing on static reporting, the dashboard is built to support **data-driven decision-making across strategic, tactical, and operational levels**.

## 🎯 Business Context
Retail organizations often face a disconnect between inventory levels and actual customer demand. This leads to:
* Excess capital tied up in slow-moving stock
* Frequent stockouts of high-demand products
* Limited visibility into product performance
* Inefficient prioritization of inventory investment

## 🧠 Project Objectives
The solution was designed to:
* Track and interpret demand trends over time
* Measure inventory efficiency and utilization
* Identify high-value products using Pareto (ABC) analysis
* Detect early warning signals for stockout risk
* Enable detailed, product-level investigation through drill-through capabilities

## 🏗️ Data Model & Design
The data model follows a **star schema architecture** to ensure scalability, performance, and clarity.

### Core Tables:
* `Fact_InventorySales`
* `Dim_Product`
* `Dim_Date`
* `Dim_Store`

### Design Principles Applied:
* Centralized **Measures Table** to manage all DAX logic and improve maintainability
* **Single-direction filtering** to ensure consistent and predictable data behavior
* Hidden surrogate keys to enforce dimension-driven analysis and prevent misuse
* Context-aware calculations to ensure accuracy at different levels of granularity (e.g., ABC classification at product level)

This approach ensures the model remains **clean, efficient, and enterprise-ready**.

## 📈 Key Analytical Capabilities
* **Demand Analysis:** Month-over-Month and Year-over-Year trend evaluation
* **Inventory Efficiency:** Turnover rates and days of inventory coverage
* **Risk Monitoring:** Identification of potential stockouts and overstock scenarios
* **Product Prioritization:** Pareto (ABC) classification based on revenue contribution
* **Drill-Through Analysis:** Deep-dive into individual product performance

## 📊 Dashboard Structure
The report is organized into focused analytical layers:
* Executive Inventory Overview
* Sales, Demand & Regional Performance
* Inventory Risk & Action Insights
* Time Intelligence (Trend Analysis)
* Pareto (ABC) Product Segmentation
* Product Category Performance
* Product Drill-Through Analysis

## 🚀 Business Value
This solution enables stakeholders to:
* Reduce excess inventory and holding costs
* Minimize revenue loss due to stockouts
* Focus on high-impact products
* Improve demand forecasting and planning
* Make faster, insight-driven decisions

## 🛠️ Tools & Technologies
* Power BI (Data Modeling & Visualization)
* DAX (Business Logic & Calculations)
* Power Query (Data Transformation)

## 📌 Key Takeaway
Effective inventory management is not just about tracking stock — it’s about **aligning supply with demand signals**.
This project demonstrates how data can be transformed into a **decision-support system** that drives measurable business impact.
Open to remote opportunities in Power BI, Data Analytics, and Business Intelligence

