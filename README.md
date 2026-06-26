# HR Employee Attrition Analysis

## Project Overview

This project analyzes employee attrition using Excel, SQL, and Power BI to identify the main factors associated with employee turnover and provide business recommendations based on data.

---

## Business Problem

Employee turnover represents a significant cost for organizations due to recruitment, onboarding, and productivity losses. The objective of this analysis is to identify patterns behind employee attrition and determine which factors contribute most to employees leaving the company.

---

## Objectives

* Analyze employee attrition.
* Identify departments and job roles with the highest turnover.
* Evaluate the relationship between overtime and attrition.
* Compare employee satisfaction, age, and monthly income.
* Build an interactive dashboard for decision-making.

---

## Dataset

The dataset contains HR information for **1,470 employees**, including:

* Age
* Department
* Job Role
* Monthly Income
* Job Satisfaction
* Overtime
* Attrition
* Education
* Gender
* Marital Status

---

## Tools Used

* Microsoft Excel
* SQL
* Power BI
* DAX

---

## SQL Analysis

SQL was used to validate the dataset and calculate key business metrics, including:

* Total employees
* Employees who left
* Attrition rate
* Attrition by department
* Attrition by job role
* Overtime analysis

---

## Excel Analysis

Excel Pivot Tables were used to validate the SQL calculations before creating the Power BI dashboard.

---

## Power BI Dashboard

The dashboard includes:

* Total Employees KPI
* Employees Left KPI
* Active Employees KPI
* Attrition Rate KPI
* Attrition by Department
* Attrition by Job Role
* Overtime vs Attrition
* Average Job Satisfaction
* Average Monthly Income
* Average Employee Age
* Interactive slicers

---

## Key Insights

* Research & Development had the highest number of employees leaving.
* Laboratory Technician showed the highest attrition among job roles.
* Employees working overtime experienced significantly higher attrition.
* Employees who left the company had lower job satisfaction.
* Employees who left earned a lower average monthly income.
* Employees leaving the company were younger on average.

---

## Business Recommendations

* Reduce excessive overtime.
* Improve employee engagement and satisfaction.
* Review compensation strategies for high-risk job roles.
* Develop retention plans focused on departments with higher turnover.

---

## Repository Structure

```
hr-employee-attrition-analysis
│
├── HR_Analytics_Employee_Attrition.pbix
├── HR_Employee_Attrition.xlsx
├── employee_attrition.sql
├── README.md
│
└── Images
    └── HR_Attrition_Dashboard.png
```
