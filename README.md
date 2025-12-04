# 📊 IBM Employee Attrition Dashboard

### 📖 Overview
This dashboard was created to analyze employee attrition within a simulated IBM dataset. The report evaluates key metrics such as **Total Employee Count**, **Attrition Rate**, and **Job Satisfaction**, and segments these figures across departments, age groups, education fields, and gender.

The dashboard uses visual analytics to highlight factors potentially driving attrition, allowing HR to identify and address at-risk employee groups, improve retention strategies, and enhance overall job satisfaction.

---

### 🎯 Project Objective
- Build a single-page visual or dashboard in Tableau to analyze employee attrition.
- Identify the **departments** with the highest attrition rates.
- Determine which **demographics** (Age, Gender, Education Field) are most susceptible to attrition.
- Analyze the relationship between **Job Satisfaction** and Attrition across different job roles.

---

### 🗄 Dataset Summary
- Source: Kaggle - IBM HR Analytics Employee Attrition & Performance
- Records: 1,470
- Fields: - Key Elements: Categorical (e.g., Department, Education Field), Numerical (e.g., Age, Monthly Income), Binary (Attrition: Yes/No).

---

### 📁 Repo Files ###

- [WA_Fn-UseC_-HR-Employee-Attrition.csv](https://github.com/jtschroer/Tableau_IBM_Employee_Attrition/blob/main/WA_Fn-UseC_-HR-Employee-Attrition.csv)

---

### ⚙️ Data Preparation & Transformation (Tableau)
Data preparation focused on ensuring all metrics are correctly calculated and dimensions are usable for grouping.

* **Handling Categorical Fields:** * **Creating Attrition Flags:** The `Attrition` column (Yes/No) was used directly or converted into a binary (1/0) field to facilitate rate calculations.
* **Model Optimization:** ---

### 🧩 Calculated Fields (Tableau)  
Click to expand.

This section is in progress.  More coming later.

### 🔍 Key Insights
Based on the dashboard visualization:

#### **Overall Performance Indicators (KPIs)**
| Metric | Value |
| :--- | :--- |
| Employee Count | 1,470 |
| Attrition Count | 237 |
| Attrition Rate | **16.12%** |
| Active Employees | 1,233 |
| Avg. Age | 37 |
| Avg. Job Satisfaction | 2.73 |

#### **Departmental and Role-Based Attrition**
* **R&D and Sales Volume:** Research & Development (R&D) and Sales account for the vast majority of attrition volume, at 56.32% (133 employees) and 38.82% (92 employees) respectively. This is expected given the high number of employees in these departments.
* **Job Satisfaction (Low Scores):** The **Laboratory Technician** and **Sales Executive** roles show the highest number of employees rating their job satisfaction as 1 (Low) or 2. This is a critical area for HR intervention, indicating potential dissatisfaction in these key roles.

#### **Demographic Breakdown**
* **Gender Attrition Disparity:** The Male Attrition Rate ($18.14\%$) is significantly higher than the Female Attrition Rate ($15.61\%$).
    * **NOTE:** *Verify the denominator (Total Male/Female Employees) for your Attrition by Gender calculation, as the percentages shown in the chart need to be confirmed against the total employee counts.*
* **Age Concentration:** The largest volume of employees is concentrated in the **25-35** age brackets (325 and 297 employees), making these groups a priority for retention efforts. The 25-30 group represents the highest single volume (325).
* **Education Field:** **Life Sciences** and **Medical** are the fields with the highest volume of employees who have left the company.

---

### 📝 Lessons Learned
* **Primary Lesson (E.g., Using LOD Expressions):** * **Secondary Lesson (E.g., Visual Design):** ---

### 🖼 Dashboard Preview

**Dashboard Snapshot** <img width="1000" alt="Dashboard Preview" alt="Dashboard Screenshot" src="image_ac6e68.jpg" />
