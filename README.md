Case Study: Exploring HR Attrition Metrics at Atlas Labs

💡Employee retention is more cost-effective than recruitment - but how do we know who's at risk of leaving?
In this Power BI case study, I analyzed HR data from a fictional company, Atlas Labs, to examine workforce dynamics and identify the drivers of employee attrition. The project was part of my Power BI coursework with DataCamp, simulating how HR analytics can enable better decision-making.
🎯 Objective
The goal was to monitor key HR metrics and understand the factors influencing employee attrition - the voluntary departure of staff from the organization.
🛠️ Tools & Techniques
Power BI Desktop & Service
DAX Functions (e.g., CALCULATE, USERELATIONSHIP)
Snowflake Schema Modeling
Advanced Visuals (Cards, Tree Maps, Matrix, Slicers)

📁 Dataset & Data Modeling
Using a fact table on employee performance and multiple dimension tables (employee details, education, satisfaction levels, etc.), I created a snowflake schema. A dedicated Date Table was generated using DAX for accurate time-based calculations.
🔗 Tables were connected using both active and inactive relationships. Key performance fields like JobSatisfaction, SelfRating, and EnvironmentSatisfaction were linked to lookup tables using USERELATIONSHIP.
📊 Dashboard Walkthrough
1. Overview Dashboard
KPI Cards: Total employees, active/inactive status, and attrition rate
Hiring Trends Over Time: Stacked column visual using USERELATIONSHIP
![image](https://github.com/user-attachments/assets/6ad434f1-8d72-45ba-b987-62a0d4e01872)

OverviewInsight: Attrition rate was 16%, with over 1,200 active employees out of 1,470 total hires.

2. Department & Role Analysis
Clustered bar charts and treemaps visualize.
Active employees by department.
Breakdown by job roles.
![image](https://github.com/user-attachments/assets/ab5919e5-b416-40b7-a9c5-a07a03b5be17)

Employee by job role
Insight: Technology was the largest department.

3. Demographics Dashboard
Visuals for age distribution, gender, ethnicity
Created Age Bins: <20, 20–29, 30–39, 40–49, 50+
![image](https://github.com/user-attachments/assets/0b588ea9-6b0f-4515-a1e4-1ffbd619039f)

Demographics
Insight: Majority of staff are aged 20–29; the company employs 2.7% more women than men.

4. Salary & Ethnicity Analysis
Cards and bar visuals for average salary by ethnic group
![image](https://github.com/user-attachments/assets/ebef5159-ec34-4e54-a80c-c584301a86e3)

Highest Avg Salary
Insight: White employees had the highest average salary; mixed-race employees had one of the lowest.

5. Performance Tracker
Employee-specific dashboards with:
Slicer for employee name
Cards for start date, last review, and next review
Satisfaction measures using CALCULATE and MAX
![image](https://github.com/user-attachments/assets/6e2e3666-4be0-4e31-9327-8c09494cf2e2)

Performance Tracker
Insight: Frequent travelers had the highest attrition rate, even though they make up just 19% of hires.

📈 Key Takeaways
✅ Attrition rate = 16%
 ✅ High turnover among frequent travelers
 ✅ The age 20–29 group forms the majority
 ✅ Need for diversity-aware compensation policies
 ✅ Job satisfaction and manager rating correlate closely with retention
📤 What's Next?
I'll be sharing the full Power BI report with interactive dashboards and the GitHub repo so others can explore and adapt the model.

 📂 GitHub: [github.com/yourusername/HR-Analytics-PowerBI](https://github.com/jaytaraviya241/HR-Analytics-Using-Powerbi)
 🔗 Power BI Report Link: [HR Analytics Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOTk1NWVjOTQtMTNmZC00YThkLTg5YjItNzQyNzdjYzlmMjkyIiwidCI6IjYxYTk0OWRjLTBiNDgtNGM3NC1iMDA4LWFjODlkNmU2MTE4YyJ9)
💬 Final Thoughts
This case study highlights the power of data storytelling in HR. By transforming raw employee data into actionable insights, companies like Atlas Labs can make informed decisions to retain talent and foster a healthier workplace.
