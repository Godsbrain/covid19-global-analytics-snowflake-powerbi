# COVID-19 Global Analytics Dashboard

## Overview

This project presents an end-to-end Business Intelligence solution for analyzing global COVID-19 trends using Snowflake, SQL, and Power BI.

The objective was to transform raw COVID-19 data into actionable insights through data modeling, analytical SQL queries, Snowflake views, DAX measures, and interactive Power BI dashboards.

The solution follows a modern analytics workflow:

Raw Data → Snowflake → Analytics Views → Power BI → Executive Dashboard

---

## Project Architecture

schema.png

The project follows a layered architecture:

### RAW Layer
Stores the original COVID-19 datasets:
- COVIDDEATHS
- COVIDVACCINATIONS

### Analytics Layer
Business-ready views created in Snowflake:

- VW_GLOBAL_DAILY
- VW_COUNTRY_STATS
- VW_VACCINATION_PROGRESS
- VW_CONTINENT_STATS

### Visualization Layer
Power BI dashboards built on top of analytical views using:
- DAX Measures
- Date Dimension
- Data Modeling
- Interactive Filters

---

## Business Questions

The project answers key analytical questions:

1. How did global COVID-19 cases evolve over time?
2. How did mortality rates change throughout the pandemic?
3. Which countries and regions were most affected?
4. What percentage of the population became infected?
5. How did vaccination programs progress across countries?
6. What was the overall global death rate?

---

## Technologies Used

### Data Warehouse
- Snowflake

### Querying & Analysis
- SQL
- Window Functions
- Aggregate Functions
- CTEs
- Temporary Tables
- Views

### Business Intelligence
- Power BI
- DAX
- Data Modeling
- Interactive Dashboards

### Version Control
- Git
- GitHub

---

## Snowflake Analytics

Key SQL techniques demonstrated:

### Exploratory Data Analysis
- Global case analysis
- Global mortality analysis
- Country-level infection rates
- Continent-level comparisons

### Advanced SQL
- Common Table Expressions (CTEs)
- Window Functions
- Running Totals
- Aggregate Analysis
- Data Validation
- Analytical Views

### Data Modeling
- Fact and Dimension structures
- Calendar Table
- Star-schema concepts

---

## Power BI Dashboard

### Executive KPIs

The dashboard highlights:

- Total Cases
- Total Deaths
- Death Rate
- Countries Analyzed
- Infection Percentage
- Vaccination Percentage

### Trend Analysis

Interactive visualizations include:

- Global Daily COVID Cases
- COVID Death Percentage Trend
- COVID Mortality Trend
- Global Death Analysis

### Filters

Users can filter results by:

- Year
- Month
- Continent

---

## Dashboard Preview

Dashboard.png

---

## Key Insights

### Global Impact

- 151M+ reported COVID-19 cases
- 3M+ reported deaths
- 2.11% global death rate
- 210 countries analyzed

### Trends

- Significant infection waves occurred throughout 2020 and 2021.
- Mortality rates peaked during the early stages of the pandemic and gradually declined.
- Vaccination programs contributed to lower mortality trends over time.

---

## Repository Structure

```text
covid19-global-analytics-snowflake-powerbi
│
├── dashboard.png
├── schema.png
├── covid19_dashboard.pbix
├── covid_analysis.sql
├── covid_views.sql
└── README.md
```

---

## Skills Demonstrated

- Data Warehousing
- Snowflake
- SQL Analytics
- Business Intelligence
- Data Visualization
- Dashboard Development
- DAX
- Data Modeling
- KPI Design
- Exploratory Data Analysis
- Stakeholder Reporting

---

## Future Enhancements

Potential project improvements:

- Country-level drill-through dashboards
- Predictive trend forecasting
- Vaccination effectiveness analysis
- Geographic mapping visualizations
- Automated data pipeline integration

---

## Author

**Solomon Mensah**

GitHub: https://github.com/Godsbrain

LinkedIn: Add your LinkedIn profile here

Location: Winnipeg, MB, Canada
