### **🚀 Project #1: Adventure Works Executive Summary Dashboard**

**Type:** Data Visualization | **Tool:** Power BI

**Overview:** 
Developed an executive dashboard for *Adventure Works* showcasing sales, customer, and product insights for data-driven decision-making.

**Key Highlights:**

* Created DAX measures and established data relationships for accurate reporting.
* Implemented forecasting using a continuous Date Table and dynamic DAX measures to predict future sales trends (Seasonality = 12, Confidence = 99%). Seasonality = 12 tells the forecasting model to look for repeating patterns every 12 units
* Enabled Q&A functionality for real-time, conversational data exploration by executives.

---

### 🚀Power BI Project #2 – Sales Report Dashboard

This dashboard was developed as a learning exercise inspired by a YouTube tutorial project.
I followed the steps carefully to understand how to connect Power BI with Python and Excel, analyzed and build interactive dashboards.

### Sheet 1 – Overview & Time-Series Analysis

* **Total Revenue**
* **Total Profit**
* **Profit Margins**
* **Total Orders**
* **Monthly Revenues (Line Chart)** – Track revenue trends over time
* **Monthly Profit (Line Chart)** – Track profit trends over time
* **Order Value Spectrum (Column Chart)** – Counts of orders per spending range
* **Unit Price vs Profit Margin (Scatter Plot)** – Identify price ranges with higher profits

### Sheet 2 – Product & Customer Analysis

* **Product Name vs Revenue (Bar Chart)**
* **Product Name vs Profit Margin % (Bar Chart)** – Highlight the most profitable products
* **Total Revenue vs Average Profit Margin (Scatter Plot)** – Point size represents total orders
* **3 Pie Charts (Export, Distributors, Wholesale Customers)**

  * Revenue, Profit, and Profit Margin %

### Sheet 3
* **Interactive Top/Bottom 5 Bar Charts**

  * **Toggle Buttons:** “Top 5” and “Bottom 5”
  * **Bar Charts:**

    1. Customers vs Revenue
    2. Customers vs Profit Margin %
    3. States vs Revenue
  * Switch between highest 5 and lowest 5 values for each chart
* **Region Analysis Pie Charts**

  * Region vs Revenue
  * Region vs Profit Margin %
  * Regions: Northeast, Southwest, Midwest, [Fourth Region]

* **Total Profit by State (Map)** – Circle size indicates profit magnitude per state

> ---
### 🚀Power BI Project #3: Waste Management Dashboard — Union Councils of Peshawar

## Overview

This project combines **GIS spatial analysis** and **Power BI** to visualize and analyze waste generation across Peshawar’s Union Councils (UCs). It helps identify high-waste areas, inefficient UCs, and optimizes waste collection routes.

## GIS Analysis

* **Choropleth Map:** Visualizes waste generation per UC (green = low, red = high).
* **Waste per Capita & Vehicle:** Identifies inefficient UCs.
* **Hotspot Analysis (Getis-Ord Gi*):** Detects clusters of high or low waste.
* **Route Optimization:** Generates 5–15 min collection and dumping coverage areas for efficient waste management.
* **Outputs:** CSVs for Power BI, PNGs, shapefiles, and GeoJSON polygons.

## Power BI Dashboard

### Sheet 1 — Waste Management Dashboard

* **Cards:** Total waste, population, average waste per vehicle, UC with highest waste.
* **Map:** Bubble map of UCs (size = waste, color = population).
* **Scatter Plot:** Waste vs. complaints per UC (bubble size = population).
* **Slicer:** Filter by UC name.
* **Top/Bottom Buttons:**

  * **Top Button:** Displays top 8 UCs by waste (red bar chart + pie chart)
  * **Bottom Button:** Displays bottom 8 UCs by waste (green bar chart + pie chart)
* **Table:** UC Name | Total Waste | Waste per Capita | Waste per Vehicle

### Sheet 2 — GIS Results (press the button in up right corner to be directed to it)

* Displays exported GIS images:

  * Waste Generation Choropleth
  * Hotspot Analysis
  * Route Optimization / Service Area Map
 

## Tools Used

* **ArcGIS Pro** — GIS analysis and route optimization
* **Power BI** — Interactive dashboard and visualizations

## IMAGES OF DASHBOARD ARE UPLOADED in REPO
---
