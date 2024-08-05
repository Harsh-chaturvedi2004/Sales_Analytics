![image](https://github.com/user-attachments/assets/efdff1cd-e6a8-4419-b422-2fe8d1245542)

# Problem Statement
## Objective:
- To create an executive sales report that meets the specific needs of sales managers and sales representatives by developing a data model and Power BI dashboards for internet sales.

## Problem Breakdown:

- Overview of Internet Sales: Dynamic dashboard to monitor overall internet sales performance.

1. Value: Enables better tracking of customer and product performance.
2. Acceptance Criteria: A Power BI dashboard that updates data daily.
3. Sales Over Time vs. Budget: Comparison of sales over time against the budget.

## Exploratory Data Analysis
### Data Cleansing and Transformation
#### DIM_Calendar Table
- Selected necessary columns and formatted them for easier navigation and visualization.

#### DIM_Customers Table
- Cleansed and joined with geography data for better customer insights.

#### DIM_Products Table
- Cleansed and enriched with subcategory and category data.

#### FACT_InternetSales Table
- Selected and filtered necessary columns to keep recent data.

### Data Model Construction
- Integrated FACT_InternetSales with DIM tables.
- Connected sales budget data (provided in Excel) to the data model for comparison with actual sales.

## Solution Implementation
- Developed a Power BI dashboard with:
-- An overview page for sales managers, showing total sales, top customers, and products.
-- Detailed pages for sales representatives, with filters for customer and product-specific data.
-- Visualizations to compare sales over time against budget targets.

![image](https://github.com/user-attachments/assets/57f9438f-444f-43c6-98fd-b2bb1cb814f2)

