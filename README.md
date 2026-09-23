# 📊 HR-Analytics-Dashboard – created using-Power-BI

## 📌 Project Overview

**HR-Analytics-Dashboard-created-using-Power-BI** is an interactive HR Analytics project developed using **Microsoft Power BI**.

The dashboard helps analyze employee data, workforce trends, employee attrition, demographics, salary, and experience to support data-driven HR decision-making.

---

## 🎯 Business Objectives

- Analyze the overall employee workforce
- Understand employee attrition
- Identify departments with higher attrition
- Analyze employee demographics
- Compare employee performance and job roles
- Understand salary and experience patterns
- Support data-driven HR decision-making

---

## 📈 Key KPIs

| KPI | Description |
|---|---|
| 👥 Total Employees | Total number of employees |
| 📉 Attrition | Number of employees who left the organization |
| 📊 Attrition Rate | Percentage of employees who left |
| 💰 Average Salary | Average employee salary |
| 🎂 Average Age | Average employee age |
| ⏳ Average Experience | Average years of employee experience |

---

## 📊 Dashboard Features

### 1. Workforce Overview

- Total employees
- Employee demographics
- Department-wise workforce
- Job role distribution

### 2. Attrition Analysis

- Overall attrition rate
- Department-wise attrition
- Job role-wise attrition
- Gender-wise attrition
- Age-group attrition

### 3. Employee Analysis

- Salary analysis
- Experience analysis
- Job level analysis
- Education analysis

### 4. Interactive Analysis

The dashboard includes interactive filters and slicers for:

- Department
- Gender
- Job Role
- Age
- Education
- Job Level

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Data Cleaning**
- **Data Modeling**
- **Data Analysis**
- **Data Visualization**

---

## 🔄 Data Analysis Process

```text
Raw HR Data
     ↓
Data Cleaning
     ↓
Data Transformation
     ↓
Data Modeling
     ↓
DAX Calculations
     ↓
Dashboard Development
     ↓
HR Insights
     ↓
Business Recommendations

Total Employees =
COUNTROWS(HR_Data)

Total Attrition =
CALCULATE(
    COUNTROWS(HR_Data),
    HR_Data[Attrition] = "Yes"
)
Attrition Rate =
DIVIDE(
    [Total Attrition],
    [Total Employees],
    0
)
Average Salary =
AVERAGE(HR_Data[MonthlyIncome])

Average Age =
AVERAGE(HR_Data[Age])
Average Experience =
AVERAGE(HR_Data[TotalWorkingYears])

