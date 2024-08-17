# Human Resources Dashboard

## User Story

As an HR manager, I need a comprehensive dashboard to analyze human resources data. The dashboard should provide both summary views for high-level insights and detailed employee records for in-depth analysis.

## Dashboard Overview

The HR Dashboard is divided into the following sections:

### Summary View

The Summary View is designed to provide a high-level overview of HR metrics, including:

- **Overview**
  - Display the total number of hired employees, active employees, and terminated employees.
  - Visualize the total number of hired and terminated employees over the years.
  - Present a breakdown of total employees by department and job titles.
  - Compare total employees between headquarters (HQ) and branches (New York is the HQ).
  - Show the distribution of employees by city and state.

- **Demographics**
  - Present the gender ratio in the company.
  - Visualize the distribution of employees across age groups and education levels.
  - Show the total number of employees within each age group.
  - Show the total number of employees within each education level.
  - Present the correlation between employees’ educational backgrounds and their performance ratings.

- **Income Analysis**
  - Compare salaries across different education levels for both genders to identify any discrepancies or patterns.
  - Present how age correlates with salary for employees in each department.

### Employee Records View

- Provide a comprehensive list of all employees with necessary information such as name, department, position, gender, age, education, and salary.
- Users should be able to filter the list based on any of the available columns.

## Data

The dashboard utilizes data from the `HumanResources.csv` file. This CSV file contains detailed employee records and is essential for generating the various metrics and visualizations in the dashboard.
