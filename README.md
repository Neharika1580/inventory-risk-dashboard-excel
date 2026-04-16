# Inventory Risk Analysis Dashboard (Excel)

## Overview
This project is an Excel-based inventory analysis solution designed to monitor stock health, identify high-risk products, and support data-driven reorder decisions. It simulates a real-world inventory scenario by incorporating stock levels, sales rates, and supplier lead times.

## Problem Statement
Businesses often face stockouts or overstocking due to poor visibility into inventory trends. This dashboard addresses that by providing a structured way to track stock risk and prioritize actions.

## Key Features
- **KPI Tracking:** Total products, critical items, percentage of critical stock, total inventory value, and average days of stock
- **Stock Risk Classification:** Products categorized as Critical, Low, or Safe based on stock levels, sales rate, and lead time
- **Category-wise Analysis:** Identifies high-risk product categories using pivot-based summaries
- **Supplier Risk Analysis:** Highlights suppliers contributing to stock risk based on lead time and product availability
- **Interactive Dashboard:** Slicers enable dynamic filtering across categories and suppliers
- **Product Lookup Tool:** XLOOKUP-based feature to retrieve real-time product details using Product ID

## Tools & Techniques Used
- Microsoft Excel
- Pivot Tables & Pivot Analysis
- Conditional Formatting (Heatmaps & Data Bars)
- XLOOKUP for dynamic data retrieval
- Structured Tables for scalable data handling

## Business Impact
- Enables quick identification of critical stock items
- Helps prioritize restocking decisions based on risk
- Improves visibility into supplier performance and delays
- Provides a centralized view of inventory health

## File
- `Inventory_Risk_Dashboard.xlsx`
