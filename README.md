# 📱 Amazon Smartphone Market Analysis (Python & Power BI)

## 🎯 Project Overview
This project presents an end-to-end data analysis workflow for the Amazon Smartphone market. The goal is to transform unstructured e-commerce data into actionable business insights using **Python** for Data Engineering & Feature Engineering, and **Power BI** for interactive analytics.

## 🛠️ Tools & Technologies Used
- **Python (Pandas, Re/Regex)**: Data Cleaning, Handling Missing Values, Category Filtering, and Feature Engineering.
- **Power BI**: Interactive Dashboard, DAX Measures, Slicers, Data Modeling, and Visualizations.

## 🔄 Project Steps
1. **Data Exploration**: Analyzed 340 initial records with duplicate items, missing values, and mixed categories.
2. **Data Cleaning**: 
   - Deduplicated data based on `ASIN` (340 → 315 records).
   - Filtered out non-smartphone categories (Landlines/Office phones) resulting in 237 clean smartphone records.
   - Fixed data types for prices and ratings.
3. **Feature Engineering**:
   - Extracted `Brand` from product titles.
   - Extracted `Storage_GB` using Regular Expressions (`Regex`).
   - Converted text sales figures (e.g., `4K+ bought`) to clean numeric values.
4. **Power BI Visualization**:
   - **Page 1 (Overview)**: High-level KPIs, Brand Distribution, Average Price & Ratings.
   - **Page 2 (Detailed Analysis)**: Price vs. Rating Scatter Plot, Storage Distribution, and Product Details Table.

## 📊 Recommendations
- Focus inventory allocation on high-rated products with stable sales velocity.
- Target `128GB` and `256GB` storage variants as the primary consumer choice.
