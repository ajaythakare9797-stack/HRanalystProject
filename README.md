# 💼 HR Analytics Dashboard – Power BI Project

Welcome to my **HR Analytics Dashboard** project, built using Power BI. This interactive dashboard provides valuable insights into employee attrition trends, satisfaction levels, and compensation patterns, helping HR teams make data-driven decisions.

---

## 📌 Objective

The goal of this project is to develop a user-friendly and insightful Power BI dashboard to help HR teams:

- Analyze employee attrition trends
- Understand job satisfaction by department and role
- Visualize salary distributions and employee demographics
- Enable data-driven strategies to reduce turnover

---

## 📊 Dataset Overview

- **Dataset Name:** `HR_Analytics.csv`  
- **Records:** ~1,400 employee entries  
- **Columns Include:**
  - Demographics: Age, Gender, Marital Status
  - Work Experience: Years at Company, Job Role, Department
  - Satisfaction Scores: Job Satisfaction, Environment Satisfaction, Relationship Satisfaction
  - Compensation: Monthly Income, Salary Slab
  - Additional: Business Travel, Education Field, Attrition status

---

## 🛠️ Tools & Skills Used

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query (M Language)**
- **Data Modeling & Relationships**
- **Interactive Visualization Design**

---

## ✅ Key Tasks Completed

### 🔹 1. Data Preparation

- Imported dataset into Power BI
- Renamed and cleaned column names (e.g., `Monthly_Income` → `Monthly Income`)
- Converted data types appropriately
- Removed duplicates
- Handled missing values (e.g., mean imputation for `YearsWithCurrentManager`)

### 🔹 2. KPI Creation (DAX)

| **KPI Name**            | **Formula**                                              |
|-------------------------|-----------------------------------------------------------|
| Total Employees         | `COUNT(EmployeeNumber)`                                   |
| Attrition Rate (%)      | `(Employees Left / Total Employees) * 100`               |
| Average Monthly Income  | `AVERAGE('Employee Data'[Monthly Income])`                |

### 🔹 3. Dashboard Visualizations

| **Visual Type**             | **Description**                                |
|----------------------------|------------------------------------------------|
| 🧁 Donut Chart              | Attrition Rate by Education Field              |
| 📊 Clustered Column Chart   | Attrition by Age Group                         |
| 📉 Horizontal Bar Chart     | Attrition by Salary Slab                       |
| 📋 Matrix                   | Job Role vs Job Satisfaction                   |
| 📈 Line Chart               | Years at Company vs Attrition Count            |
| 🏢 Column Chart             | Department vs Number of Employees Left         |
| 🎛️ Slicers                  | Gender & Department filters                    |
| 📝 Title Header             | Custom text box with project title             |

---

