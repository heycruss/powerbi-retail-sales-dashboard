# 📊 Retail Sales Dashboard | Power BI

---

# Overview

The objective of this project was to transform a flat transactional dataset into a well-structured Business Intelligence solution. This involved designing a Star Schema data model, identifying and resolving data quality issues (such as duplicated identifiers and inconsistent records), creating reusable DAX measures, and developing an interactive Power BI dashboard that enables users to explore the data dynamically rather than relying on static reports.

The dashboard was designed as an analytical tool, allowing users to dynamically change both the business metric and the analysis dimension, providing a flexible experience beyond a traditional static report.

---

# Dashboard Preview

![Dashboard](Retail-Sales-Dashboard.png)

---

# Dataset

### Source

- Superstore Sales Dataset (Kaggle)

### Dataset Information

- Rows:
- Columns:
- Period:
- Country:

Brief description of the dataset.

---

# Business Requirements

The dashboard was designed to answer questions such as:

- Which customer segment generates the highest sales?
- Which product category performs best?
- How have sales evolved over time?
- Which shipping mode is used the most?
- ...

---

# Data Model

![Data Model](Images/data_model.png)

Explain:

- Why you chose a Star Schema.
- Fact table.
- Dimension tables.
- Relationships.

---

# Data Preparation

## Cleaning Process

Explain briefly:

- Data types
- Removed duplicates?
- Renamed columns?
- Missing values?
- Date table
- etc.

---

## Product Key Issue

Explain the duplicated Product ID problem.

Example:

Original Product ID:

![Duplicate Product](Images/product_issue.png)

Explain your solution.

---

# Measures

![Measures](Images/measures.png)

Main KPIs:

- Total Sales
- Total Orders
- Distinct Customers
- Orders per Customer
- Repeat Customer Rate
- Average Shipping Days

Explain any interesting measure.

---

# Dynamic Features

Explain:

- Field Parameters
- Dynamic charts
- Dynamic KPIs
- Dynamic titles
- Tooltip (if added)

Include screenshots.

---

# Dashboard Pages

## Executive Overview

![Overview](Images/page_overview.png)

Explain the page.

---

## Filters

Explain available filters.

---

## Visualizations

Explain:

- KPI Cards
- Line Chart
- Donut Chart
- Top Products
- Matrix

---

# DAX Examples

Example 1

```DAX
-- Paste measure here
```

Explain what it does.

---

Example 2

```DAX
-- Paste measure here
```

Explain what it does.

---

# Skills Demonstrated

- Data Cleaning
- Data Modeling
- Star Schema Design
- Power Query
- DAX
- Interactive Reporting
- Business Intelligence

---

# What I Learned

Write here:

- Problems you found.
- Decisions you made.
- Things you would improve.
- Lessons learned.

---

# Repository Structure

```text
Retail Sales Dashboard

│
├── Dashboard.pbix
├── Dataset.csv
├── README.md
│
└── Images
    ├── dashboard.png
    ├── data_model.png
    ├── measures.png
    ├── page_overview.png
    └── ...
```

---

# Author

**Ramón García Rico**

Data Analyst

Tokyo, Japan

LinkedIn:
