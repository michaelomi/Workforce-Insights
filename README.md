# Workforce Insights 📋
![Power BI](https://img.shields.io/badge/Power%20BI-Visualization-yellow.svg) ![DAX](https://img.shields.io/badge/DAX-Metrics-blue.svg) ![Excel](https://img.shields.io/badge/Excel-Data%20Cleaning-green.svg)

This project provides a comprehensive analysis of employee demographics, performance metrics, attrition trends, and diversity data. It offers actionable insights to support HR decision-making and workforce strategy optimization using interactive visualizations in Power BI.


## Highlights of the Analysis 📊

### General Statistics
- **Total Employees:** 1,470  
- **Attrition Rate:** 16.1%  
- **Average Age:** 37 years  
- **Average Tenure in Company:** 7 years  

## Key Insights by Dashboard Section 🔍

### 1. Employee Overview 👥
![Employee Overview Icon](https://imgur.com/tYcNUfM.png)

- **Demographics:**  
  - **Males** make up **60%** of the workforce, while **Females** account for **40%**.  
  - The **26-35 age group** is the largest, with **606 employees (41.22%)**.  

- **Departments:**  
  - The **Research & Development (R&D)** department leads with **65.37%** of employees (961 employees).  

- **Tenure Distribution:**  
  - **52.79%** of employees (776 employees) are in the tenure range of **0-5 years**.  
  - **4.49%** of employees (66 employees) have a tenure of **20+ years**.  

### 2. Performance Metrics 📈
![Performance Metrics Icon](https://imgur.com/f72LfTE.png)

- **Top Performers:**  
  - Employee **RM485**, a Sales Executive, scored the highest performance score at **97 points**.  

- **Training Insights:**  
  - Training correlates with performance. Only employees with **2+ training sessions** scored over **90 points**.  

- **Department Comparisons:**  
  - **Sales** and **Research & Development** departments have the highest-performing employees, with scores of **97 and 95**, respectively.  

### 3. Employee Exits (Attrition) 🚪
![Employee Exits Icon](https://imgur.com/2SMXTKc.png)

- **General Trends:**  
  - **16.1%** of employees left the company.  
  - The **26-35 age group** had the most attrition in absolute numbers (**116 employees**).  
  - The **18-25 age group** had the highest attrition rate (**36.36%**).  

- **Roles and Departments:**  
  - The **Sales Department** had the highest attrition rate (**21%**).  

- **Other Factors:**  
  - Males constituted **63%** of attrition cases.  
  - Employees in the **Life Sciences field** had the highest attrition (89 employees).  

### 4. Diversity Insights 🌍
![Diversity Insights Icon](https://imgur.com/yHpYjDp.png)

- **Tenure and Income:**  
  - Employees in the **20+ years tenure** range have the highest average income (**$14K**).  

- **Departments:**  
  - The **Sales department** has more Females (32.14%) than Males (29.14%), while **Research & Development** has more Males (65.99%) than Females (64.46%).  

## Visuals 📈

Interact with the Power BI dashboard [here](https://app.powerbi.com/view?r=eyJrIjoiMTY5MzMyNzQtN2IyOC00OThiLWJmNTItZDY1MjVmYmI0MjIxIiwidCI6IjA1ODU3NTFmLTRiNDctNDUzOS04YmMzLWJmODNlMmVlMWQzZiJ9)

### Dashboard Pages
1. **Employee Overview**: Gender ratio, marital status, age group distribution, tenure distribution, job role distribution.  
2. **Performance Metrics**: Top 10 performers by role, training performance correlation, department and job role by average monthly income.  
3. **Employee Exits**: Heatmap of exit demographics, attrition by various categories.  
4. **Diversity Insights**: Gender by income and departments, tenures by income, employees education field.  

### Key Features
- Dynamic filtering by marital status and age group.  
- Interactive charts for exploring relationships between metrics.  

## Tools Used 💻
- **Power BI**: For data visualization and dashboard creation.  
- **DAX**: For advanced metrics calculations.  
- **Excel**: For initial data cleaning and preparation.  

## Data Cleaning Notes 🔧
- Reduced **Employee IDs** from **1480 rows to 1470 rows** by removing duplicates.  
- Corrected inconsistencies in the **Travel Column** for accurate categorization.  
- Created calculated columns in Power BI for:  
  - **Performance Metric**: A weighted formula incorporating Job Involvement, Job Satisfaction, Overtime, Performance Rating, and Training Times.  
  - **Tenure Range Grouping**: Categorized employees into tenure ranges (e.g., 0-5 years, 6-10 years) for better visualization.  
