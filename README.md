# Enterprise-Loan-Risk-Default-Analytics-Dashboard

## Overview

The Enterprise Loan Risk & Default Analytics Dashboard is a comprehensive Power BI project designed to analyze loan performance, borrower behavior, and default risk patterns. The dashboard provides interactive visualizations and KPI-driven insights that help identify high-risk loan segments, monitor lending trends, and support data-driven financial decisions.

This project uses Power BI Desktop, Power BI Service, SQL Server, Dataflows, and advanced DAX measures to build an end-to-end enterprise analytics solution.

---

## Objectives

* Analyze loan distribution across different customer categories
* Identify high default-risk borrower segments
* Track Year-over-Year (YOY) and Year-to-Date (YTD) loan trends
* Monitor borrower demographics and financial behavior
* Build scalable reporting pipelines using Dataflows and Incremental Refresh

---

## Tech Stack

* **Power BI Desktop**
* **Power BI Service**
* **Microsoft SQL Server**
* **Power Query**
* **DAX**
* **Standard Mode Gateway**
* **Dataflows**
* **SQL**

---

## Key Features

* Interactive KPI dashboards
* Loan amount analysis by purpose and demographics
* Default rate tracking across employment types and years
* Credit score category analysis
* YOY and YTD loan trend analysis
* Decomposition Tree for root cause analysis
* Incremental Refresh setup for scalable performance
* Scheduled refresh using Power BI Service Gateway

---

## Dataset Description

The dataset contains enterprise loan-related information including:

* Loan Amount
* Loan Purpose
* Credit Score Category
* Employment Type
* Marital Status
* Education Type
* Mortgage & Dependents Information
* Age Groups
* Default Status
* Year-wise Loan Data

---

## Project Workflow

### 1. Data Integration

* Downloaded and configured Standard Mode Gateway
* Installed Microsoft SQL Server
* Imported loan data into SQL Server
* Connected SQL Server with Power BI Service

### 2. Dataflow Creation

* Created Dataflows in Power BI Service
* Imported data into Power BI Desktop using Dataflows
* Configured scheduled refresh and incremental refresh

### 3. Data Cleaning & Transformation

Performed using Power Query Editor:

* Data type correction
* Data profiling
* Data validation
* Column transformation and renaming

### 4. Dashboard Development

Created multiple interactive visualizations including:

* Donut Charts
* Clustered Column Charts
* Line Charts
* Decomposition Tree
* KPI Cards

---

## DAX Measures Used

### Loan Amount by Purpose

Functions Used:

* `SUMX`
* `FILTER`
* `NOT`
* `ISBLANK`

### Average Income by Employment Type

Functions Used:

* `CALCULATE`
* `AVERAGE`
* `ALLEXCEPT`

### Default Rate by Employment Type

Functions Used:

* `ALL`
* `ALLEXCEPT`
* `COUNTROWS`
* `DIVIDE`
* `FILTER`

### Average Loan by Age Groups

Functions Used:

* `AVERAGE`
* `AVERAGEX`
* `VALUES`

### Median Loan Calculations

Functions Used:

* `MEDIANX`

### YOY Loan Amount Analysis

Custom YOY DAX Measures

### YOY Default Loan Change

Custom DAX Growth Measures

### Decomposition Tree Analysis

Functions Used:

* `SWITCH`

---

## Dashboard Insights

* Identified employment categories with higher default rates
* Analyzed average loan trends across age groups
* Tracked yearly loan growth and default fluctuations
* Compared loan distributions based on credit score bins
* Evaluated borrower behavior using marital status and education type

---

## Data Validation

Validation checks were performed for:

* Average Loan by Age Groups
* Default Rate by Year
* Donut Chart Metrics
* Clustered Column Chart Results
* Median Calculations

---

## Power BI Service Configuration

* Configured Gateway Connection
* Scheduled Automatic Refresh
* Enabled Incremental Refresh
* Published Reports to Power BI Service
* Shared Reports for enterprise access

---

## Project Structure

```text
Enterprise-Loan-Risk-Dashboard/
│
├── Dataset/
├── SQL Scripts/
├── PowerBI_Report/
├── Dashboard_Screenshots/
├── Dataflow_Config/
└── README.md
```

---

## Dashboard Pages

* Loan Overview Dashboard
* Default Risk Analysis
* Credit Score Analytics
* YOY & YTD Trend Analysis
* Borrower Demographics Dashboard

---

## Future Improvements

* Integrate real-time streaming datasets
* Add machine learning-based default prediction
* Deploy dashboard using embedded analytics
* Add row-level security for enterprise access
* Integrate Azure and Snowflake pipelines

---

## Learning Outcomes

Through this project, the following skills were developed:

* Advanced DAX Calculations
* Enterprise Dashboard Development
* Data Modeling
* ETL & Dataflows
* SQL Server Integration
* Power BI Service Administration
* Incremental Refresh Optimization
* Business Intelligence Reporting

---
