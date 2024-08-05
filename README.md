# Problem Statement
## Objective:
- To create an executive sales report that meets the specific needs of sales managers and sales representatives by developing a data model and Power BI dashboards for internet sales.

## Problem Breakdown:

- Overview of Internet Sales: Dynamic dashboard to monitor overall internet sales performance.

1. Value: Enables better tracking of customer and product performance.
2. Acceptance Criteria: A Power BI dashboard that updates data daily.
3. Sales Over Time vs. Budget: Comparison of sales over time against the budget.

## SQL
Data Requirements and Preparation
Data Cleansing and Transformation
-- DIM_Calendar Table
-- Selected necessary columns and formatted them for easier navigation and visualization.
-- SQL Example:
sql SELECT [DateKey], [FullDateAlternateKey] AS Date, [EnglishDayNameOfWeek] AS Day, [EnglishMonthName] AS Month, LEFT([EnglishMonthName], 3) AS MonthShort, [MonthNumberOfYear] AS MonthNo, [CalendarQuarter] AS Quarter, [CalendarYear] AS Year FROM [AdventureWorksDW2019].[dbo].[DimDate] WHERE CalendarYear >= 2019
