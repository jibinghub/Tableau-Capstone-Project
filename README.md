# Tableau-Capstone-Projec📊 Tableau Capstone Project – HR Analytics Dashboard
📘 Project Summary
This project presents a full HR Analytics solution built in Tableau using the HR Data (Attrition+) dataset.
The dashboards analyze key aspects of workforce behavior — employee demographics, compensation trends, career growth, promotion patterns, and attrition risks — enabling HR teams to make data-driven decisions around hiring, retention, salary strategy, and employee experience.
The project includes 3 interconnected dashboards + storytelling pages, offering both high-level summaries and deep-dive insights.

🔗 Tableau Public Link
👉 https://public.tableau.com/app/profile/jibin.ahammed/viz/finaldashbored/Story1?publish=yes

🔍 Key Insights
Workforce age is concentrated between 25–40, with hiring peaks at age 30–35.
Gender distribution varies by age, but most job roles show a male-heavy trend.
Salary progression increases with job level, peaking at mid-senior levels.
Attrition risk is highest among low-income + low-satisfaction employees (seen in heatmap).
Promotion delays differ strongly by role — e.g., Research Directors have longer tenure before promotion.
Recently promoted employees make up the largest promotion segment.
🛠️ Features Used
LOD Expressions
Used for fixed-level KPIs such as Total Employee Count, Average Salary Hike, and Avg Years Since Last Promotion.
Parameter Control
Used to dynamically highlight Promotion Status in the donut chart.
Dashboard Actions
Cross-filtering between job role, department, satisfaction, and other charts.
Table Calculations
Used for running totals, label formatting, highlight effects.
Story Pages
Three data storytelling sequences summarizing key insights for:
Employee Demographics
Compensation & Rewards
Experience, Promotion & Career Growth
📁 Repository Contents
root/
│
├── data/
│   └── HR Data.xlsx
│
├── docs/
│   ├── Dataset Assessment Document (DAD).pdf
│   ├── Business Requirements Document (BRD).pdf
│   └── Functional Requirements Document (FRD).pdf
│
├── tableau_workbook/
│   ├── HR_Analytics_Dashboard.twbx
│   └── Story Workbook
│
├── screenshots/
│   ├── demographics_dashboard.png
│   ├── compensation_dashboard.png
│   └── promotion_dashboard.png
│
└── README.md
👤 Author
Jibin
