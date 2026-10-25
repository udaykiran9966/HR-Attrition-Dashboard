# HR Employee Attrition Dashboard

Power BI dashboard analysing employee attrition (employees leaving the company).

## Dataset
IBM HR Analytics Employee Attrition & Performance dataset from Kaggle (1,470 employees, 35 columns). This is a public practice dataset, not real company data.
The original dataset had no missing values. I added some blank values myself to practise data cleaning in Power Query.

## Tools
Power BI, Power Query, DAX

## What I did
- Cleaned the data in Power Query (missing values, unused columns).
- Added Attrition Flag, Age Group, Income Group columns.
- Created DAX measures: Total Employees, Attrition Count, Attrition Rate %.
- Built a dashboard with 3 KPI cards, 4 charts and Department and Gender slicers.

## Key findings
- Sales (20.77%) and Human Resources (19.05%) have higher attrition than Research & Development (13.81%).
- The 18-25 age group has the highest attrition (36.36%).
- Low-income employees leave more (28.09%) than high-income employees (10.61%).
- Employees who work overtime leave more (30.53%) than those who do not (10.44%).

## Dashboard
![Dashboard](Screenshot%202026-10-25%20145621.png)
