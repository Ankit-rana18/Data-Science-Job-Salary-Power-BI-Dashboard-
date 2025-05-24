# 📊 Data Science Job Salary Dashboard – Power BI

This project showcases an interactive Power BI dashboard that visualizes global salary trends in the field of **Data Science** across different company sizes, experience levels, job titles, and locations.


---

## 📌 Project Overview

This dashboard provides a comprehensive overview of salary patterns in data science roles, with multiple filters and visual elements allowing users to explore:
- Salary by company size (Small, Medium, Large)
- Year-wise trends in average salary and job counts
- Country-wise formatted salary table
- Experience-level salary comparisons
- Top-paying job titles in the industry

---

## 🧠 Key Insights

- **2021** saw the highest average salary, peaking at **$711K**
- **Entry-level roles** reported surprisingly high average compensation in some regions
- **AI Scientist** and **Machine Learning Scientist** topped the salary charts
- Company size had a clear influence on both average salary and job count distribution

---

## 💡 Features & Visuals

- 📅 **Line Charts**: Avg salary & job type trends over years
- 🌐 **Table**: Country-wise formatted salaries with sorting
- 🍩 **Donut Chart**: Avg salary by experience level
- 🧮 **Cards**: Highlight avg salaries by experience tier
- 🎯 **Bar Chart**: Max salary by job title
- 🧩 **Slicer Buttons**: Stylish filters for company size categories

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **DAX** for custom measures:
  - Formatted Salary (`$K`)
  - Year-wise aggregation
  - Experience-based filtering and summaries
- **Custom Visual Design**:
  - Dark theme
  - Gradient backgrounds
  - Button slicers for user-friendly interaction

---

## 📁 Files

- `DataScience_Salary.pbix`: Main Power BI file (optional to upload)
- `README.md`: Project documentation
- `Dashboard Screenshot.png`: Preview image

---

## 📈 Measures Used (Sample DAX)

```DAX
Formatted Salary = 
"$" & FORMAT(ROUND([avg_salary] / 1000, 0), "#,0") & "K"

```
---
## 📜 License
This project is for educational and portfolio purposes only.

---
## 👤 Author
Developed by Ankit Rana


