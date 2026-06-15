# Power BI Interview Questions and Answers

## Overview

This repository contains the Top 30 Power BI Interview Questions and Answers frequently asked in Data Analyst, Business Intelligence Analyst, Power BI Developer, and Reporting Analyst interviews.

The questions range from beginner to advanced levels and cover important topics such as Power BI Architecture, Data Modeling, DAX, Power Query, Visualization, Security, and Performance Optimization.

This repository is designed to help students, freshers, and experienced professionals prepare for technical interviews and improve their Power BI knowledge.

---

## Topics Covered

### Power BI Fundamentals

* Power BI Components
* Power BI Architecture
* Power BI Desktop
* Power BI Service
* Power BI Gateway
* Power BI Report Server

### Data Modeling

* Relationships
* Star Schema
* Snowflake Schema
* Fact Tables
* Dimension Tables

### DAX (Data Analysis Expressions)

* Measures
* Calculated Columns
* Calculated Tables
* Aggregation Functions
* Time Intelligence Functions

### Power Query

* Data Transformation
* Data Cleaning
* ETL Process
* Query Folding

### Visualization

* Charts
* KPIs
* Dashboards
* Drill Down
* Drill Through

### Security

* Row Level Security (RLS)
* Workspace Management

### Performance Optimization

* Model Optimization
* Query Optimization
* Best Practices

---

# Top 30 Power BI Interview Questions and Answers

## 1. What is Power BI?

Power BI is a Business Intelligence and Data Visualization tool developed by Microsoft that helps users connect, transform, analyze, and visualize data to create interactive reports and dashboards.

---

## 2. What are the main components of Power BI?

* Power BI Desktop
* Power BI Service
* Power BI Mobile
* Power BI Gateway
* Power BI Report Server

---

## 3. What is Power BI Desktop?

Power BI Desktop is a Windows application used for data transformation, modeling, report creation, and visualization.

---

## 4. What is a Dashboard in Power BI?

A dashboard is a single-page collection of visualizations that provides a consolidated view of business metrics.

---

## 5. What is a Report in Power BI?

A report is a multi-page collection of visualizations created from one dataset.

---

## 6. What is Power Query?

Power Query is a data transformation and ETL tool used to clean and prepare data before loading it into Power BI.

---

## 7. What is DAX?

DAX (Data Analysis Expressions) is a formula language used for calculations and data analysis in Power BI.

Example:

```DAX
Total Sales = SUM(Sales[Amount])
```

---

## 8. Difference Between Measure and Calculated Column?

### Measure

* Calculated at runtime
* Consumes less memory

### Calculated Column

* Stored in memory
* Calculated during data refresh

---

## 9. What is a Fact Table?

A fact table contains measurable business data such as sales, revenue, and profit.

Example:

* Sales Amount
* Quantity Sold

---

## 10. What is a Dimension Table?

A dimension table contains descriptive information.

Examples:

* Customer
* Product
* Date
* Region

---

## 11. What is Star Schema?

A star schema consists of one fact table connected directly to multiple dimension tables.

---

## 12. What is Snowflake Schema?

A snowflake schema normalizes dimension tables into multiple related tables.

---

## 13. What are Relationships in Power BI?

Relationships connect tables using common columns.

Types:

* One-to-One
* One-to-Many
* Many-to-One
* Many-to-Many

---

## 14. What is Row Level Security (RLS)?

RLS restricts data access for different users based on roles.

---

## 15. What is Drill Down?

Drill Down allows users to navigate from summarized data to detailed data.

---

## 16. What is Drill Through?

Drill Through allows users to navigate to another report page containing detailed information.

---

## 17. What is Bookmark in Power BI?

Bookmarks save the current state of a report page.

---

## 18. What is a KPI?

A KPI (Key Performance Indicator) measures business performance against a target.

---

## 19. What is a Slicer?

A slicer is a visual filter used to filter report data interactively.

---

## 20. What is Query Folding?

Query Folding pushes transformations back to the data source to improve performance.

---

## 21. Difference Between Import Mode and DirectQuery?

### Import Mode

* Faster performance
* Data stored inside Power BI

### DirectQuery

* Real-time data
* Queries source directly

---

## 22. What is Power BI Gateway?

Gateway enables secure communication between on-premises data sources and Power BI Service.

---

## 23. What are Calculated Tables?

Tables created using DAX expressions.

---

## 24. What is a Composite Model?

A model that combines Import and DirectQuery modes.

---

## 25. What is Incremental Refresh?

Incremental Refresh loads only newly added or modified data.

---

## 26. What is USERELATIONSHIP Function?

Used to activate inactive relationships in DAX calculations.

---

## 27. What is CALCULATE Function?

CALCULATE modifies filter context in DAX.

Example:

```DAX
Sales_USA =
CALCULATE(
    SUM(Sales[Amount]),
    Customer[Country] = "USA"
)
```

---

## 28. How Do You Optimize Power BI Performance?

* Use Star Schema
* Remove unused columns
* Reduce cardinality
* Use measures instead of calculated columns
* Enable query folding

---

## 29. What is the Difference Between Dashboard and Report?

### Dashboard

* Single Page
* Created in Power BI Service

### Report

* Multiple Pages
* Created in Power BI Desktop

---

## 30. Why Should We Hire You as a Power BI Developer?

I possess strong skills in Power BI, SQL, DAX, Data Modeling, Data Visualization, and Business Intelligence. I can transform raw business data into actionable insights and build interactive dashboards that support data-driven decision-making.

---

## Skills Covered

* Power BI
* DAX
* Power Query
* Data Modeling
* SQL
* Business Intelligence
* Dashboard Development
* Data Visualization
* ETL
* Reporting

---

## Author

Mannuru Mahesh

Aspiring Data Analyst | Power BI Developer | Business Intelligence Enthusiast
