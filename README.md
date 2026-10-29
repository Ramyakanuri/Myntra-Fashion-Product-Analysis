# Myntra Fashion Product Analysis

## Project Overview

This project analyzes Myntra fashion product catalog data using Microsoft Power BI. It explores product availability across gender categories, brand representation, pricing patterns, and product catalog characteristics through an interactive dashboard.

The dashboard is designed to help users explore how products are distributed across brands, price segments, gender categories, and other catalog attributes.

## Project Objectives

- Analyze product distribution across gender categories.
- Identify brands with the highest number of listed products.
- Examine overall product pricing and compare average prices across gender categories.
- Identify the highest-priced products in the catalog.
- Analyze the distribution of products across price segments.
- Compare brands based on their average number of product images.
- Build an interactive dashboard to explore catalog data using filters.

## Dataset

- **Dataset:** Myntra Fashion Product Catalog
- **Total Products:** 12,491
- **Distinct Brands:** 677
- **Source:** [Myntra Fashion Product Analysis Dataset](https://github.com/anmolmalviya05/Myntra-Fashion-Product-Analysis)

The dataset contains product IDs, product names, brand names, gender categories, prices, image counts, product descriptions, and primary colors.

This dataset represents product catalog information rather than actual transaction or sales data.

## Tools and Technologies

- **Microsoft Excel:** Data inspection and preparation.
- **Power Query:** Data cleaning, transformation, and preparation.
- **Microsoft Power BI Desktop:** Data modeling, DAX measures, interactive visualizations, and dashboard development.

## Data Preparation

The dataset was cleaned and prepared using Excel Power Query before being analyzed in Power BI.

Data preparation included reviewing the dataset, handling missing or blank values, and preparing the data for analysis. Blank values were replaced with "Unknown" where appropriate, and the prepared data was used to build the dashboard.

## Analysis Performed

### 1. Product Overview
- Total product count.
- Distinct brand count.
- Average product price.
- Average number of images per product.

### 2. Pricing Analysis
- Average product price by gender.
- Product price distribution across price segments.
- Comparison of the highest-priced products.
- Identification of the leading price segment.

### 3. Brand Analysis
- Top 10 brands by product count.
- Top 10 brands by average number of product images.
- Top 10 brand product concentration.

### 4. Gender Distribution
- Product distribution across gender categories.
- Comparison of average listed prices across gender categories.

### 5. Catalog Characteristics
- Analysis of product image counts.
- Comparison of catalog representation across brands and categories.

## Dashboard Features

The Power BI dashboard includes:

- KPI cards for key catalog metrics.
- Interactive slicers for Gender, Brand, Primary Color, and Price Range.
- Bar charts for brand and product comparisons.
- A price distribution chart.
- A donut chart showing product distribution by gender.
- Insight cards highlighting the leading price segment, most common price segment share, and brand with the highest average image count.
- A welcome page with navigation to the fashion analysis dashboard.

The slicers allow users to explore the catalog dynamically and examine different product segments.

## Key Findings

The dashboard summarizes product and brand counts, average listed pricing, gender-wise product distribution, price-segment representation, and brand-level catalog characteristics.

Specific numerical findings should be reported only after validating the corresponding Power BI measures against the prepared dataset.

**Scope limitation:** The dataset supports product catalog and pricing analysis. It does not contain actual sales, revenue, profit, customer purchases, conversion rates, or inventory performance data. Therefore, the project does not draw conclusions about sales performance or customer purchasing behavior.

## Project Files

- `Myntra_Fashion_Product_Analysis.pbix` — Interactive Power BI dashboard.
- `screenshots/welcome_page.png` — Dashboard welcome page.
- `screenshots/fashion_analysis_dashboard.png` — Fashion analysis dashboard.

## Conclusion

This project demonstrates the use of Excel Power Query and Power BI to prepare, analyze, and visualize fashion product catalog data. The interactive dashboard provides a structured view of brand representation, pricing patterns, gender-wise product availability, and catalog characteristics.


## Dashboard Preview

### Welcome Page
![Myntra Welcome Page](screenshots/welcome_page.png)

### Fashion Analysis Dashboard
![Fashion Analysis Dashboard](screenshots/fashion_analysis_dashboard.png)
