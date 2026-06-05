# E-Commerce Product Analytics Case Study

## Overview

This project analyzes 320K+ ecommerce user events to understand user behavior, funnel progression, conversion patterns, and product performance. The goal was to identify where users drop off in the purchase journey and generate actionable product insights using Python, SQL, and Power BI.

---

## Objectives

- Analyze user funnel progression from visit to purchase
- Measure conversion and drop-off rates
- Perform root cause analysis (RCA) across multiple user segments
- Identify high-friction stages in the funnel
- Build an interactive business dashboard for stakeholder reporting

---

## Dataset

Synthetic ecommerce product analytics dataset containing:

- 320K+ event-level user interactions
- 12K+ unique users
- Multiple traffic sources, devices, countries, and product categories
- Funnel events including:
  - visit
  - view
  - add_to_cart
  - checkout
  - purchase

---

## Tools & Technologies

- Python
- Pandas
- SQL (SQLite)
- Matplotlib
- Power BI
- Jupyter Notebook
- Git & GitHub

---

## Key Analyses Performed

### Data Cleaning & Validation

- Standardized categorical fields
- Parsed timestamps
- Created session-level funnel progression logic
- Validated pricing and timestamp integrity
- Engineered temporal features for behavioral analysis

### Funnel Analysis

- Calculated session-level funnel progression
- Measured conversion and drop-off rates
- Identified checkout-to-purchase as the highest abandonment stage

### Root Cause Analysis (RCA)

Segmented funnel behavior across:

- traffic source
- device type
- geography
- product category
- weekday and hourly trends

### SQL Analytics

Used SQL queries to:

- calculate purchase conversion metrics
- compare acquisition channel performance
- analyze category-wise purchases
- track DAU and engagement patterns

### Power BI Dashboard

Built an interactive dashboard featuring:

- KPI cards
- session funnel visualization
- traffic-source conversion analysis
- monthly trend analysis
- category revenue analysis
- device distribution metrics
- interactive filters

---

## Key Findings

- The highest drop-off occurred between checkout and purchase.
- Funnel degradation remained relatively consistent across traffic sources, devices, and geographies.
- Referral traffic showed slightly stronger purchase conversion compared to paid acquisition channels.
- Product browsing engagement remained healthy in upper-funnel stages.

---

## Recommendations

- Improve the overall checkout experience to reduce final-stage abandonment.
- Investigate potential friction during transaction completion.
- Optimize lower-funnel conversion flow and purchase experience.
- Continue monitoring conversion trends through interactive dashboards.

---

## Dashboard Preview

(Add Power BI dashboard screenshots here)

---

## Project Structure

```text
product-analytics-project/
│
├── data/
├── notebooks/
├── visuals/
├── queries/
├── README.md
└── .gitignore
```

---

## Author

Ananya Modem
