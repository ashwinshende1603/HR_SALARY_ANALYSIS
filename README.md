# 🚀 Strategic HR Salary & Compensation Analytics Dashboard

![Compensation-Decisions-The-Power-of-HR-Analytics](https://github.com/user-attachments/assets/bc61ee72-373c-478e-9d47-718ab3352c58)

## ✨ Project Overview

This Power BI dashboard provides a **comprehensive, data-driven framework** for analyzing organizational compensation structure, ensuring pay equity, and validating the "pay-for-performance" model. Built on the `HR_Salary_Analysis_Cleaned_650rows.xlsx` dataset, it transforms raw compensation data into actionable intelligence for HR leaders, finance partners, and department managers.

Our objective is to move beyond simple averages to conduct strategic audits that support fair, competitive, and fiscally responsible compensation decisions.

---

## 🎯 Key Value Proposition

The dashboard is structured around four critical areas of compensation management, answering the most vital strategic HR questions:

| Focus Area | Key Questions Answered | Key Visuals |
| :--- | :--- | :--- |
| **Budget & Spend** | What is our total compensation expenditure? Where is the pay distributed across the organization? | Total Compensation KPIs, Salary Distribution (Clustered Column Chart), Treemap for Departmental Spend. |
| **Pay Equity** | Do pay gaps exist across genders or education levels? Are our pay structures fair across employment types? | Gender Pay Gap %, Average Salary by Gender, Education vs. Compensation Chart. |
| **Performance Alignment** | Are we rewarding our top talent appropriately? Is our bonus structure effective? | Average Salary by Performance Rating, Line/Column Chart comparing Salary vs. Bonus by Rating. |
| **Operational Deep Dive** | What is the specific pay range for an Analyst in IT? How does pay progression look in the Sales department? | Drill-down Pay Hierarchy, Filtered Scatter Plot of Experience vs. Salary, Pay Band Table. |

---

## 💡 Key Analytical Insights

By interacting with this dashboard, users can immediately surface critical findings related to compensation health and fairness:

* **Gender Pay Gap:** Quantify the exact percentage difference between average Male and Female salaries, highlighting the specific departments that contribute most to this gap (Page 2).
* **Performance Reward Validation:** Confirm that the average **Salary and Bonus payout for 'Excellent' performers** is statistically higher than 'Average' or 'Poor' performers, validating the efficacy of the pay-for-performance policy (Page 3).
* **Compensation Structure Audit:** Identify the precise **Minimum and Maximum salary bands** for every `Designation` (e.g., Intern, Analyst, Manager) across the organization, ensuring internal pay equity is maintained (Page 4).
* **Experience vs. Pay:** Detect potential retention risks by identifying experienced employees (e.g., 10+ years) whose compensation falls significantly below the organizational trend line shown on the **Salary vs. Experience Scatter Plot** (Page 1).
* **Variable Pay Dependence:** Determine which departments (e.g., Sales vs. IT) rely more heavily on **Variable Pay (Bonus)** versus **Fixed Pay (Salary)**, informing budget forecasts and sales incentive design (Page 4).

---

## 📂 Dashboard Structure & Navigation

The Power BI file is logically segmented into four distinct reporting pages:

### 1. Compensation & Budget Overview 💰
Focuses on the macro view: total cost, average pay, and how spending is allocated by department and location.

<img width="800" height="500" alt="DASHBOARD 1" src="https://github.com/user-attachments/assets/bc3576ee-c3d9-4b34-a063-6ca9394cac27" />

### 2. Pay Equity & Fairness Analysis ⚖️
Dedicated to checking for structural pay biases based on protected characteristics like **Gender** and educational attainment.

<img width="800" height="500" alt="DASHBOARD 2" src="https://github.com/user-attachments/assets/e2ea4457-edbc-408e-96eb-94803a6bb1bf" />

### 3. Performance & Retention Audit 📈
Examines the link between **Performance Rating**, compensation, and employee experience to ensure high performers are incentivized and retained.

<img width="800" height="500" alt="DASHBOARD 3" src="https://github.com/user-attachments/assets/5c59436e-d4d6-4b5c-b93b-6fd0b9b96d8e" />

### 4. Operational Deep Dive 🔎
Provides managers with granular, interactive views of pay progression and salary bands within their specific **Department** and **Designation** levels.

<img width="800" height="500" alt="DASHBOARD 4" src="https://github.com/user-attachments/assets/0a861c17-919a-43ef-b33a-21ceb04e50ff" />

---

## 🛠️ Setup & Usage Instructions

This project is delivered as a **Power BI Template (`.pbit`)** for easy setup and scalability.

### Prerequisites
* Microsoft Power BI Desktop (Latest Version)
* The raw data file: `HR_Salary_Analysis_Cleaned_650rows.xlsx - Sheet1.csv`

### How to Run the Dashboard

1.  **Download:** Download the `HR Salary dashboard.pbit` template file and the data file.
2.  **Open Template:** Double-click the `HR Salary dashboard.pbit` file. Power BI will open and prompt you for the data source.
3.  **Load Data:** You will be prompted to select the location of the **CSV data file**. Navigate to and select the `HR_Salary_Analysis_Cleaned_650rows.xlsx - Sheet1.csv` file.
4.  **Transform & Load:** Power BI will automatically load the data, apply the necessary transformations, and populate all the DAX measures and visualizations.
5.  **Analyze!** Start your strategic analysis from the **Compensation & Budget Overview** page.

### Data Refresh

To update the dashboard with new data (e.g., next quarter's payroll run):
1.  Replace the existing `HR_Salary_Analysis_Cleaned_650rows.xlsx - Sheet1.csv` file with the updated data (must maintain the same columns and name).
2.  In Power BI Desktop, navigate to the **Home** tab and click **Refresh**.

---

## 🔗 Data Fields Used

The analysis is based on the following key fields from the source data:

* `Salary` (Numerical)
* `Bonus` (Numerical)
* `Total Compensation` (Calculated: Salary + Bonus)
* `Department` (Categorical)
* `Designation` (Categorical)
* `Gender` (Categorical)
* `Performance Rating` (Categorical)
* `Experience (Years)` (Numerical)

---
