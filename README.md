# 📊 HR Analytics Dashboard – End-to-End Workforce Intelligence Project

## Overview

What truly drives employee attrition?
Is it compensation, workload, job satisfaction, or something deeper?

This project delivers a complete end-to-end HR Analytics solution, transforming raw employee data into actionable workforce intelligence. The analysis goes beyond surface-level reporting to uncover key drivers of attrition, workforce patterns, and retention risks.

Built using Power BI Power Query, this project follows a structured analytics workflow, from data cleaning and modeling to insight generation and executive-ready dashboards.

---

## Live Interactive Dashboard

[Interact with the dashboard here](https://www.novypro.com/profile_about/1768603691117x499853414232449100?Popup=memberProject&Data=1778115277995x425659025797783230)

---

## Business Objectives

This project is designed to answer critical stakeholder questions:

* What is the current workforce composition?
* What is the attrition rate, and where is it highest?
* Which employee segments are most at risk of leaving?
* What are the key drivers of attrition?
* What actions can improve employee retention and engagement?

---
## Dataset Description
This HR dataset consists of 1,470 employee records designed to explore the factors influencing employee attrition and performance. It combines demographic data, such as age and education, with professional details like job role, department, and monthly income, as well as subjective metrics including job satisfaction, work-life balance, and relationship ratings. The dataset serves as a comprehensive tool for identifying patterns in turnover and understanding how various workplace factors impact long-term employee retention.

**Raw Data Snapshot**
<img width="1366" height="494" alt="Raw Dataset" src="https://github.com/user-attachments/assets/508afaf1-55c8-421e-8406-ac92da67305d" />

--- 

## Project Workflow

### 1. Data Cleaning & Transformation

* Cleaned and transformed raw HR data using **Power Query**
* Handled Inconsistent formatting
* Checked for duplicates and missing values, and discovered that there were no duplicate records or missing entries in the dataset.
* Corrected incorrect data types for analytical accuracy
* Removed irrelevant/unnecessary columns
* Created a **surrogate key** to ensure data integrity

<img width="1366" height="562" alt="Data Preparation 1" src="https://github.com/user-attachments/assets/b217475d-8e28-46d2-a9f8-c7e2bc7dcee4" />

<img width="1366" height="561" alt="Data Preparation 2" src="https://github.com/user-attachments/assets/3bc5f9c9-be3d-4581-83a3-659f0f3c0ac1" />

<img width="1365" height="561" alt="Data Preparation 3" src="https://github.com/user-attachments/assets/aba6dc5e-5248-4602-9719-e0b19ca833d0" />

---

### 2. Data Modeling (Star Schema)

* Converted flat dataset into a **structured data model**
* Built:

  * **Fact Table** (Employee Records)
  
  <img width="1366" height="557" alt="HR Fact Table" src="https://github.com/user-attachments/assets/14b1abc3-7fdc-40ab-ac4f-2d7ef1f6b82b" />

  * **Dimension Tables** (Department_DIM & Employee_DIM Tables)
  <img width="1366" height="558" alt="Employee_DIM Table" src="https://github.com/user-attachments/assets/d42fe340-6f3a-4679-89c6-ce6cdd59e017" />

  <img width="1366" height="558" alt="Depatment_DIM Table" src="https://github.com/user-attachments/assets/1ef3ee0a-4c47-4bff-bbfb-7ec3e60094c1" />

* Established relationships for efficient querying
* Designed a scalable star schema for performance optimization
<img width="996" height="473" alt="Data Modeling" src="https://github.com/user-attachments/assets/000fe051-cfc6-410b-9438-20c4bcd0a3f5" />

---

### 3. DAX & Measures

* Developed key business metrics using **DAX**, including:

  * Total Headcount
  * Attrition Count
  * Attrition Rate (%)
  * Average Age
  * Average Tenure
* Ensured accurate aggregation across all dimensions

<img width="866" height="455" alt="DAX Measures" src="https://github.com/user-attachments/assets/3045ca38-6c5a-414f-9696-463544d657e3" />

---

### 4. Dashboard Design & Wireframing

* Created structured wireframes using **Figma**
* Designed 3 analytical dashboards focused on:

  * Workforce Overview
  * Attrition Analysis
  * Attrition Drivers & Insights
* Prioritized **clarity, storytelling, and decision-making**

<img width="1920" height="1080" alt="HR Analytics Dashboard 1" src="https://github.com/user-attachments/assets/67b82fe8-03d2-424b-8a62-aaeed920c85e" />

<img width="1920" height="1080" alt="HR Analytics Dashboard 2" src="https://github.com/user-attachments/assets/bd79e8ae-6dcc-4904-b9ce-326986edb698" />

<img width="1920" height="1080" alt="HR Analytics Dashboard 3" src="https://github.com/user-attachments/assets/456c8a07-3fb3-4440-bed2-c861dafc4f72" />

---

## Dashboard Preview

---

## Dashboard Breakdown

### 1. Workforce Overview

**Purpose:** Understand workforce composition at a glance

<img width="967" height="546" alt="Page 1" src="https://github.com/user-attachments/assets/21bd36a0-9064-4baa-be12-b08b0f913e5b" />

**Key Insights:**

* Total workforce: **1,470 employees**
* Average age: **36.9 years**
* Average tenure: **7.0 years**
* Workforce is **male-dominated (60%)**
* **Sales Executive** has the largest headcount
* **Divorced employees show lower attrition**, while **single employees have higher attrition counts**

---

### 2. Attrition Analysis

**Purpose:** Identify where attrition is occurring

<img width="967" height="544" alt="Page 2" src="https://github.com/user-attachments/assets/0c12bdf2-e0ff-4810-8973-5841aa0c632e" />


**Key Insights:**

* Overall attrition rate: **16.12%**
* **Human Resources** shows the highest attrition rate
* High attrition observed in:

  * Sales Representatives
  * Research Directors
* **Younger employees (18–24)** show higher attrition tendencies
* Slightly higher attrition observed among **male employees**

---

### 3. Attrition Drivers & Insights

**Purpose:** Understand why employees are leaving

<img width="967" height="545" alt="Page 3" src="https://github.com/user-attachments/assets/b04e426c-9026-46f5-8a3b-236243ed2fbc" />

**Key Insights:**

* **Overtime is a major driver of attrition**
* Employees with **low job satisfaction (levels 1–2)** are significantly more likely to leave
* **Higher-income employees show higher attrition rates**
* Poor **work-life balance strongly correlates with attrition**
* Low **environment satisfaction** contributes to employee exits

**Top 2 Drivers of Attrition:**

1. Overtime workload
2. Low job satisfaction

---

## Key Value Delivered

This project moves beyond dashboards to provide:

* ✅ **Data-driven retention insights**
* ✅ Identification of **high-risk employee segments**
* ✅ Clear understanding of **attrition drivers**
* ✅ A foundation for **HR decision-making and strategy**

---

## Recommendations

Based on the insights uncovered from the analysis, the following recommendations are proposed to help improve employee retention, workforce satisfaction, and overall HR decision-making:

### 1. Reduce Excessive Overtime

The analysis revealed that employees working overtime are significantly more likely to leave the organization. Management should:

* Monitor overtime frequency across departments
* Redistribute workload where necessary
* Encourage healthier work-life balance practices
* Introduce flexible work arrangements where possible

---

### 2. Improve Employee Satisfaction & Engagement

Low job satisfaction strongly correlates with higher attrition. To address this:

* Conduct regular employee engagement surveys
* Improve communication between employees and management
* Recognize and reward employee contributions
* Create clearer career growth opportunities

---

### 3. Department-Specific Retention Strategies

Departments with high attrition rates require targeted interventions:

* Investigate workload and management practices
* Conduct departmental satisfaction reviews
* Implement tailored retention initiatives

---

### 4. Promote Workplace Well-Being

Poor work-life balance and low environment satisfaction contribute to employee exits. The organization should:

* Foster a healthier workplace culture
* Encourage employee wellness initiatives
* Improve overall workplace conditions and support systems

---

## Dashboard Features

The dashboard was designed with both usability and interactivity in mind to enhance stakeholder experience and data exploration.

### Interactive Filters (Slicers)

Users can dynamically filter the dashboard by:

* Gender
* Department
* Job Role
* Education Field

This enables focused analysis across different employee segments.

---

### Page Navigation

Custom page navigation buttons were implemented to allow seamless movement between dashboard pages:

* Workforce Overview
* Attrition Analysis
* Attrition Drivers & Insights

This improves dashboard usability and storytelling flow.

---

### Bookmark Configuration

Bookmarks were configured to support dashboard interactions and improve user experience.

#### Implemented Bookmark Features:

* Refresh button functionality
* Resetting slicers to the default state
* Navigation consistency across pages

---

### KPI Cards

Dynamic KPI cards were used to display:

* Total Headcount
* Attrition Count
* Attrition Rate
* Average Age
* Average Tenure

These provide quick executive-level insights at a glance.

---

### Responsive Visual Storytelling

The dashboard combines:

* Bar charts for comparison analysis
* Donut charts for distribution insights
* Trend visuals for attrition patterns

This ensures insights are communicated clearly and effectively.

---

## Tools & Technologies

* **Power BI** – Data modeling & dashboard development
* **Power Query** – Data cleaning & transformation
* **DAX (Data Analysis Expressions)** – Measures and calculations
* **Figma** – Dashboard wireframing and layout design
* DAX Studio

---

## Explore The Full View Of The Dashboard
<img width="967" height="546" alt="Page 1" src="https://github.com/user-attachments/assets/21bd36a0-9064-4baa-be12-b08b0f913e5b" />

<img width="967" height="544" alt="Page 2" src="https://github.com/user-attachments/assets/0c12bdf2-e0ff-4810-8973-5841aa0c632e" />

<img width="967" height="545" alt="Page 3" src="https://github.com/user-attachments/assets/b04e426c-9026-46f5-8a3b-236243ed2fbc" />

---

## Future Improvements

* Implement predictive attrition modeling (Machine Learning)
* Add employee segmentation clustering
* Integrate real-time HR data pipelines
* Enhance dashboard with drill-through analysis

---

## Conclusion

This project demonstrates a complete HR analytics workflow, combining:

* Data cleaning and transformation
* Dimensional modeling
* DAX calculations
* Interactive dashboard development
* Business insight generation

The dashboard provides actionable insights that support:

* Data-driven HR strategies
* Employee retention improvement
* Workforce optimization
* Better organizational decision-making

This project also demonstrates the ability to:

* Transform raw data into structured analytical models
* Build scalable star schema, data models
* Design interactive dashboards with business impact
* Implement advanced dashboard features such as:

  * Page navigation
  * Bookmark configuration
  * Dynamic filtering and interactivity
* Deliver actionable insights, not just visualizations
* Apply end-to-end analytics workflow from raw data to executive-level reporting

Overall, the project reflects strong analytical thinking, business understanding, and technical proficiency in Power BI and data analytics.

---

## Author
Ibrahim Abdulrasaq | Data & BI Analyst

---

## Let’s Connect

If you found this project insightful or want to collaborate:

🔗 [Email](mailto:ibrahimabdulrasaqademola2017@gmail.com)

🔗 [LinkedIn](https://www.linkedin.com/in/ibrahim-abdulrasaq/)

🔗 [Github](https://github.com/ibrahimabdulrasaq)
