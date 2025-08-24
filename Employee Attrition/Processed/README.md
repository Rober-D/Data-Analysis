# 💼 HR Employee Attrition Analysis Project

## 📌 Overview
This project investigates employee attrition to understand key factors contributing to turnover and retention. Python is used for data cleaning and exploration, and Power BI for interactive dashboards that make findings easier to communicate and interpret.

---

## 🔍 Objectives
- Identify the main drivers behind employee attrition.
- Explore correlations between salary, job roles, education, and distance from home.
- Provide actionable insights and recommendations to support HR decision-making.

---

## 🛠 Tools & Technologies
- **Python** (Pandas, Seaborn, Matplotlib) – Data analysis & visualization
- **Power BI** – Interactive dashboards
- **Google Colab / Jupyter Notebook** – Development environment
- **GitHub** – Version control and documentation

---

## 📊 Dashboard Highlights
- Total number of employees and attrition status
- Attrition by Job Role and Distance from Home
- Monthly Income by Education Level
- Years at Company vs Income (with Attrition status highlighted)
- Slicers for job role and other dimensions

![Dashboard](https://github.com/user-attachments/assets/81a3be09-aa88-47d8-aa45-1d3ffa3e5813)

---

## 🧠 Key Insights
- **Sales Representatives** had the highest attrition rate.
- Some roles (like **Healthcare Representatives**) showed that distance doesn’t always affect attrition, while others (like **Research Director**, **Sales Rep**) are more vulnerable.
- Employees who left the company generally had lower **average monthly income**.
- Several employees have spent **more than 5 years in the company with salaries similar to new joiners**, possibly indicating dissatisfaction.

---

## ✅ Recommendations
- Focus on **retention strategies** for roles with higher attrition (e.g., Sales-related roles).
- Consider **compensation reviews**, especially for long-tenure employees earning similar to new hires.
- Monitor employee segments where **distance from home** is a notable factor.
- Recommend tracking average salary of current employees to detect cases where **pay is close to those who left**, allowing timely interventions.

---

## 🔮 Future Work
- Analyze attrition patterns by **age and gender**.
- Explore **average monthly income** trends for each **department**.
- Study the impact of **marital status** on attrition among males and females to detect which demographic is more influenced and effective in retention.

---

## 📂 Project Structure
📁 data/
├── main_dataset.csv
└── updated_dataset.csv

📁 visuals/
└── dashboard.png

📁 notebooks/
└── eda_analysis.ipynb

📁 powerbi/
└── employee_attrition_dashboard.pbix
