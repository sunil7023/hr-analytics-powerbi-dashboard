# 👥 HR Analytics Dashboard — Employee Attrition (Power BI)

An interactive Power BI dashboard that helps HR and business managers understand **why employees leave**. It breaks down attrition by department, age, education, salary slab, job role and years at the company.

> **Built by:** Sunil Luhar — MIS & Data Reporting | Power BI • Excel • SQL • Looker Studio
> **Live dashboard:** [Click here to view](PASTE-YOUR-POWER-BI-PUBLISH-TO-WEB-LINK-HERE)

---

## 📸 Dashboard Preview

![HR Analytics Dashboard](screenshots/dashboard.png)

---

## 🎯 Project Objective

To turn raw HR records into a simple dashboard that answers questions such as:

- What is our overall attrition rate, and how does it differ by department?
- Which age groups and job roles lose the most employees?
- Does salary level affect attrition?
- How long do employees stay before they leave?

---

## 📊 Key Features

- **KPI cards:** Employee count, Attrition, Attrition Rate, Average Age, Average Salary, Average Years at Company
- **Department buttons:** One click on Human Resources, Research & Development or Sales updates every chart
- **Attrition by Education:** Donut chart
- **Attrition by Age group:** Column chart
- **Attrition by Salary Slab:** Bar chart
- **Attrition by Years at Company:** Area chart
- **Attrition by Job Role:** Bar chart, plus a table of job role by job satisfaction rating (1 to 4)
- **Attrition by Gender:** Tree map
- **Custom dark theme** designed for easy reading

---

## 🔎 Sample Insights (Sales department view)

- Sales has **446 employees** and **92 attrition cases**, an attrition rate of **20.6%**. This is higher than the other department views in the dashboard (roughly 11% to 16%).
- The **26–35 age group** has the most exits (41 cases).
- **Sales Executives (57)** and **Sales Representatives (33)** account for almost all attrition in the department.
- Most leavers are in the **lowest salary slab (up to 5K)**: 43 cases, followed by the 5K–10K slab: 36 cases.
- **Marketing (38%)** and **Life Sciences (32%)** are the largest education groups among leavers.
- In the **Human Resources** department there are **63 employees** and **12 attrition cases** (19.0%). Eight of the 12 leavers are aged 26–35 and ten earn up to 5K.

*(Add your own 2–3 insights after exploring the other departments.)*

---

## 🛠️ Tools & Skills Used

| Area | Details |
|---|---|
| Tool | Microsoft Power BI Desktop |
| Data preparation | Power Query (cleaning, data types, grouping into age and salary bands) |
| Calculations | DAX measure for Attrition Rate, plus aggregations for employee count, attrition count, average age, average salary and average years |
| Data model | Single table (`HR_Analytics`) with age groups and salary slabs for grouping |
| Visuals | KPI cards, donut, column, bar and area charts, tree map, table, slicer buttons |
| Design | Custom dark theme, consistent colors, clear layout |

---

## 📁 Repository Structure

```
hr-analytics-powerbi-dashboard/
│
├── hr_analytics_dashboard.pbix     # Power BI report file
├── data/
│   └── YOUR-DATA-FILE-NAME         # Source data (CSV or Excel)
├── screenshots/
│   └── dashboard.png
└── README.md
```

---

## 📂 Data Source

**Source:** IBM HR Analytics Employee Attrition & Performance sample dataset (public, fictional data).

This project uses sample data for learning and portfolio purposes only. It does not contain any real company or employee information.

Key columns used in the dashboard:

| Column | Meaning |
|---|---|
| EmpID | Employee ID |
| Department | Human Resources, Research & Development or Sales |
| JobRole | Employee job role |
| Age / AgeGroup | Age and age band (18-25, 26-35, 36-45, 46-55, 55+) |
| Gender | Male or Female |
| EducationField | Field of education |
| MonthlyIncome / SalarySlab | Monthly income and salary band |
| YearsAtCompany | Tenure in years |
| JobSatisfaction | Satisfaction rating from 1 to 4 |
| Attritioncount | 1 if the employee left, otherwise 0 |

---

## ▶️ How to Open the Dashboard

1. Download or clone this repository.
2. Install **Power BI Desktop** (free) from Microsoft.
3. Open `hr_analytics_dashboard.pbix`.
4. If Power BI asks for the data source, go to **Home → Transform data → Data source settings** and point it to the file in the `data/` folder.

---

## 📬 Contact

Available for freelance Power BI, Excel and reporting projects on **Upwork** and **Fiverr**.

- **Name:** Sunil Luhar
- **LinkedIn:** [My LinkedIn Profile](PASTE-YOUR-LINKEDIN-LINK-HERE)
- **Upwork:** [My Upwork Profile](PASTE-YOUR-UPWORK-LINK-HERE)
- **Fiverr:** [My Fiverr Profile](PASTE-YOUR-FIVERR-LINK-HERE)
- **Email:** [youremail@gmail.com](mailto:youremail@gmail.com)
