# Sales Performance, Target Achievement & Operational Risk Dashboard

## Project Overview

This Power BI dashboard was developed to help business leaders monitor sales performance, evaluate target achievement, identify operational risks, and support data-driven decision-making.

The report transforms fragmented sales data into an executive-friendly analytics solution that enables users to understand business performance across regions, categories, countries, shipping methods, and regional managers.

The dashboard focuses on answering key business questions:

* Is the business growing year-over-year?
* Is growth translating into profitability?
* Are sales targets being achieved?
* Which regions and categories drive performance?
* Are product returns increasing?
* Are delivery delays creating business risks?
* Which managers and categories require attention?

---

## Business Problem

The organization operates across multiple regions and product categories. Management lacked a centralized reporting solution to monitor:

* Sales growth
* Profitability
* Order trends
* Category target achievement
* Product returns
* Delivery performance

Leadership required a simple and intuitive dashboard that could be used during monthly business review meetings without requiring technical expertise.

---

## Dashboard Structure

## Data Model 

The dashboard follows a star-schema-inspired data model to support efficient filtering, target tracking, and performance analysis.

![Data Model](https://github.com/akhileshraut/)

### Page 1: Business Performance Overview

Provides a high-level view of business health and performance.

#### KPIs

* Total Sales
* Total Profit
* Total Orders
* Target Achievement %
* Return Rate %
* Delivery Delay %

#### Visuals

* Performance by Region
* Performance by Category
* Performance by Country
* Performance by Ship Mode
* Monthly Sales vs Target Trend

#### Features

* Dynamic KPI Selection (Sales, Profit, Orders)
* Year-over-Year Growth Indicators
* Top Performer Highlighting
* Dynamic Titles & Labels
* Interactive Filtering

---

### Page 2: Targets & Business Risks

Focuses on operational performance and areas requiring management attention.

#### KPIs

* Target Achievement %
* Target Gap
* Returned Orders
* Return Rate %
* Delayed Orders
* Delay Rate %

#### Visuals

* Category Target Achievement Analysis
* Regional Manager vs Category Performance Matrix
* Returns Analysis
* Delivery Delay Analysis
* Risk Assessment View

#### Features

* Target Tracking
* Category Performance Monitoring
* Return Trend Analysis
* Delivery Performance Monitoring
* Risk Identification

---

## Data Model

### Fact Tables

* Orders
* Returns
* Target

### Dimension Tables

* Date Table
* People

### Key Relationships

* Orders ↔ Date
* Orders ↔ Returns
* Orders ↔ Target
* Orders ↔ People

---

## Key Metrics

### Sales Metrics

* Total Sales
* Sales YoY Growth %
* Sales vs Target
* Target Achievement %

### Profitability Metrics

* Total Profit
* Profit Margin %
* Profit YoY Growth %

### Order Metrics

* Total Orders
* Orders YoY Growth %

### Returns Metrics

* Returned Orders
* Return Rate %
* Return Growth %

### Delivery Metrics

* Delayed Orders
* Delay Rate %
* Average Delivery Days

---

## Technical Highlights

### Power Query

* Data Cleaning
* Data Transformation
* File Consolidation
* Delivery Days Calculation

### DAX

* Year-over-Year Analysis
* Dynamic KPI Selection
* Dynamic Titles
* Conditional Formatting
* Ranking Calculations
* Performance Indicators

### Visualization Techniques

* Dynamic Field Parameters
* Conditional Color Formatting
* Custom Data Labels
* Error Bars for Target Comparison
* Interactive Drilldowns

---

## Key Insights Delivered

* Identification of top-performing regions
* Category-level target achievement analysis
* Profitability assessment by region and category
* Return trend monitoring
* Delivery delay analysis
* Regional manager performance evaluation
* Business risk identification

---

## Tools Used

* Microsoft Power BI
* Power Query
* DAX
* Data Modeling

---

## Author

**Akhilesh Raut**

Microsoft Certified Power BI Data Analyst

Passionate about transforming data into actionable business insights through interactive and visually compelling dashboards.
