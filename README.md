# Amazon Product Analytics Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data%20Analysis-blue)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-green)
![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?logo=kaggle)

<p align="center">
  <img src="assets/dashboard-demo.gif" alt="Dashboard Demo" width="100%">
</p>

## Table of Contents

- [Overview](#overview)
- [Project Objectives](#project-objectives)
- [Dataset](#dataset)
- [Dashboard Pages](#dashboard-pages)
- [Features](#features)
- [Data Preparation](#data-preparation)
- [Technologies Used](#technologies-used)
- [Repository Structure](#repository-structure)
- [How to Open](#how-to-open)
- [Author](#author)

## Overview

This project presents an interactive **Power BI dashboard** developed to analyze Amazon product data using information on pricing, discounts, categories, ratings, and customer reviews.

The dashboard was designed to provide an executive-level overview while also allowing users to explore products, compare categories, evaluate pricing strategies, and analyze customer feedback through multiple interactive report pages.

---

## Project Objectives

The dashboard was developed to answer questions such as:

- How many products are available in the dataset?
- Which product categories contain the largest number of products?
- How are discounts distributed across the catalog?
- Which categories have the highest average prices?
- Which products stand out based on ratings and customer reviews?
- How can users efficiently explore products through interactive filtering?

---

## Dataset

This project uses the **Amazon Sales Dataset**, publicly available on Kaggle.

- **Dataset:** Amazon Sales Dataset
- **Author:** Karkavelraja J
- **Source:** https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset
- **License:** CC BY-NC-SA 4.0

The dataset contains over **1,400 Amazon products** with information including:

- Product details
- Categories
- Actual and discounted prices
- Discount percentages
- Customer ratings
- Rating counts
- Review titles and contents
- Product and image links

The dashboard was developed using the **amazon.csv** file after performing data cleaning and transformation in **Power Query**.

> **License Notice**
>
> This repository contains an analytical dashboard built from the Amazon Sales Dataset. The original dataset is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)** license.
>
> Please refer to the original Kaggle dataset page for the complete license terms and attribution requirements.

---

# Dashboard Pages

## Overview

<p align="center">
  <img src="images/overview.png" width="100%">
</p>

Provides a high-level summary of the dataset through KPIs and executive visualizations, allowing users to quickly understand the overall catalog.

Main indicators include:

- Total Products
- Total Reviews
- Average Price
- Average Discount
- Average Rating

---

## Category Analysis

<p align="center">
  <img src="images/category-analysis.png" width="100%">
</p>

Explores product distribution across categories, highlighting pricing, discounts, ratings, and catalog composition.

---

## Product Explorer

<p align="center">
  <img src="images/product-explorer.png" width="100%">
</p>

Allows detailed exploration of individual products, including pricing information, ratings, and product descriptions through interactive filtering.

---

## Pricing & Discounts

<p align="center">
  <img src="images/pricing-discounts.png" width="100%">
</p>

Analyzes pricing strategies by comparing actual prices, discounted prices, and discount percentages across different product categories.

---

## Customer Reviews

<p align="center">
  <img src="images/customer-reviews.png" width="100%">
</p>

Focuses on customer ratings and review metrics, helping identify highly rated products and overall customer satisfaction.

---

# Features

- Interactive dashboard with cross-filtering between visuals
- Executive KPI cards for key business metrics
- Category-based product analysis
- Product exploration with dynamic filtering
- Pricing and discount analysis
- Customer ratings and review insights
- Data cleaning and transformation using Power Query
- Business metrics calculated with DAX

---

# Data Preparation

Data preparation was performed entirely in **Power Query**, including:

- Data type conversion
- Removal of currency symbols
- Conversion of prices to numeric values
- Conversion of discount percentages to numeric format
- Cleaning of rating count values
- General data formatting

---

# Technologies Used

| Technology | Purpose |
|------------|---------|
| Microsoft Power BI Desktop | Dashboard development |
| Power Query | Data cleaning and transformation |
| DAX | Business calculations and KPIs |
| Kaggle | Data source |

---

# Repository Structure

```text
amazon-product-analytics-dashboard/
│
├── assets/
│   └── dashboard-demo.gif
│
├── data/
│   └── amazon.csv
│
├── images/
│   ├── overview.png
│   ├── category-analysis.png
│   ├── pricing-discounts.png
│   ├── product-explorer.png
│   └── customer-reviews.png
│
├── Amazon_Product_Analytics_Dashboard.pbix
└── README.md
```

---

# How to Open

1. Clone or download this repository.
2. Open **Amazon_Product_Analytics_Dashboard.pbix** using Microsoft Power BI Desktop.
3. Explore the report pages using the interactive filters and visualizations.

---

# Author

**Matheus Rocha**

Statistics Undergraduate at the Federal University of Minas Gerais (UFMG)

- GitHub: https://github.com/matheusoch
- LinkedIn: https://www.linkedin.com/in/matheuspcoelho/