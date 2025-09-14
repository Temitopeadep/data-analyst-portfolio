# Portfolio Projects

This document highlights my data analytics and visualization projects, covering tools such as Power BI, Tableau, Python, SQL, and Excel. Each project demonstrates my ability to extract insights, create dashboards, and make data-driven recommendations.

---

# SmartMum: Maternal Health Risk Prediction Through AI (XGBoost Model)
![Model Accuracy](https://img.shields.io/badge/Accuracy-89.6%25-brightgreen)
![AUC Score](https://img.shields.io/badge/AUC-0.95-blue)

## Overview
This project was developed for the 3MTT knowledge showcase (July Edition), it's an AI-powered maternal health risk prediction tool built using BigQuery ML (XGBoost) and integrated with Power BI and Power Apps. It enables early identification of pregnancy-related complications by analyzing clinical and demographic data

## Problem Statement 
Many pregnant women, especially in underserved areas, miss early detection of health risks due to limited access to timely screening and data insights. There’s an urgent need for a smart, accessible tool that predicts maternal health risks early  supporting safer pregnancies and informed interventions.

## Project Goal
To reduce maternal health risks through early prediction and actionable insights for healthcare providers and expectant mothers.

## Project Components
### Executive Summary
1. Model: XGBoost via BigQuery ML.
2. Accuracy: 89.6%
3. 	Recall: 87.3%
4. Precision: 88.1%
5. AUC Score: 0.95
6. Dataset Size: 1,000 Records
###  Key Features
- Uses real health indicators to predict Low / Medium / High risk.
- Power BI dashboard with demographics, clinical variables, and trends.
- Power Apps form for public access without technical knowledge.

### Data Source
Dataset: [Maternal Health Risk | Kaggle](...)
- 1,000 anonymized records  
- Core columns: Age, BP, BS, BodyTemp, HeartRate, BMI, ANC Visits, Trimester, Region, Education  
- Enhanced columns: Delivery History, Hospital Access

  ### Dashboard
![Screenshot](https://github.com/Temitopeadep/SmartMum--Maternal-Health-Risk-Prediction/blob/main/dashboard1.png)
![Screenshot](https://github.com/Temitopeadep/SmartMum--Maternal-Health-Risk-Prediction/blob/main/dashboard2.png)

### PowerApps Interface
![Screenshot](https://github.com/Temitopeadep/SmartMum--Maternal-Health-Risk-Prediction/blob/main/powerapp%20interface.png)

### Findings
1. Model Performance: The XGBoost model achieved strong metrics — Accuracy: 89.6%, Recall: 87.3%, Precision: 88.1%, and AUC: 0.95, confirming its reliability in predicting maternal health risks.
2. Risk Distribution: Most cases fall into the Medium Risk category, suggesting a window for preventive care. High-risk cases, though fewer, remain clinically significant.
3. ANC Visits: Low or zero antenatal care visits strongly correlate with higher maternal health risk levels. Regular ANC visits are protective.
4. Clinical Indicators: Elevated BMI, Heart Rate, Blood Pressure, and Body Temperature are key predictors of high-risk classifications.
5. Demographics & Access: Both urban and rural regions exhibit similar risk trends. However, women with limited access to facilities or education face compounded risks.

### Recommendation
* Promote early and frequent ANC visits to shift risk levels from high to medium/low.
* Integrate AI predictions into frontline healthcare tools for early intervention.
* Train health workers to identify and act on clinical indicators such as elevated BP, BMI, and heart rate.
* Expand outreach in low-access areas, especially for under-educated and rural populations.
* Scale the SmartMum app across regions to support real-time maternal risk assessment.

  ###  Tools Used
- Google BigQuery ML – for training the XGBoost classification model to predict maternal risk levels.
- Microsoft Power BI – for data visualization and dashboard development.
- Microsoft Power Apps – user-friendly maternal risk prediction form.
- GitHub – for hosting project code and documentation
- ChatGPT (by OpenAI) – for technical assistance

### Links
- [BigQuery](https://console.cloud.google.com/bigquery?sq=954458391922:ad90499052664c02a6328e99d623c19f)
- [Power App](https://apps.powerapps.com/play/e/default-18f15a3f-ea52-4261-b725-0b0f0d1bab03/a/3f4e200a-5ef6-4243-a44a-16aac7ab0a22?tenantId=18f15a3f-ea52-4261-b725-0b0f0d1bab03&hint=19c11dff-6196-48df-8786-c149e04f3516&source=sharebutton&sourcetime=1752784196040)

---

## SUPERSTORE SALES DASHBOARD 

## Project Overview
The Superstore Sales Dashboard provides a detailed analysis of sales, profit, and customer behavior across product categories, regions, and order priorities. This project was created to transform raw sales data into actionable insights for better business decision-making.

## Tools & Skills Used
- Excel
- Power Query
- Pivot Tables & Charts
- Data Cleaning & Transformation
- KPI Tracking & Reporting

## Key Features

Overall Metrics:

Total Sales: $14,915,600.82

Profit: $1,521,767.96

Total Orders: 8,399

## Dashboard
![excel project](https://github.com/user-attachments/assets/d7329e2b-f6ad-480e-954a-7d7c4bd85b17)


## Insights & Business Impact
1. Focus on profitable regions and products while addressing underperforming items.
2. Support inventory and sales strategy optimization.
3. Clear sales trend tracking for forecasting and planning.

## Key Learnings
- Dashboard design for data storytelling.
- Identifying and visualizing KPIs for decision-making.
- Hands-on practice with data analytics workflow (cleaning → analysis → insights).



---

 # Professional-Trend-Analysis

## Overview
This dashboard presents an analytical overview of 630 professionals across multiple industries, roles, and demographics. The objective is to derive trends in salary, education, career switching factors, gender representation, and technical preferences.
## Data Cleaning Steps
- Promoted Header
- Removed Empty Columns
- Removed Duplicate Rows
- Introduced Age Group Classification
- Removed Duplicate Columns

  ## Findings
- Demographic Overview: Total Professionals Surveyed: 630, Average Age: 29.87 years, Programming Languages Used: 6
- Industry Distribution: Top Industry: "Others" followed by Tech, Finance, and Education.
- Role Distribution: The majority of respondents are Data Analysts (60.48%), followed by Others (28.25%). Minor roles include Data Engineers, Data Scientists, Database Developers, and Data Architects (combined under 12%).
- Gender Representation: Male: 74.29% and Female: 25.71%
- Salary Range by Role: Data Analysts dominate across all salary bands, particularly in lower to mid-range categories (e.g., 0–40k, 41k–65k, 66k–85k), Data Engineers and Data Scientists show more concentration in higher salary bands (125k–225k). The “Others” category includes a wide salary spread, reinforcing the mixed nature of the roles grouped here.
- Education vs Salary: Bachelor’s and Master’s degrees are most common among higher salary bands (over 66k), Associates and High School level education dominate the lowest salary bands (0–40k), PhDs are few but generally associated with salaries over 125k.
- Career Switch & Motivation Factors: Major reason for switching careers: Better Salary, Other common motivations include: Remote Work, Work-Life Balance, Good Culture

  ## Dashbord
 <img width="1462" height="757" alt="trend analysis" src="https://github.com/user-attachments/assets/941f540f-4f0f-4fa5-b9fe-d6c2659a44ae" />


  ## Obervation
1. Most survey data and insights are skewed toward the Data Analyst profile, which should be taken into account in interpretation.
2. A clear gender gap is observed, suggesting a potential diversity challenge in data-related professions.
3. High salary brackets correlate with more technical roles like Data Engineer and Data Scientist, while Data Analysts are more prevalent in lower brackets.
4. Higher education levels, particularly Master’s and PhDs, positively influence salary prospects in data professions.
5. Compensation and flexible work environments are strong drivers for job changes and retention.

## Recommendation
1. Talent Strategy: Invest in structured career paths for Data Analysts to grow into higher-paid technical roles.
2. Diversity & Inclusion: Explore initiatives to increase female participation and address gender imbalance.
3. Upskilling & Education Support: Encourage advanced education (e.g., Master’s programs, certifications) to unlock higher salary potential for employees. and offer training to transition Associates or High
4. School-level employees into more skilled roles.
5. Workplace Policies: offering more remote work options and focusing on work-life balance, as these are highly valued.




---

## Project Four – # Titanic Survival Analysis  

## Project Overview  
This project explores the famous Titanic dataset using **Python** and **pandas** to uncover survival patterns among passengers. The analysis provides insights into demographics, ticket class, and embarkation points that influenced survival rates.  

## Objectives  
- Analyze passenger data to uncover survival trends  
- Explore the impact of sex, class, and embarkation point on survival rates  
- Strengthen data wrangling and visualization skills  

## Tools & Libraries  
- **Python**  
- **pandas** for data manipulation  
- **matplotlib** and **seaborn** for data visualization  

## Key Insights  
- **Survival Rate by Sex**: Female passengers had a significantly higher survival rate compared to males.  
- **Overall Survival Rate**: About **38%** of passengers survived the tragedy.  
- **Survival Rate by Class**: First-class passengers had the highest survival rate, while third-class passengers faced the most risk.  
- **Embarkation Points**: Most passengers boarded from Southampton, followed by Cherbourg and Queenstown.  

## Visualizations  
The project includes visualizations such as:  
- Survival rate by gender  
- Survival rate across passenger classes  
- Survival distribution by embarkation points  
- Overall survival percentage
  
![titanic1](https://github.com/user-attachments/assets/5a020d97-6123-4943-a74b-347dc47b027a)
![titanic2](https://github.com/user-attachments/assets/0353fe78-0e0d-4b92-8bb1-d19b63112b15)
![titanic3](https://github.com/user-attachments/assets/49c46e50-2b3d-40a2-a400-88dc5ddf7d06)

## Learning Outcomes  
This project helped me:  
- Practice data cleaning, transformation, and analysis using **pandas**  
- Improve visualization skills with **matplotlib** and **seaborn**  
- Translate raw data into meaningful insights about a historical event  



---

# SQL – Superstore Database & Analytics
## Project Overview
This project involved designing and analyzing a Superstore Database from scratch using Microsoft SQL Server. It was a hands-on way to strengthen my skills in database modeling, data cleaning, and SQL-based business analytics.

## What I Worked On
1. Designed a normalized database schema.
2. Imported and cleaned raw Superstore data.
3. Populated tables using the INSERT method with mock data.
4. Wrote complex SQL queries to extract business insights.

 ## Database Schema
The database contained 4 main tables:
- CUSTOMER
- ORDERS
- ORDER STATUS
- USERS


## Key SQL Queries & Insights

1. Total Revenue per Order by Customer.
   -  Showed how much revenue each order generated per customer.
   -  Useful for identifying top clients.

2. Top 10 Product-Customer Combinations by Profit
   - Identified the most profitable product-customer-region combinations.
   - Supports strategic targeting.

3. Top 20 High-Volume Orders by Category
   - Highlighted product categories driving large-volume orders.
   - Valuable for inventory planning.

3. Top 20 Orders with Customer Details & Date Filter
   - Focused on recent high-volume orders by customer and category.
   - Great for spotting trends and bulk buyers.
     
![SQL1](https://github.com/user-attachments/assets/abf6d092-3a67-4a7b-9f1d-d7946c282e18)
![SQL2](https://github.com/user-attachments/assets/17162219-72e4-4091-a119-fd77f22dcc33)
![SQL4](https://github.com/user-attachments/assets/98b10924-fede-4be0-85dd-67abcb00adb2)
![SQL5](https://github.com/user-attachments/assets/3d46d340-eeef-4358-8890-18c9a3e2f886)
![SQL6](https://github.com/user-attachments/assets/9c73bb1c-1924-48f8-86a5-54bcc19e81a8)
![SQL7](https://github.com/user-attachments/assets/7b68afa5-6044-438b-8f44-916b8f65ce9f)
![SQL8](https://github.com/user-attachments/assets/dcd3b4f3-d1d9-48c4-82b5-0ec0f0762508)

## Skills Gained
- Database design & normalization
- Writing optimized SQL queries
- Data cleaning & transformation in SQL
- Turning raw data into actionable business insights


---

 # HR-EMPLOYEE-ATTRITION-DASHBOARD  

## Project Overview  
This HR Employee Attrition Dashboard was developed to help HR professionals generate actionable insights that can reduce employee attrition and improve workforce retention strategies.  

## Data Source  
- Meriskill  

## Tools  
- Excel: Data Cleaning and Transformation  
- Tableau: Data Transformation, Exploratory Analysis, and Visualization  

## Data Cleaning  
All data cleaning and transformation were carried out in Excel:  
1. Removed redundant columns  
2. Renamed columns for clarity  
3. Dropped duplicate records  
4. Cleaned inconsistent entries  
5. Removed missing (NaN) values  
6. Performed data transformation for analysis readiness  

## Data Analysis  

### Demographics  
Summarized employee statistics, including age group, gender, distance from home, and marital status. Provided insights into workforce diversity and commuting patterns for informed decision-making.  

### Turnover Analysis I  
Offered insights into employee attrition by department, job role, business travel, and tenure in the current role. Helped identify areas needing better workforce management and retention strategies.  

### Turnover Analysis II  
Explored attrition by job level, overtime, performance rating, monthly income, and attrition increase levels. Provided critical insights for effective HR strategies and decision-making.  

### Employee Wellness  
Analyzed employee wellness factors, including monthly income, hourly rate, relationship satisfaction, performance rating, environmental fit, job involvement, and work-life balance. Highlighted insights to guide HR in developing employee-friendly policies.  

## Results and Findings  
- Total employees: 1,470  
- Total attrition: 237 employees  
- Employees living near the office were most affected (144 of 237)  
- Single employees recorded the highest attrition (61%)  
- Male employees had the highest number of attrition cases  
- Employees with moderate job involvement were most affected  
- 115 attritions linked to environmental status  
- 112 employees reported job dissatisfaction  
- Employees promoted on time were affected more  
- Average Monthly Income: 6,503  
- Average Hourly Rate: 65.89  
- 84.3% of employees who left had low performance ratings  
- Entry-level employees were most affected  
- 156 employees who rarely traveled were impacted  

## Dashboard Visuals  

![HR ATTRITION DASHBOARD](https://github.com/Temitopeadep/HR-EMPLOYEE-ATTRITION-DASHBOARD/assets/142262047/27d5d096-e1e0-4bd3-8fc9-ac95251a03b9)  

![DEMOGRAPHICS](https://github.com/Temitopeadep/HR-EMPLOYEE-ATTRITION-DASHBOARD/assets/142262047/c19d310b-d177-4f9a-83d4-54275d3ea20c)  

![TURNOVER ANALYSIS I](https://github.com/Temitopeadep/HR-EMPLOYEE-ATTRITION-DASHBOARD/assets/142262047/f9e1866f-cb43-4f7e-af52-80adc991c412)  

![TURNOVER ANALYSIS II](https://github.com/Temitopeadep/HR-EMPLOYEE-ATTRITION-DASHBOARD/assets/142262047/2846844a-f6f9-4064-b2e4-a1be16560733)  

![EMPLOYEE WELLNESS](https://github.com/Temitopeadep/HR-EMPLOYEE-ATTRITION-DASHBOARD/assets/142262047/af51ca2f-9154-4964-b5a1-cc74a6f36e20)  

## Recommendations  
- Investigate reasons behind low performance ratings across employees.  
- Review organizational structure and policies affecting single male employees.  
- Ensure business travel opportunities are more evenly distributed among staff.  

---
This project demonstrates how Tableau can transform HR data into actionable insights that support employee engagement, wellness, and retention strategies.  

[Tableau Public](https://public.tableau.com/app/profile/temitope.adepoju/viz/HREMPLOYEEATTRITIONDASHBOARD/PAGE1)
[Linkedin](www.linkedin.com/in/temitope-elizabeth-adepoju-25bb40160)

