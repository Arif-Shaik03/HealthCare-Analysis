# HealthCare-Analysis

# 🏥 Hospital Healthcare Analytics Dashboard

This is a full-stack **Hospital Healthcare Dashboard** project using **Excel**, **MySQL**, and **Power BI** (June 2025 version). It showcases modern data analyst skills including data cleaning, advanced SQL queries, and an interactive dashboard with dynamic visuals, toggles, and insights crucial for healthcare operations.

---

## 📌 Overview

**Objective**:  
To provide hospital stakeholders with a data-driven visual system to monitor patient inflow, departmental efficiency, gender trends, and length of stay using modern BI tools.

**Tools Used**:
| Tool       | Role in Project                              |
|------------|-----------------------------------------------|
| ✅ Excel   | Raw data cleaning and transformation          |
| ✅ MySQL   | Data modeling, joins, and query building       |
| ✅ Power BI (June 2025) | Dashboard building & data storytelling |

---

## 📁 Project Structure

```text
📦 Hospital_Healthcare_Dashboard
├── Hospital Dashboards.pbix     # Power BI file with full visuals
├── README.md                    # Project documentation (you’re reading it)
├── screenshot_1.png             # Dashboard Overview
├── screenshot_2.png             # Toggle Table View
├── screenshot_3.png             # Department Drilldown



🔧 Workflow Summary
1. Excel – Data Cleaning
    • Cleaned and structured patient data

    • Removed nulls, duplicates, and ensured consistent formatting

    • Final output exported for MySQL loading

2. MySQL – Querying
    • Created normalized schema with tables:

    • patients, admissions, doctors, departments

Wrote SQL queries to:

    • Calculate readmission rates

    • Count patients by gender & department

    • Average stay duration by age/gender

Example SQL:

sql
Copy
Edit
SELECT d.name AS Department, COUNT(p.patient_id) AS TotalPatients
FROM patients p
JOIN departments d ON p.department_id = d.id
GROUP BY d.name;
3. Power BI – Dashboard Development
   • Used June 2025 version with enhanced UI capabilities

Custom visuals include:

   • KPIs for patient count, stay duration

   • Department-level slicers & charts

   • Gender and age-based analysis

   • Toggle switch to show/hide detailed table view

   • Custom date filters and drilldowns

📸 Dashboard Screenshots
✅ Home Overview
     
✅ Dashboard Overview
     

✅ Toggle Interaction
     
  

✅ Patient Dashboard 
    

✅ Doctor Dashboard 
    


✅ Surgery Dashboard 
    

✅ Finance Dashboard
    




📊 Key Insights

  • 🏥 Emergency & General Medicine departments handle the most admissions

  • 👵 Elderly patients have longer stay durations and higher readmission risk

  • 📅 Peak patient traffic occurs early in the week

  • 👨‍⚕️ Pediatrics shows a higher female-to-male ratio

🚀 How to Run This Project
   1 . Clone this repository or download the ZIP

   2 . Open Hospital Dashboards.pbix in Power BI Desktop (June 2025 or later)

   3 . Optional: Connect to MySQL database if using live queries

   4 . Interact with slicers, toggles, and charts

💼 Ideal For
This project is perfect for:

  • 💡 Data analyst portfolio showcase

  • 🧪 Healthcare analytics use cases

  • 🛠️ Demonstrating Excel → SQL → BI stack integration

  • 🎯 Power BI UI/UX with modern gradients and toggle visuals


🙋 About Me
I’m a passionate Data Analyst skilled in building data-driven solutions and compelling dashboards. Connect with me:
