# 📊 HR & Training Performance Analytics Dashboard

## 📌 Project Overview
This project presents an end-to-end data analytics solution using Microsoft Excel, covering raw data cleaning, performance KPI engineering, dynamic data aggregation, and an interactive executive dashboard. The dashboard provides deep insights into employee training outcomes, financial investments in learning & development, workforce satisfaction metrics, and departmental distributions.

---

## 🧹 Data Cleaning & Preparation Pipeline
The raw dataset contained unformatted columns, raw dates, missing values, and unstructured text. The dataset was transformed into a clean, structured layout using systematic data sanitization techniques.

### 1. Messy Dataset (Raw Input)
![Messy HR Dataset](https://github.com/mbilalb181/Hr-Analytics-Performance-Dashboard./blob/main/Screenshot%20of%20Messy%20Data.png)

### 2. Cleaned Dataset with Conditional Formatting
![Clean HR Dataset](https://github.com/mbilalb181/Hr-Analytics-Performance-Dashboard./blob/main/Screenshot%20of%20Clean%20Data.png)

**Key Cleaning & Formatting Steps:**
- **Standardization & Structure:** Unified job titles, dates, pay zones, and department names across all employee records.
- **Conditional Formatting Rules:**
  - Data bars and visual indicators applied to **Current Employee Rating** and **Performance Score**.
  - Color scale formatting applied to **Engagement Score** and **Satisfaction Score**.
  - Highlight rules implemented for **Training Duration (Days)** and **Training Outcome Status**.

---

## 🖥️ Executive Interactive Dashboard
![HR Analytics Dashboard](https://github.com/mbilalb181/Hr-Analytics-Performance-Dashboard./blob/main/Screenshot%20of%20Dashboard.png)

---

## 📈 Key Performance Indicators (KPIs)
A dedicated summary layer calculates key organizational metrics for quick executive assessment:

| KPI Metric | Value / Figure | Description |
| :--- | :--- | :--- |
| **Average Engagement Score** | `2.9` | Average engagement rating across active employees |
| **Average Satisfaction Score** | `3.0` | Overall workforce satisfaction level |
| **Average Training Cost** | `PKR 561` | Average cost invested per employee training |
| **Sum of Training Cost** | `Rs 1,765,656` | Total budget spent on internal & external training |
| **Average Current Employee Rating** | `3.0` | Mean performance score of the workforce |

---

## 📉 Dashboard Visualizations Breakdown
The interactive dashboard features **7 distinct chart types**, each engineered to answer specific HR questions:

1. **Donut Chart — Training Outcome Status**
   - **Rows/Category:** Training Outcome (*Passed, Completed, Failed, Incomplete*)
   - **Values:** Count of `Employee ID`
   - **Insight:** High-level distribution of course completion status (`812` Incomplete, `801` Passed, `786` Completed, `751` Failed).

2. **Clustered Column Chart — Training Cost by Department**
   - **Rows/Category:** Department Type (*Production, IT/IS, Sales, Software Engineering, Admin Offices, Executive Office*)
   - **Values:** Sum of `Training Cost`
   - **Insight:** Production department holds the highest training expenditure (`Rs 1,187,440`).

3. **Clustered Bar Chart — Employees by Course**
   - **Rows/Category:** Training Program Name (*Communication Skills, Project Management, Technical Skills, Customer Service, Leadership Development*)
   - **Values:** Count of `Employee ID`
   - **Insight:** Tracks total enrollments per course (*Communication Skills leading with 705 employees*).

4. **3D Pie Chart — Internal vs External Training Cost**
   - **Rows/Category:** Training Type (*Internal vs. External*)
   - **Values:** Sum of `Training Cost`
   - **Insight:** Financial split between internal programs (`Rs 890,638`) and external vendors (`Rs 875,019`).

5. **Stacked Bar Chart — Training Outcome by Marital Status**
   - **Rows/Category:** Marital Description (*Divorced, Married, Single, Widowed*)
   - **Values:** Count of `Employee ID` broken down by Training Outcome.
   - **Insight:** Analyzes course completion trends across demographic segments.

6. **Line Chart — Employee Satisfaction Score Trend**
   - **Rows/Category:** Satisfaction Score ratings (`1` to `5`)
   - **Values:** Count of `Employee ID`
   - **Insight:** Distribution of satisfaction scores across staff (*673 employees rated score 4*).

7. **Area Chart — Employee Distribution by Pay Zone**
   - **Rows/Category:** Pay Zone (`Zone A`, `Zone B`, `Zone C`) across timeline years.
   - **Values:** Count of `Employee ID`
   - **Insight:** Visualizes employee volume trends over time across compensation tiers.

---

## 🎛️ Interactive Filters & UI Design
- **4 Connected Global Slicers:**
  - 🏢 **Business Unit** (*BPC, CCDR, EW, MSC, NEL, PL, PYZ, SVG, TNS, WBL*)
  - 📂 **Department Type** (*Admin Offices, Executive Office, IT/IS, Production, Sales, Software Engineering*)
  - 💳 **Pay Zone** (*Zone A, Zone B, Zone C*)
  - 🎓 **Training Outcome** (*Completed, Failed, Incomplete, Passed*)

- **Dashboard UI & Formatting Highlights:**
  - Modern, dark-themed header title section ("HR ANALYTICS TEAM DASHBOARD").
  - Card layouts with muted, rounded-corner containers for chart panels.
  - Transparent chart backgrounds and custom data labels for high visual clarity.

---

## 🛠️ Tools & Technologies
- **Microsoft Excel:** Data Cleaning, Formulas, Conditional Formatting, Pivot Tables, Data Viz & Dashboarding
- **Version Control:** Git & GitHub

---

## 📁 File & Worksheet Structure
```text
HR & TRAINING PERFORMANCE DASHBOARD.xlsx
├── Messy_HR_Dataset_Detailed      # Original raw dataset
├── Clean-HR-Dataset-Detailed      # Cleaned data with conditional formatting
├── KPI-Scorecard                  # KPI summary metrics
├── Training Outcome Status        # Pivot table for outcomes
├── Training Cost by Department   # Departmental cost aggregation
├── Employees by Course            # Course enrollment breakdowns
├── Internal vs External Training  # Cost split analysis
└── HR Analytics Dashboard         # Interactive executive dashboard
```
---

## 🚀 How to Run & View
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/hr-analytics-dashboard.git](https://github.com/your-username/hr-analytics-dashboard.git)
   ## 👏 Thank You for Visiting!
---
Thank you so much for taking the time to explore this project! 🌟

If you found this dashboard insightful or helpful for your own work:

- ⭐ **Leave a Star:** Please consider starring this repository to show your support!
- 🔔 **Follow for More:** Follow my profile to stay updated on future data analytics, data cleaning, and business intelligence projects.

Happy Analyzing! 🚀
