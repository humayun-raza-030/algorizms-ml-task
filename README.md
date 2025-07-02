# 🚚 Uqaab Shipment Logistics Analysis

Welcome to the logistics analysis module for **Uqaab**, a digital platform modernizing Pakistan's trucking industry. This repository explores real-world freight data to uncover operational insights that drive smarter decision-making.

---

## 📦 Project Overview

Using Python, pandas, and Seaborn, we analyze shipment records to answer key business questions:
- What are the most common shipment routes?
- Are our drivers and trucks being utilized efficiently?
- Which regions are most active in terms of shipment volume?
- How can fuel consumption and delivery times be optimized?

This analysis simulates backend logic for the admin control panel of Uqaab’s logistics dashboard.

---

## 📁 Dataset

The dataset includes the following fields for each shipment:

| Column               | Description                                      |
|----------------------|--------------------------------------------------|
| `shipment_id`        | Unique shipment identifier                       |
| `shipper_id`         | Shipper reference                                |
| `carrier_id`         | Carrier reference                                |
| `truck_id`           | Assigned truck                                   |
| `truck_type`         | Truck size/class (Small, Medium, Large)          |
| `fuel_type`          | Fuel used (Hybrid, Petrol)                       |
| `origin`             | Shipment starting location                       |
| `destination`        | Shipment end location                            |
| `cargo_type`         | Type of goods transported                        |
| `distance_km`        | Distance between origin and destination          |
| `estimated_time_hrs` | Estimated travel time                            |
| `actual_time_hrs`    | Actual delivery time                             |
| `fuel_consumed_liters` | Fuel used during shipment                     |
| `driver_hours`       | Assigned driver hours                            |
| `load_date`          | Start date of shipment                           |
| `delivery_date`      | Scheduled delivery date                          |
| `status`             | Current shipment status (Delivered, Delayed)     |

---

## 🧪 Analysis Performed

### 📏 Key Metrics
- Average shipment distance
- Driver utilization rates
- Fuel efficiency per truck type
- Top 5 most frequent shipment routes
- Shipment volume by region

### 📊 Visualizations
- Histogram of shipment distances
- Bar chart of top shipping routes
- Boxplot of driver utilization by truck type
- Stacked bar of shipment counts per region
- Bar chart of km per liter by truck class

Each chart is accompanied by business insights and recommendations, making the findings actionable for logistics managers.

---

## 🛠️ Technologies Used

- Python 3.x
- pandas
- matplotlib
- seaborn
- Jupyter Notebook

---

## 📈 Output Preview

All results, including visualizations and summary insights, are available in the [`shipment_analysis.ipynb`](./shipment_analysis.ipynb) notebook.

---

## 📃 Summary

This analysis provides a strong foundation for operational decision-making inside the Uqaab platform. By combining data wrangling, metric analysis, and visualization storytelling, we simulate the backend dashboard logic that drives Uqaab's core KPIs.

---
