📊 Employee Attrition Analysis

📄 Project Overview

This project analyzes employee attrition trends using an internal HR dataset. The analysis was conducted using Microsoft Excel and Power Query to clean, transform, and visualize the data through an interactive dashboard. The goal was to uncover patterns driving employee turnover and propose actionable strategies for HR decision-makers.


📂 Dataset

 Source: Internal HR data (`HR Attrition Dataset.xlsx`)
 Total Employees: 2,925


Key Data Fields:

 Demographics: Age, Gender, Marital Status, Education
 Job Attributes: Job Role, Department, Years at Company, Promotion History
 Engagement: Job Satisfaction, Work-Life Balance
 Attrition Status and Overtime


🛠 Tools Used

 Microsoft Excel (Pivot Tables, Dashboard)
 Power Query (Data Cleaning & Transformation)


🧹 Data Cleaning & Transformation

Performed in Power Query:

 Removed uninformative columns (e.g., `Over18`, `Standard Hours` — all with constant values)
 Corrected data types (e.g., integers, text, categories)
 Created calculated fields:
   Years in Current Role Group (0–2, 3–5, etc.)
   Age Brackets (18–19, 20–29, etc.)
 Filtered out invalid/missing data
 Standardized inconsistent categorical values (e.g., in `Marital Status`)


💡 Key Insights & Recommendations

🔹 Gender & Age
 63% of employees who left were male; 37% were female.
 Employees aged 30–39 experienced the highest attrition, followed by those aged 20–29.
 🌟 Recommendation: Launch retention initiatives targeting mid-career male professionals, such as mentorship and leadership pipelines.

🔹 Marital Status
 Single employees account for 50% of attrition, compared to married or divorced employees.
 🌟 Recommendation: Build inclusive workplace communities and flexible benefits to support younger, single employees who may feel less rooted.

🔹 Department & Role-Based Attrition
 Highest attrition seen in the R\&D department, followed by Sales.
 Job Roles with Most Attrition:

   Laboratory Technician: 130
   Sales Executive: 113
   Research Scientist: 99
 These roles often involve high stress or limited mobility.
 🌟 Recommendation:

   Conduct stay interviews in high-risk roles.
   Evaluate workload, recognition, and career growth for technicians and junior researchers.

🔹 Promotion & Tenure
 Employees who have not been promoted recently are more likely to leave.
 0–2 years in the same role showed the highest attrition — even among newly promoted staff.
 🌟 Recommendation: Implement structured career development milestones within the first 2 years of role assignment and track promotion eligibility cycles.

🔹 Education
 Employees with Bachelor’s Degrees represented the largest group leaving (\~41%).
 🌟 Recommendation: Offer upskilling programs, tuition support, and certification opportunities to encourage development over departure.

🔹 Overtime & Work-Life Balance
 Employees with low work-life balance ratings and those who work overtime had significantly higher attrition.
 🌟 Recommendation: Promote workload balancing policies, flexible scheduling, and periodic burnout checks through employee pulse surveys.


📁 Folder Structure

Employee-Attrition-Analysis/
🔽 README.md                          ← This project summary
🔽 data/
🔾   └️ HR Attrition Dataset.xlsx      ← Original dataset
🔽 analysis/
🔾   └️ Employee Attrition Analysis.xlsx ← Main workbook with Power Query and dashboard
🔽 outputs/
🔾   └️ Employee Attrition Report.pdf  ← Exported dashboard
🔽 visuals/
🔾   └️ dashboard_screenshot.png       ← Dashboard preview

![Dashboard Screenshot](visuals/dashboard_screenshot.png)
