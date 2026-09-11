# Data Analyst Assessment — Olist E-Commerce Business Analysis

## Executive Summary

This project presents an end-to-end analysis of the **Brazilian E-Commerce Public Dataset by Olist** as part of a Data Analyst Assessment.

The objective was to use publicly available e-commerce data to identify meaningful
business opportunities, performance gaps, trends, and operational improvement areas
that could support management decision-making.

The analysis focuses on four key business areas:

- Revenue and product-category performance
- Seller contribution and concentration
- Sales trends over time
- Delivery performance and customer experience

The final solution includes data processing in Python, a management-oriented
dashboard in Looker Studio, a structured assessment workbook, and a senior-management
presentation.

---

## Business Context

Management wants to become more data-driven and understand:

- Which product categories contribute most to revenue
- Which sellers are major contributors to business performance
- How sales performance changes over time
- How delivery performance relates to customer experience
- Which areas should be prioritized for business improvement

The analysis was designed to translate transactional data into practical,
management-oriented insights and recommendations.

---

## Dataset

### Brazilian E-Commerce Public Dataset by Olist

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

The interconnected structure provides sufficient complexity for data cleaning,
joining, feature engineering, aggregation, exploratory analysis, and business
reporting.

---

## Business Problem

The primary business problem is to understand the key drivers of e-commerce
performance and identify operational and commercial opportunities that management
can act upon.

The analysis investigates:

1. Revenue and category performance
2. Seller contribution
3. Sales trends
4. Delivery performance
5. Customer experience

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

These hypotheses were tested using descriptive and exploratory analysis. Where the
data only supports association, causal conclusions were intentionally avoided.

---

# Data Preparation & Methodology

## Tools Used

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

```text
Raw Olist Data
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
Dashboard & Management Recommendations

# Links & Deliverables

### Google Sheet
https://docs.google.com/spreadsheets/d/1T-ZfumP3lxSUba43zfR-yv7v_d3y_X8rfngJgE5ApBk/edit?usp=sharing

### Looker Studio Dashboard
https://datastudio.google.com/reporting/7fbcfa1d-714d-4f73-897a-80b84452e315
