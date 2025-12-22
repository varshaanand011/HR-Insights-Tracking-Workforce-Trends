***HR Insights: Tracking Workforce Trends – Exploratory Data Analysis (EDA)***

This project presents an exploratory data analysis of workforce trends using the HR-Insights-Tracking-Workforce-Trends dataset. The analysis focuses on understanding employee attrition patterns based on age groups and tenure, enabling HR teams to identify workforce stability risks and improve retention planning using data-driven insights.


 📁 Project Structure


HR-Insights-Tracking-Workforce-Trends/
│
├── README.md                          <-- You are here
├── data/
│   ├── raw/                           <-- Original workforce dataset
│   └── cleaned/                       <-- Cleaned workforce dataset
├── notebooks/                         <-- Jupyter notebooks with full analysis
├── scripts/                           <-- Data cleaning & visualization scripts
├── reports/
│   └── analysis_report                <-- Summary of findings and insights
└── visuals/                           <-- Generated charts and plots


 🎯 Project Objectives

Aim of the Project:

* To analyze employee data in order to uncover patterns related to employee behavior, satisfaction, and attrition.
* To examine key factors influencing employee turnover, including department, tenure, and work-life balance.
* To identify correlations and trends that impact employee retention.
* To derive actionable insights that support proactive and data-driven HR decision-making.
* To assist organizations in developing strategies that improve employee engagement, reduce attrition, and retain top talent.

Phase 1 — Problem Definition & Dataset Selection

Problem Statement

Employee turnover poses a significant challenge for organizations. High attrition rates lead to increased recruitment and training costs, loss of experienced talent, reduced productivity, and disruptions in team stability. Many organizations lack clear insights into the underlying factors that contribute to employee dissatisfaction and voluntary exits.

* By identifying the drivers of employee attrition, organizations can:
* Improve employee engagement and job satisfaction
* Design effective and targeted retention strategies
* Optimize compensation, career progression, and work-life balance initiatives
* Reduce operational costs associated with frequent hiring
* This project applies exploratory data analysis (EDA) techniques to uncover patterns and trends in employee data that explain attrition behavior and support proactive HR decision-making.

Dataset Details

Dataset Name: HR-Insights-Tracking-Workforce-Trends
Source: Workforce analytics dataset
Key Features:

  * Age Group
  * Tenure
  * Attrition Flag (Yes / No)
  Analysis Focus: Workforce trends and attrition behavior


 Phase 2 — Data Cleaning & Pre-processing

Dataset Issues Identified and Handled

✔ Missing Value Checks

* Verified completeness of age group, tenure, and attrition fields

✔ Data Standardization

* Standardized age group labels
* Ensured consistent encoding of attrition flags

✔ Feature Engineering

* Categorized tenure into experience bands
* Prepared age group categories for analysis

✔ Data Validation

* Checked for invalid tenure values
* Confirmed logical relationships between age group and tenure

Output:
Cleaned dataset saved in:
/data/cleaned/HR_Insights_Workforce_Trends_Cleaned.csv


 Phase 3 — Exploratory Data Analysis (EDA)

Performed Univariate, Bivariate, and Multivariate analysis with multiple visualizations.

 🔹 Univariate Analysis

* Distribution of attrition flags
* Workforce distribution by age group
* Tenure distribution across employees

 🔹 Bivariate Analysis

* Attrition vs Age Group
* Attrition vs Tenure
* Tenure patterns across attrition status

🔹 Multivariate Analysis

* Combined analysis of age group, tenure, and attrition
* Workforce stability trends across multiple demographic factors


 Visualizations Created

* Bar charts
* Count plots
* Box plots
* Line charts (tenure trends)

Libraries Used:

* Matplotlib
* Seaborn


 Key Insights

* Employees with shorter tenure show higher attrition rates
* Certain age groups are more prone to early attrition
* Attrition risk decreases as employee tenure increases
* Workforce stability improves with experience and time in the organization


 Conclusion

This project demonstrates a structured **workforce analytics EDA pipeline:

* Clear HR problem framing
* Accurate data cleaning and validation
* Insightful analysis using limited but meaningful features
* Clear visual storytelling focused on attrition behavior

The analysis helps HR teams better understand **who is leaving and when**, enabling targeted retention strategies for early-tenure and high-risk age groups.



 How to Use This Project

Clone the repository:

bash
git clone https://github.com/varshaanand011
/HR-Insights-Tracking-Workforce-Trends


Install dependencies:

bash
pip install -r requirements.txt

Explore the project:

* Analysis notebooks: `/notebooks/`
* Visualizations: `/visuals/`
* Summary insights: `/reports/`



🛠 Technical Skills Demonstrated

* Python (Pandas, NumPy)
* Data Cleaning & Validation
* Exploratory Data Analysis (EDA)
* Workforce Trend Analysis
* Data Visualization (Matplotlib, Seaborn)


 Author

Varsha Anand N
GitHub: [https://github.com/your-username](https://github.com/varshaanand011)
