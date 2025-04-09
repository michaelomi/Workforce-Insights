# 📋 Workforce Insights 
This is a comprehensive project that analyzes employee demographics, performance metrics, attrition trends, and diversity data. It provides actionable insights to support HR decision-making and workforce strategy optimization.  

## 📊 Highlights of the Analysis  

### General Statistics  
- **Total Employees:** 1,470  
- **Attrition Rate:** 16.1%  
- **Average Age:** 37 years  
- **Average Tenure in Company:** 7 years  

## 🔍 Key Insights by Dashboard Section  

### 1. **Employee Overview**  
![Employee Overview Icon](https://imgur.com/tYcNUfM.png)

- **Demographics:**  
  - **Males** make up **60%** of the workforce, while **Females** account for **40%**.  
  - The **26-35 age group** is the largest, with **606 employees (41.22%)**.  

- **Departments and Roles:**  
  - The **Research & Development (R&D)** department leads with **65.37%** of employees.  
  - **Sales Executives** (Sales department) are the most common job role at **22.18%**.  

- **Tenure Distribution:**  
  - **52.79%** of employees are in the tenure range of **0-5 years**.  
  - Only **1.09%** of employees have a tenure of **31-40 years**.  

### 2. **Performance Metrics**  
![Performance Metrics Icon](https://imgur.com/f72LfTE.png)

- **Top Performers:**  
  - Employee **RM485**, a Sales Executive, scored the highest performance score at **97 points**.  

- **Training Insights:**  
  - Training correlates with performance. Only employees with **2+ training sessions** scored over **90 points**.  
  - **Human Resources** has the lowest average training times (**2.6 sessions**) and the lowest performance scores.  

- **Department Comparisons:**  
  - **Sales** and **Research & Development** departments have the highest-performing employees, with scores of **97 and 95**, respectively.

### 3. **Employee Exits (Attrition)**  
![Employee Exits Icon](https://imgur.com/2SMXTKc.png)

- **General Trends:**  
  - **16.1%** of employees left the company.  
  - The **26-35 age group** had the most attrition in absolute numbers (**116 employees**).  
  - The **18-25 age group** had the highest attrition rate (**35.8%**).  

- **Roles and Departments:**  
  - The **Sales Department** had the highest attrition rate (**21%**).  
  - **Sales Representatives** faced the highest attrition rate (**40%**).  

- **Other Factors:**  
  - Males constituted **63.29%** of attrition cases.  
  - Employees in the **Life Sciences field** and those earning **"Upto 5k"** had the highest attrition rates.  

### 4. **Diversity Insights**  
![Diversity Insights Icon](https://imgur.com/yHpYjDp.png)

- **Gender and Age:**  
  - Females earn slightly more, with an average monthly income of **$6.7k**, compared to Males at **$6.4k**.  

- **Tenure and Income:**  
  - Employees in the **31-40 years tenure** have the highest average income.  

- **Departments:**  
  - The **Sales department** has more Females, while **Research & Development** has more Males.  

## 📈 Visuals  
Interact with the Power BI dashboard [here](https://github.com/michaelomi/Workforce-Insights/blob/main/Workforce%20Insights%20Dashboard.pbix).

### Dashboard Pages  
1. **Employee Overview**: Gender ratio, marital status, age group distribution, tenure distribution, job role distribution.  
2. **Performance Metrics**: Top 10 performers by role, training performance correlation, department and job role by average monthly income.  
3. **Employee Exits**: Heatmap of exit demographics, attrition by various categories.  
4. **Diversity Insights**: Gender by income and departments, tenures by income, employees education field.  

### Key Features  
- Dynamic filtering by marital status, and age group.  
- Interactive charts for exploring relationships between metrics.  

## 💻 Tools Used  
- **Power BI** for data visualization.  
- **DAX** for advanced metrics calculations.  
- **Excel** for initial data cleaning and preparation.  

## 📎 Resources  
- [Power BI File](https://github.com/michaelomi/Workforce-Insights/blob/main/Workforce%20Insights%20Dashboard.pbix)  
- [Dataset](https://github.com/michaelomi/Workforce-Insights/blob/main/HR_Analytics.xlsx)

## 🔧 Data Cleaning Notes  
- Reduced **Employee IDs** from **1480 rows to 1470 rows** by removing duplicates.  
- Corrected inconsistencies in the **Travel Column** for accurate categorization.  
- Created calculated columns in Power BI for:  
  - **Performance Metric**: A weighted formula incorporating Job Involvement, Job Satisfaction, Overtime, Performance Rating, and Training Times.  
  - **Tenure Range Grouping**: Categorized employees into tenure ranges (e.g., 0-5 years, 6-10 years) for better visualization.  
