# Workforce Intelligence | Employee Analytics Dashboard

## Project Overview

Workforce Intelligence is an Employee Data Analysis project developed using Microsoft Excel. The project focuses on analysing employee information to understand workforce demographics, job roles, salary distribution, educational qualifications, age groups, and employee joining trends.

An interactive Excel dashboard presents key workforce metrics through KPI cards, charts, and visualizations, making employee data easier to understand and interpret.

## Project Objectives

- Analyse employee distribution across different job roles.
- Understand workforce demographics through gender and age analysis.
- Examine salary distribution and salary variations.
- Analyse employee educational qualifications.
- Identify employee joining trends over time.
- Present meaningful workforce insights through an interactive dashboard.

## Dashboard Preview

![Workforce Intelligence Dashboard](dashboard/office_analysis_dashboard.png)

## Key Performance Indicators (KPIs)

The dashboard includes the following key metrics:

| KPI | Value |
|---|---:|
| Total Employees (Cleaned Dataset) | 161 |
| Average Salary | 54.23K |
| Minimum Salary | 28.9K |
| Maximum Salary | 85K |
| Female Employees | 88 |
| Male Employees | 73 |

## Dashboard Features

### 1. Employee Analysis by Job Title
Visualizes employee distribution across 10 different job roles to understand workforce allocation.

### 2. Age Group Analysis
Analyses employee distribution across different age groups using age bins.

### 3. Gender Distribution
Shows the proportion of male and female employees within the organization.

### 4. Employee Joining Trends
Displays the cumulative employee joining pattern over time using joining dates.

### 5. Education and Salary Analysis
Explores salary distribution across different educational qualifications using a coded education category.

### 6. Gender by Job Title
Compares the number of male and female employees across different job roles.

### 7. Interactive Job Title Filter
Allows users to filter dashboard information based on selected job titles.

## Dataset Description

The cleaned dataset contains **161 employee records and 10 columns**.

| Column Name | Description |
|---|---|
| Name | Employee name |
| Emp ID | Unique employee identification number |
| Gender | Employee gender |
| Education Qualification | Employee educational qualification |
| Date of Join | Employee joining date |
| Job Title | Employee's designated job role |
| Salary | Employee salary |
| Age | Employee age |
| Leave Balance | Available employee leave balance |
| First Characters | Helper column containing the first character of employee names |

## Key Insights

- The dataset contains 161 unique employee records.
- Female employees account for approximately 54.66% of the workforce.
- Male employees account for approximately 45.34% of the workforce.
- Packaging Associate has the highest employee count with 22 employees.
- Bachelor's Degree is the most common educational qualification, with 49 employees.
- The average salary is approximately 54.23K.
- Employee salaries range from 28.9K to 85K.

## Data Cleaning

Data preparation was performed to ensure the dataset was suitable for analysis.

- Removed 838 placeholder rows containing the text `null` in the employee ID field.
- Retained 161 valid employee records.
- Verified employee ID uniqueness.
- Prepared cleaned Excel and CSV datasets for analysis.

## Tools and Technologies Used

- **Microsoft Excel** – Data preparation, analysis, and dashboard development.
- **Excel Charts** – Data visualization and graphical representation.
- **Excel Filters** – Interactive dashboard filtering.
- **CSV** – Structured data storage and data exchange.

## Project Structure

```text
Workforce-Intelligence/
│
├── data/
│   ├── office_employee_data_cleaned.xlsx
│   └── office_employee_data_cleaned.csv
│
├── dashboard/
│   └── office_analysis_dashboard.png
│
├── docs/
│   └── DATA_DESCRIPTION.txt
│
├── README.md
└── .gitignore
```

## How to Use This Project

1. Clone or download this repository.
2. Open the cleaned Excel dataset from the `data` folder.
3. Review the employee records and available attributes.
4. Open the dashboard image from the `dashboard` folder to explore the analysis.
5. Use the CSV dataset for further analysis in other data analytics tools.

## Future Scope

This project can be extended by integrating SQL, Python, and Power BI to perform advanced employee data analysis, build interactive visualizations, and generate deeper workforce insights.

## Conclusion

The Workforce Intelligence project demonstrates how employee data can be transformed into meaningful insights using Microsoft Excel. It provides a structured approach to understanding workforce demographics, salary patterns, job roles, educational qualifications, and joining trends through data analysis and visualization.

---

**Project Category:** Data Analytics | HR Analytics | Excel Dashboard
