# HR-Analytics-Dashboard
### Tools : SQL | Power BI


#### A single-page, interactive Power BI dashboard analyzing employee attrition drivers using a synthetic 150-employee HR dataset.

### **Overview**

This dashboard identifies why employees leave — not just how many — by grouping department, job satisfaction, and overtime status into one connected attrition-risk narrative, backed by headcount, compensation, and hiring-trend context. Slicers let users filter the whole dashboard down to a specific segment.

### **Key Insights**
**Department:** Finance and Marketing show the highest attrition (~33-35%); IT the lowest (~15%)
**Overtime:** Attrition nearly doubles for employees working overtime (31.9% vs. 18.5%)
**Job Satisfaction:** Strong inverse relationship — attrition drops from ~39-40% at low satisfaction to ~5% at the highest
**Hiring Seasonality:** April and November are peak hiring months; June is the slowest

### **Dashboard Structure**
**KPI row:** Total Employees, Attrition Rate%, Avg Monthly Income, Avg Tenure, Avg Performance Rating (with custom icons)
**Attrition-risk row:** Attrition Rate% by Department, OverTime, and Job Satisfaction — grouped together intentionally
**Context row:** Avg Monthly Income by Department, Headcount by Department, Job Role distribution (Top 8), Gender split
**Hiring Trend by Month:** seasonality view of new hires
**Slicers:** Department, Gender, OverTime, and Hire Date — for cross-filtering the entire page
