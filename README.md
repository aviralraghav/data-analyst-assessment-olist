# Data Analyst Assessment — Olist E-Commerce Business Analysis

## Executive Summary

This project analyzes the **Brazilian E-Commerce Public Dataset by Olist** to identify
key revenue drivers, sales trends, seller contribution patterns, and the relationship
between delivery performance and customer experience.

The objective is to translate transactional e-commerce data into actionable insights
that can support management decisions around **revenue growth, seller strategy,
operational performance, and customer experience**.

---

## Business Context

Management wants to become more data-driven and understand:

- Which product categories contribute most to business performance
- Which sellers are major contributors to revenue
- How sales performance changes over time
- Whether delivery performance is associated with customer satisfaction
- Where management should focus operational and commercial efforts

This analysis was designed as a management-oriented business analysis rather than
a purely technical data exercise.

---

## Dataset

**Dataset:** Brazilian E-Commerce Public Dataset by Olist

**Source:** Kaggle  
**Dataset URL:**  
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

The dataset contains multiple related tables covering:

- Orders
- Order Items
- Customers
- Sellers
- Products
- Product Categories
- Payments
- Reviews
- Geolocation

The use of multiple interconnected datasets makes the analysis suitable for
data cleaning, joining, feature engineering, aggregation, and exploratory analysis.

---

## Business Problem

The primary business problem is to understand the key drivers of e-commerce
performance and identify operational opportunities that management can act upon.

The analysis focuses on four areas:

1. **Revenue and category performance**
2. **Seller contribution**
3. **Sales trends over time**
4. **Delivery performance and customer experience**

---

## Analytical Questions

The analysis answers the following questions:

1. Which product categories generate the highest sales and order volume?
2. Which sellers and product categories contribute most to sales performance?
3. How do sales and order volumes change over time?
4. What payment patterns exist across orders?
5. Are there differences in customer experience across delivery-performance groups?

---

## Hypotheses

**H1:** A relatively small number of product categories and sellers contribute a
disproportionately large share of total sales.

**H2:** Longer delivery times are associated with lower customer satisfaction.

The hypotheses were treated as analytical questions to be tested against the available data.
The analysis does not assume causality where the dataset only supports association.

---

# Data Preparation & Methodology

## Tools

The analysis was performed using:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Google Sheets
- Google Looker Studio
- Microsoft PowerPoint
- GitHub

## Data Processing Workflow

The raw Olist datasets were processed through the following workflow:

```text
Raw Data
   ↓
Data Quality Audit
   ↓
Missing Value Handling
   ↓
Duplicate Removal
   ↓
Data Type Correction
   ↓
Category Translation
   ↓
Dataset Joins
   ↓
Order-Level Aggregation
   ↓
Feature Engineering
   ↓
Exploratory Analysis
   ↓
Management Dashboard & Recommendations

## Google Sheet

The complete assessment workbook, including the Data, Q1–Q8, Q10,
and Processed Data worksheets, is available here:

[View Google Sheet](https://docs.google.com/spreadsheets/d/1T-ZfumP3lxSUba43zfR-yv7v_d3y_X8rfngJgE5ApBk/edit?usp=sharing)
