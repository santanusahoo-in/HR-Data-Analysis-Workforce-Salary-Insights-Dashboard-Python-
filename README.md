# HR Data Analysis: Workforce & Salary Insights

## 📊 Project Summary
This project focuses on analyzing HR data to uncover actionable insights about the workforce — including employee distribution, departmental performance, salary trends, and demographic diversity.  
Using Python, Power BI, and visualization libraries like Matplotlib and Plotly, the analysis explores how salaries and employees vary across departments, genders, and locations, helping HR teams make data-driven decisions.

---

## 💡 Business Problem
Human Resource departments often manage scattered employee data across systems and spreadsheets. Without structured analysis, decision-making around hiring, retention, and salary benchmarking becomes slow and reactive.

**Problem Statement:**  
How can HR data be analyzed to identify patterns in salaries, gender representation, departmental performance, and workforce growth trends to guide better business decisions?

---

## 🎯 Objectives
- Clean and integrate HR employee data for consistent analysis.  
- Evaluate total and average salaries by **department**, **state**, and **gender**.  
- Identify high-cost departments and regions driving payroll spending.  
- Track hiring patterns and headcount growth over time.  
- Visualize pay distribution to detect potential gender or regional disparities.  
- Deliver clear and interactive visuals for executive decision-making.

---

## 🧩 Data Overview
The dataset contains employee details such as:
- **Employee ID, Name, Gender, Department**
- **Hire Date, Birth Date, Job Title**
- **Location (State/Province)**
- **Salary, Bonus, and Pay Grade**

---

## 🧠 Methodology
1. **Data Cleaning & Transformation**
   - Removed duplicates, handled missing values.
   - Standardized date formats and categorical columns.
   - Converted salary fields to numeric for computation.

2. **Exploratory Data Analysis (EDA)**
   - Distribution of employees by gender, department, and location.
   - Salary comparison across genders and departments.
   - Correlation between hire date, salary, and department size.

3. **Visualization & Reporting**
   - Used **Matplotlib**, **Seaborn**, and **Plotly** for visuals.
   - Built KPI visuals for Power BI dashboard integration.

---

**📁 File:** [`hr_data_analysis.ipynb`](hr_data_analysis.ipynb)  
**🧮 Tools & Libraries Used:** Python:
```Py
pandas
numpy
matplotlib
seaborn
plotly
datetime
os
```
**👨‍💻 Developer:** [Santanu Sahoo]

---

## 📈 Key Visuals & Insights

### 1️⃣ Total Salaries by US State
![Total Salaries by US State](Image/Screenshot%202025-10-08%20215844.png)

- California and Minnesota dominate total payroll costs.  
- Total salaries across 8 states exceed **$10.6M** across 284 employees.  
- Western and Midwestern regions lead in total workforce cost concentration.

---

### 2️⃣ Average Salary per Employee by State
![Average Salary per Employee by State](Image/avg_salary_by_state.png)

- **California** leads with an average salary of **$44,644**, followed by **Minnesota** and **Massachusetts**.  
- Indicates strong compensation competitiveness in coastal states.

---

### 6️3️⃣ Gender-Based Salary Distribution
![Total and Average Salary by Gender](Image/salary_by_gender_combined.png)

- **Total Salary Share:** Males earn **~70% ($7.47M)** of the total salary pool, while females account for **~30% ($3.21M)**.  
- **Average Salary:** Interestingly, female employees have a slightly **higher average salary ($39,700)** compared to males ($36,786)**.  
- This suggests that while female representation in the dataset is smaller, their pay per employee is competitive — indicating fewer but higher-paid roles.  
- However, the imbalance in total salary share highlights potential **gender representation gaps** in overall workforce distribution.

---
### 4️⃣ Average Annual Salary Trend Across Years
![Average Annual Salary Trend Across Years](Image/salary_trend_hireyear.png)

- Clear upward trajectory post-2010, peaking at **$100,050** by 2013.  
- Suggests recent hiring cycles focus on higher-pay roles, possibly management and tech.

---

### 5️⃣ Salary vs. Age Relationship
![Salary vs Age](Image/salary_vs_age.png)

- Positive but **weak correlation** between age and salary.  
- Younger employees are distributed across wide salary ranges, indicating merit-based or role-based compensation.

---

### 6️⃣ Workforce & Salary Distribution by State × Department
![State × Department Workforce & Salaries Heatmap](Image/state_department_salary_heatmap.png)

- Production and Information Services dominate headcount and salary share across all states.  
- **Tennessee** and **California** show the highest department concentration and salary totals.  
- Highlights potential over-staffing or cost concentration zones.

---

## 📝 Report Summary
The HR Data Analysis project successfully transformed raw employee data into meaningful workforce and compensation insights.  
By cleaning, aggregating, and visualizing employee information across states, departments, and demographics, the analysis revealed key trends in salary distribution, workforce structure, and hiring patterns.  

A series of visualizations — including salary maps, trend lines, and demographic comparisons — provided a data-driven understanding of how HR metrics vary across geography and time.  

This project bridges data and decision-making by offering a reproducible analysis pipeline that HR leaders can use to:
- Evaluate pay equity.
- Identify high-cost departments or regions.
- Understand workforce distribution and trends.
- Support compensation planning and budgeting.

---

## 🧩 Conclusion
The analysis uncovered several important findings:
- **Regional Pay Patterns:** California and Minnesota lead both in total and average salaries, confirming their dominance in overall payroll spending.
- **Department Dynamics:** Production and Information Services employ the most staff and account for the majority of salary expenditure.
- **Gender Representation:** Male employees form a larger portion of the workforce (≈70%), yet female employees exhibit higher average salaries — a sign of equitable pay practices among experienced women.
- **Career Growth Trends:** The steady rise in average salaries from 2010 to 2013 suggests positive hiring momentum and improved compensation structures.
- **Age vs Salary:** Minimal correlation between age and salary indicates that roles and skills, rather than age, drive compensation decisions.

---

## 💡 Overall Insights
1. **Balanced Workforce:** The company maintains an overall diverse and fairly distributed salary structure, with minor room for gender representation improvement.  
2. **High-Pay Regions:** Western and Midwestern states dominate salary contribution — likely due to high-skill or leadership roles clustered there.  
3. **Departmental Focus:** Production departments absorb most salary costs; further analysis could reveal optimization opportunities.  
4. **Upward Salary Growth:** Annual hiring data suggests a healthy salary trajectory reflecting employee experience and role maturity.  
5. **Data-Driven HR:** Implementing this analysis in Power BI or a live dashboard could provide real-time insights for recruitment, budgeting, and equity audits.

---

## 🧭 Final Note
This project exemplifies how **data analytics empowers HR strategy** — turning spreadsheets into actionable intelligence.  
With expansion into predictive analytics (e.g., attrition risk or promotion likelihood), this analysis could evolve into a comprehensive **People Analytics System** for smarter workforce decisions.

---

✨ **Next Goal:** Integrate the outputs into a live Power BI dashboard or deploy a lightweight web app version for HR teams to explore insights interactively.

