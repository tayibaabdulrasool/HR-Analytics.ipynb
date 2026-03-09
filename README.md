# HR-Analytics.ipynb
**Project Overview**

This project analyzes factors influencing employee attrition using a dataset from Kaggle
.
The goal is to identify which factors cause employees to leave the company, visualize trends, and provide actionable insights for HR decision-making.

**Key Objectives:**

Identify factors affecting employee attrition.

Determine departments with the highest turnover.

Explore the impact of job satisfaction and salary on attrition.

Examine the gender pay gap.

Visualize employee retention trends based on experience and tenure.

**Dataset**

File: WA_Fn-UseC_-HR-Employee-Attrition.csv

Rows: 1470 employees

Columns: 35+ features including Age, Gender, Department, JobSatisfaction, MonthlyIncome, OverTime, Attrition, and more.


**Libraries Used**
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

**Analysis & Visualizations**
**1. Correlation Analysis**

Created a heatmap to identify relationships with attrition.

**Insights from correlation:**

Employees working overtime are more likely to leave.

Low job satisfaction increases attrition.

Lower monthly income is associated with leaving.

Younger employees and those with fewer years at the company have higher attrition.

Longer commuting distance slightly increases attrition.

**2. Attrition by Department**

Countplots and groupby analysis revealed Sales and Research & Development departments have higher turnover.

**3. Job Satisfaction Impact**

Correlation and visualizations show employees with lower job satisfaction are more likely to resign.

**4. Gender Pay Gap**

**Grouped MonthlyIncome by Gender:**

Checked for differences in average salary between male and female employees.

**5. Experience and Tenure**

Histogram of YearsAtCompany shows most employees leaving are in early years (0–2 years).

Employees with longer tenure (10+ years) show better retention.

**6. Visualizations**

Heatmap: Numeric feature correlations

Countplot: Attrition distribution

Bar chart: Attrition by department

Boxplot: Salary vs Attrition

Histogram: Years at Company

**Key Findings**

Factors influencing employee attrition:

Overtime work, low job satisfaction, lower salary, younger age, fewer years at company, and longer commuting distance.

Departments with highest turnover:

Sales and Research & Development have higher attrition rates.

Job satisfaction impact:

Employees with low satisfaction leave more frequently.

Gender pay gap:

Minor differences may exist; visualization and analysis help HR assess fairness.

Tenure influence:

Employees in early years are at higher risk of leaving.

**Conclusion**

The analysis identifies key risk factors affecting employee retention.

HR teams can focus on:

Reducing excessive overtime

Increasing job satisfaction programs

Reviewing compensation packages

Providing support to new employees in first 2 years

These insights can help reduce attrition and improve retention strategies.


**Future Work**

Build a predictive model to forecast employee attrition.

Include additional features like performance ratings, promotion history, and employee engagement scores.

Conduct a department-level attrition analysis to target retention strategies.
