# HR Dashboard Suite – Tableau Project

## Project Overview  
This repository contains the Tableau workbooks for the HR Dashboard Suite. The dashboards provide a comprehensive view of HR metrics including headcount, demographics, performance, salary trends, and region-based insights.

## Contents  
- `/data/` — source Excel file(s) (e.g., `HR_Summary.xlsx`)  
- `/workbooks/`  
  - `Dashboard_Overview.twbx` — High-level executive-focused dashboard (see below)  
  - `Dashboard_Details.twbx` — Detailed drill-down dashboard for HR business partners  


## Dashboard 1: Overview  
- Intended for senior leadership: shows key KPIs (active employees, turnover rate, average tenure), trends across time, and high-level geographic summary.  
- Design-focus: one page, large KPI tiles, trend lines, map with regional summary, global filters (e.g., by status, region).  

## Dashboard 2: Details  
- Intended for HR analysts and business partners: offers interactive drill-down by department, location, gender, hire date; includes scatter plot of salary vs performance, tenure distribution, and table of individual employee metrics.  
- Design-focus: multi-sheet navigation, detailed filters, tooltip enhancements, calculated fields (e.g., “Time in Role”, “% Salary Increase”), export capability.