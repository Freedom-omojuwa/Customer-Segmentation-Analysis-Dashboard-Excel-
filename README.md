# Customer Segmentation Analysis Dashboard (Excel)
> *Interactive Excel dashboard designed to analyze customer demographics, income levels, loyalty segments, occupations, and customer growth patterns to support customer-focused business decisions.*

![Customer Segmentation Analysis Dashboard](visuals/Customer%20Segmentation.png)
---

## Table of Contents

1. [Project Overview](#1-project-overview)
2. [Objectives](#2-objectives)
3. [Project Scope & Tools](#3-project-scope--tools)
4. [Repository Structure](#4-repository-structure)
5. [Data Workflow](#5-data-workflow)
6. [Data Model & Schema](#6-data-model--schema)
7. [Analysis & Metrics](#7-analysis--metrics)
8. [Key Insights](#8-key-insights)
9. [Recommendations](#9-recommendations)
10. [Assumptions & Limitations](#10-assumptions--limitations)
11. [Future Enhancements](#11-future-enhancements)
12. [Deliverables](#12-deliverables)
13. [Author](#13-author)

---

## 1. Project Overview

**Context:** 
This project focuses on analyzing customer data to better understand segmentation patterns, demographic distribution, income levels, loyalty, and growth trends.

**Problem Statement:** 
Businesses often struggle to understand the diverse needs of different customer groups, making it challenging to personalize marketing strategies and enhance customer retention.

**Approach:**  
Using Excel, Power Query, Pivot Tables, and Pivot Charts, raw customer data was cleaned, transformed, and analyzed to build an interactive dashboard.

**Outcome:**
A dynamic customer segmentation dashboard that provides insights into demographics, income distribution, loyalty behavior, occupation patterns, and customer growth trends.

---

## 2. Objectives

### Primary Objective

- Build an interactive Excel dashboard to analyze customer demographics, income levels, loyalty segments, and growth trends.

### Secondary Objectives

- Identify customer distribution across different generations.
- Analyze customer income brackets and wealth profiles.
- Evaluate customer loyalty using tenure-based segmentation.
- Examine occupational distribution within the customer base.
- Track customer acquisition and growth trends over time.
- Compare customer demographics across regions and customer segments.
- Transform raw customer data into actionable business insights through interactive visualizations.

> 💡 *Every analysis and dashboard component in this project was designed to support these objectives.*

---

## 3. Project Scope & Tools

### Scope

-->
| Category | Tools |
|----------|------|
| Data Processing | Excel, Power Query |
| Analysis | Pivot Tables, Pivot Charts |
| Visualization | Excel Dashboard |
| Interaction | Slicers |
| Documentation | GitHub README |

---

## 4. Repository Structure

```
furniture-sales-performance-dashboard/
│
├── data/
│   ├── raw/          # Original dataset before cleaning
│   └── processed/    # Cleaned and transformed data used for analysis and dashboard 
│
├── visuals/          # Dashboard screenshots and exported visuals 
│
└── README.md         # You are here (Project documentation)
```

---

## 5. Data Workflow

```
Raw customer data
      ↓
Data Import into Excel
      ↓
Data Cleaning & Transformation (Power Query)
      ↓
Pivot Table & Pivot Chart Analysis
      ↓
Interactive Dashboard Development
      ↓
Business Insights & Reporting
```

---

## 6. Data Model & Schema

## Dataset: Furniture Sales Data

This dataset contains transactional-level furniture sales records used for analysis and dashboard development.

Each row represents a single sales transaction, including customer, product, shipping, and financial details.

---

## Data Structure

| Field Name        | Data Type | Description                          | Example Value |
|------------------|----------|--------------------------------------|---------------|
| CustomerID       | Text     | Unique customer ID                   | CUST-1001     |
| Name             | Text     | Customer full name                   | Emily Davis   |
| Gender           | Text     | Customer gender (Male/Female)       | Male          |
| Age              | Number   | Age of the customer                  | 29            |
| Generation       | Text     | Customer generation group            | Millennial    |
| Region           | Text     | Customer location region             | East          |
| Occupation       | Text     | Customer job role                    | Engineer      |
| Income           | Number   | Annual income of customer            | 250000       |
| Income Bracket   | Text     | Income category                      | Medium        |
| Customer Segment | Text     | Type of customer segment             | Retail        |
| Join_Date        | Date     | Customer registration date           | 2021-06-15    |
| Tenure           | Number   | Years as a customer                  | 3             |
| Tenure Group     | Text     | Customer loyalty category            | Loyal         |
| Year             | Number   | Year the customer joined             | 2021          |   

> **Row count (approx.):** 2001 rows
> **Date range:** 01/02/2015 – 12/30/2025

---

## 7. Analysis & Metrics

### Analytical Approach

This project uses Exploratory Data Analysis (EDA) in Microsoft Excel to examine customer demographics, income distribution, loyalty patterns, and customer growth trends. The objective is to segment customers into meaningful groups and uncover insights that can support customer engagement, retention, and business decision-making.

The analysis was conducted using Power Query for data cleaning and transformation, Pivot Tables for data aggregation, Pivot Charts for visualization, and Slicers for interactive filtering.


## Key Metrics Defined

| Metric | Definition | Why It Matters |
|--------|------------|----------------|
| Total Customers | Total number of customers in the dataset | Measures the overall size of the customer base|
| Average Age | Average age of all customers | Helps understand the demographic profile of customers |
| Average Income | Average income across all customers| Indicates the overall purchasing power of the customer base |
| Average Tenure | Average number of years customers have remained with the business | Measures customer retention and loyalty |
| Generation Distribution | Distribution of customers across generations (Boomers, Gen X, Millennials, Gen Z) | Helps identify dominant age segments |
| Wealth Profile | Distribution of customers across income brackets (Low, Medium, High) | Provides insight into customer economic segments |
| Loyalty Segment | Classification of customers based on tenure groups (New, Emerging, Loyal, Legacy) | Evaluates customer loyalty and retention patterns |
| Occupational Profile | Distribution of customers by occupation) | Helps understand the professional characteristics of customers |
| Customer Growth Trend | Number of customers acquired over time | Tracks growth patterns and customer acquisition trends |

---
## Methods Used

- Data cleaning and transformation using Power Query
- Date conversion and standardization
- Creation of calculated fields and segmentation categories
- Customer generation classification
- Income bracket segmentation
- Tenure group segmentation
- KPI calculations for Customer Count, Average Age, Average Income, and Average Tenure
- Pivot Tables for customer aggregation and analysis
- Pivot Charts for trend and demographic visualization
- Interactive filtering using Region and Customer Segment slicers
- Dashboard design and visualization in Microsoft Excel

---


## 8. Key Insights

### Insight 1: Millennials Represent the Largest Customer Segment

Generation analysis shows that Millennials make up the largest share of the customer base, with 273 females and 269 males, totaling 542 customers (27.1% of the 2,000 customers). This indicates that the business has a strong customer presence within this age group.

### Insight 2: Low-Income Customers Dominate the Customer Base

The wealth profile analysis indicates that a large proportion of customers are within the low-income segment, suggesting that this income group forms a key part of the bank’s customer base.

### Insight 3: Loyal Customers Form a Significant Portion of the Customer Base

Tenure analysis indicates that a significant proportion of customers fall within the Loyal segment, representing 39.35% of the 2,000 customers. This highlights strong customer retention and long-term engagement.

### Insight 4: Professional and Business-Oriented Occupations Are Well Represented

Occupation analysis shows a fairly even distribution across key professional groups, with retired customers (307), teachers (303), doctors (290), students (289), engineers (288), bankers (262), and traders (261) each contributing a significant share of the customer base. This presents opportunities for targeted marketing and tailored customer engagement strategies across segments.

### Insight 5: Customer Acquisition Shows Fluctuating Trends Over Time

The customer growth trend shows fluctuations over the years, with no consistent upward progression. Customer numbers peaked in 2016 (200 customers), 2019 (212 customers), and 2021 (211 customers), but generally remained within a relatively stable range between 155 and 212 customers, indicating variable acquisition patterns rather than steady growth.

### Insight 6: Customer Demographics Vary Across Regions

Regional analysis reveals differences in customer demographics, income levels, and loyalty patterns, suggesting that customer behavior varies by location.

---

## 9. Recommendations

| Priority | Recommendation | Based On | Suggested Owner |
|----------|---------------|----------|-----------------|
| High | Increase inventory availability and marketing activities in top-performing states such as California to maximize revenue opportunities | Insight 1 | Sales & Inventory Team |
| High | Focus promotional campaigns on high-performing categories like Chairs to drive additional sales growth | Insight 2 | Marketing Team |
| Medium | Maintain and optimize Standard Class shipping operations since it is the most preferred shipping method among customers | Insight 3 | Operations Team |
| Medium | Prepare targeted promotional campaigns before peak sales periods such as November and December | Insight 5 | Marketing & Sales Team |
| Low | Develop strategies to improve engagement and sales contribution from Corporate and Home Office customer segments | Insight 6 | Business Development Team |
---

## 10. Assumptions & Limitations

### Assumptions

- All transaction records in the dataset were assumed to be complete and accurate.
- Sales, profit, and discount values were assumed to be correctly recorded.
- Shipping duration values were assumed to reflect actual delivery timelines.
- Customer and regional information were assumed to be consistent across all records.

---

### Limitations

- The dataset is a sample/tutorial dataset and may not fully represent real-world business operations.
- The analysis focuses only on historical sales data and does not include predictive forecasting.
- Customer demographic and behavioral data were not included in the dataset.
- External business factors such as marketing spend, economic conditions, and competitor activity were not considered.
- The project was developed entirely in Excel without advanced statistical or machine learning analysis.

---

## 11. Future Enhancements

- [ ] Build a Power BI version of the dashboard for enhanced interactivity
- [ ] Add automated dashboard refresh using Power Query connections
- [ ] Include predictive sales forecasting analysis
- [ ] Expand the dashboard with additional KPIs and customer behavior analysis

---

## 12. Deliverables

| Deliverable | Description | Location |
|-------------|-------------|----------|
| Raw Dataset | Original furniture sales dataset used for analysis | `/data/raw/` |
| Processed Dataset | Cleaned and transformed dataset used for dashboard reporting including Interactive Excel dashboard with KPIs, slicers, charts, and maps | `/data/processed/` |
| Dashboard Visuals | Dashboard screenshots and exported visuals | `/visuals/` |
| README Documentation | Full project documentation and workflow explanation | `/README.md` |

---

## 13. Author

**Freedom Omojuwa**
Aspiring Data Analyst | Quantity Surveying Graduate

- 🔗 linkedin.com/in/freedom-omojuwa-1a64b8249
- 💼 freedom-omojuwa.github.io
- 📧 Freedomomojuwa@gmail.com

---

*Last updated: May 2026*

