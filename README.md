# 📊 Microsoft Power BI Project – End-to-End Data Analysis (5 Stages)

This repository showcases a comprehensive Power BI project demonstrating all **five stages of the data analysis lifecycle**, powered by data sourced and processed through **SQL Server Management Studio (SSMS)** and visualized using **Power BI Desktop**.

---

## 🔍 Project Summary

The analysis integrates two distinct datasets:
- 🎓 **Enhanced Engineering College Placement Records**  
- 🧑‍💼 **Sample Employee Dataset**

The goal is to extract actionable insights related to **student placement trends** and **HR performance metrics**, following a structured analytics pipeline.

---

## ✅ Five Stages of Data Analysis – Implemented

### 1. 🧠 Ask the Right Questions
- What are the key placement success factors by department and batch?
- How does employee satisfaction correlate with attrition or job role?
- Which dimensions influence campus hiring success and workforce retention?

---

### 2. 🛠️ Prepare the Data *(via SSMS)*
- Connected and imported both datasets from **SQL Server databases** using **DirectQuery** and **Import** modes.
- Performed SQL queries for joins, filters, and schema shaping.
- Exported refined views into Power BI.

---

### 3. 🧮 Process the Data *(in Power BI)*
- Built data models with proper relationships, data types, and normalization.
- Created DAX measures and calculated columns for KPIs:
  - `Placement Rate %`
  - `Average Salary by Department`
---

### 4. 📈 Analyze the Data
- Correlation analysis of department-wise placement success vs. student scores.
- Attrition and promotion frequency by gender, department, and experience.
- Identified outliers in offer count, satisfaction scores, and performance ratings.

---

### 5. 📊 Share & Visualize Insights
- Built interactive dashboards using:
  - Bar, Line, Pie Charts
  - Slicers and Drilldowns
  - Card KPIs and Tooltips
- Deployed insights for decision-making in HR and Training departments.

---

## 💾 Files in this Repository

| File Name                            | Description                                             |
|-------------------------------------|---------------------------------------------------------|
| `Prepare The Data.pbix`             | Contains raw data import and preprocessing steps        |
| `Dashboard For HR Data Analysis.pbix` | Final analytical dashboard with insights and KPIs     |
| `README.md`                         | Project overview, methodology, and documentation        |

---

## 🧰 Technologies Used

| Tool                     | Purpose                                          |
|--------------------------|--------------------------------------------------|
| **SQL Server (SSMS)**    | Data querying, preprocessing, schema management |
| **Power BI Desktop**     | Modeling, visualization, and dashboarding       |
| **DAX & Power Query**    | Data transformation and calculated metrics       |

---

## 📌 Use Cases

This project simulates real-world analytics solutions in:
- Campus placement decision-making
- HR workforce optimization
- Institutional performance reporting
- Executive KPI dashboards

---

## 👩‍💻 Author

Created by **Ashmitha R** - with expertise in SQL, Power BI, and end-to-end business intelligence workflows.

---

