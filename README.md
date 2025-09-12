# 🏢 Employee-Attrition-Project
## 📌 Project Overview
Employee attrition (when employees leave an organization) has a major business impact.  
This project explores an **HR dataset (15,000 employees, 10 features)** to:  
1. Analyze attrition drivers (salary, department, promotions, satisfaction, working hours).  
2. Build **machine learning models** to predict employee exit.  
3. Create an **interactive Power BI dashboard** for HR insights & decision-making.  

## 📊 Dataset
The dataset contains ~15,000 employee records with 10 features:
satisfaction_level
last_evaluation
number_project
average_monthly_hours
time_spend_company
Work_accident
left (Target: 1 = Left, 0 = Stayed)
promotion_last_5years
Department
salary

## 🔑 Key Steps & Features  

### 1️⃣ Data Exploration (Python, Pandas, Seaborn)  
- Checked missing values, distribution of target (`left`).  
- Explored satisfaction level vs working hours (correlation & scatter plot).  
- Grouped attrition by **department, salary, promotion history**.  

### 2️⃣ Data Preparation  
- Encoded categorical features (`salary`, `Department`).  
- Scaled numeric columns (`satisfaction_level`, `last_evaluation`, etc.) for ML models.  

### 3️⃣ Machine Learning Models (Scikit-learn)  
- Logistic Regression  
- Random Forest  
- Gradient Boosting  

✅ Evaluated with Accuracy, Precision, Recall, F1-score, ROC-AUC.  
✅ Compared feature importance (top drivers of attrition: satisfaction, time in company, salary).  

### 4️⃣ Dashboard (Power BI)  
- Built from exported Excel file (`Employee_Attrition_Insights(1).xlsx`).  
- Visuals included:  
  - **KPI Cards**: Total Employees, Employees Left, Retention Rate.  
  - **Donut Chart**: Stayed vs Left.  
  - **Bar Charts**: Attrition by Department, Salary Level, Promotion History.  
  - **Line Chart**: Satisfaction vs Average Monthly Hours (with trendline)

## 📂 Repository Structure  
📦 Employee-Attrition-Project
┣ 📜 Emp_attriton_project1.ipynb ← Jupyter Notebook (EDA + ML models)
┣ 📜 Employee_Attrition_Insights(1).xlsx ← Cleaned dataset for dashboards
┣ 📜 Emp_attr_dashboard1.pbix ← Power BI dashboard file
┣ 📜 README.md ← Project documentation

## 📊 Power BI Dashboard Preview  

> 🔎 Key Insight: Employees with **low satisfaction & longer working hours** tend to leave.  
> Attrition is higher among **low-salary employees** and those without **recent promotions**.  

## 🚀 Skills Demonstrated  
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Machine Learning (Logistic Regression, Random Forest, Gradient Boosting)  
- Data Visualization with Power BI  
- Business Insights & Storytelling  

## 📌 How to Use This Project  
1. Clone/download the repository.  
2. Open `Emp_attriton_project1.ipynb` to explore the Python analysis.  
3. Open `Employee_Attrition_Insights(1).xlsx` in Power BI to rebuild the dashboard or use the included `Emp_attr_dashboard1.pbix`.  

## ✅ Conclusion  
This project demonstrates how **data science + business intelligence** can be combined:  
- Machine learning highlights **key predictors** of attrition.  
- Power BI turns findings into **interactive dashboards** for HR teams to act on.  
