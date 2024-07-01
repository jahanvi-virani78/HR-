# HR_Analytics_Dashboard_Tableau

# Introduction
Introducing the HR Analytics Dashboard, built upon the [**HR dataset**](HR%20Data.xlsx). This dashboard provides a comprehensive analysis of employee attrition and related factors within the organization. Through a series of visualizations, it offers insights into employee demographics, attrition rates, departmental trends, job satisfaction, and more. Utilizing various chart types and filters, it uncover patterns to inform strategic decisions and improve employee retention strategies.

## Contents
- [Dashboard Snapshot and Link](#dashboard-snapshot-and-link)
- [Overview of the Dashboard](#overview-of-the-dashboard)
- [Tools Used](#tools-used)
- [Author](#author)

## Dashboard Snapshot and Link:
This is the snapshot of the Dashboard 👇

 ![HR Analytics Dashboard](https://github.com/SAI-MANOJ-P/HR_Analytics_Dashboard_Tableau/assets/147478138/f4aa6257-6c96-47fb-b4c6-7f816fba2251)

For a detailed exploration of these visuals, you can access the
 [Dashboard](https://public.tableau.com/app/profile/sai.manoj.p7063/viz/HRAnalyticsDashboard_17072269097090/Dashboard1) here.

## Overview of the Dashboard:

## Visualizations:

1. **Key Performance Indicators (KPIs):**
   - Employee Count: Total number of employees in the dataset.
   - Attrition Count: Number of employees who have left the organization,   
     calculated using a defined expression (`if [attrition] == 'yes' THEN 1 ELSE 0 END`).
   - Attrition Rate: Percentage of employees who have left the organization, calculated as the sum of attrition count divided by the sum of employee count.
   - Active Employees: Number of employees currently employed, derived from the difference between total employee count and attrition count.
   - Average Age: Mean age of the employees.

2. **Attrition by Gender:**
   - Lollipop chart illustrating attrition count categorized by gender.

3. **Department-wise Attrition:**
   - Pie chart displaying attrition count and percentage breakdown by department.

4. **Number of Employees by Age:**
   - Bar graph showcasing employee distribution across age ranges, with dynamically adjustable bins.

5. **Job Satisfaction Rating:**
   - Heatmap visualizing department-wise employee counts for specific job satisfaction ratings.

6. **Education Field-wise Attrition:**
   - Bar graph presenting attrition rates based on educational qualifications.

7. **Attrition Rate by Gender for Different Age Groups:**
   - Multiple donut charts depicting attrition rates for each gender across different age groups.

## Filters:
- Education Filter: Drop-down menu enabling filtering by educational qualification.
- Department Filter: Selection of a department in the pie chart will update all other visualizations in the dashboard accordingly.
- Gender Filter: Selecting a gender in the lollipop chart will synchronize all other visualizations in the dashboard accordingly.

This dashboard provides a holistic view of employee attrition dynamics, allowing stakeholders to delve into various aspects and identify areas for targeted intervention and improvement.


## Tools Used

- **Tableau Public:** Utilized for creating interactive dashboard visualizations and hosting the resulting dashboards online.

  
## Author
**Sai Manoj Pandiri**
- [GitHub](https://github.com/SAI-MANOJ-P)
- [Linkedin](https://www.linkedin.com/in/saimanojpandiri/)
