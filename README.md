# 📊 Data Job Dashboards — Power BI

## 📌 Overview
This project explores a global dataset of data-related job postings to answer key questions:
- Which data roles pay the most, on both a yearly and hourly basis?
- How has job demand trended throughout 2024?
- What does a specific role look like in terms of remote work, degree requirements, benefits, job type, and hiring platform?

## 🧩 Dashboard 1: Data Job Dashboards 
<img width="1425" height="805" alt="Data_Job_Dashboards" src="https://github.com/user-attachments/assets/49b6c550-7709-48f1-a6b6-c81d365ce58a" /> -->
 - **Job Count** — Total job postings analyzed (479K)
 - **Star Rating** — Aggregate employer/job rating
 - **Yearly Median Salary** — Overall median yearly salary ($113K)
 - **Hourly Median Salary** — Overall median hourly rate ($48)

   Visuals
   - **Job Trend Line Chart** — Monthly job posting volume across 2024, with a trendline showing overall demand direction
   - **Hourly vs. Yearly Salary Scatter Plot** — Compares median hourly and yearly pay across roles to highlight relative compensation positioning (e.g., ML Engineer vs. Data Analyst)
   - **Highest Paying Jobs Bar Chart** — Ranks roles by median yearly salary
   - **Job Title Matrix Table** — Drillable breakdown of job count, yearly/hourly median salary, and a sparkline of job trend per role

Filter
  - Slicer on Job_title to isolate any single role across all visuals
## 🔍 Dashboard 2: Job Title Drill-Through (Detail View)
<img width="1507" height="800" alt="Job_title_drill_through" src="https://github.com/user-attachments/assets/a67fc3cd-84f4-42b5-9b3e-711460566b45" />

## 🛠️ Tools & Tech
- Power BI Desktop — Data modeling, DAX measures, and report design
- DAX — Custom measures for medians, counts, and percentage calculations
- Power Query — Data cleaning and transformation

## 🙌 Acknowledgements
The purpose of recreating the dashboard was to understand the workflow, techniques, and concepts used in Power BI and to develop hands-on dashboard-building skills with the help of Luke Baraousse
