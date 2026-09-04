# 🏥 Hospital Emergency Room (ER) Operations & Patient Flow Analysis

An interactive Excel Data Analytics project analyzing Emergency Room patient visits, wait times, satisfaction scores, and referral distributions across 2023–2024. Designed to help healthcare managers identify operational bottlenecks and improve patient experience.

---

## 📌 Executive Summary & Key Results (STAR)

* **Situation:** Emergency Room operations faced high wait times and fluctuating patient satisfaction scores across peak months.
* **Task:** Analyze multi-year operational data to uncover factors driving long wait times, track patient admission rates, and profile demographic referral patterns.
* **Action:** Built a dynamic, multi-page Excel dashboard utilizing Pivot Tables, dynamic Slicers, KPI cards, and custom chart formatting to segment metrics by year, month, and department.
* **Result:** Uncovered that **52% of ER visits result in admissions** and identified **General Practice (103 cases)** and **Orthopedics (65 cases)** as the primary referral sources driving volume.

---

## 🖼️ Dashboard Preview

![Hospital ER Dashboard](screenshots/dashboard_preview.png)

---

## 📊 Key Analytical Insights

* **Patient Volume:** Total patient traffic recorded at **513 visits**.
* **Wait Time Performance:** Average ER wait time stood at **36.32 minutes**.
* **Patient Satisfaction:** Overall average score achieved was **5.15 / 10**.
* **Admission Status:** **52% Admitted (269)** vs. **48% Not Admitted (244)**.
* **Demographic Breakdown:** 
  * **Gender:** 53% Male (272) vs. 47% Female (241).
  * **Age Bracket:** Highest ER volume occurs in the **0–9 age group (76 patients)**, followed by **60–69 (67 patients)**.
* **Department Referrals:** **General Practice** represents the highest volume of referrals (103 patients), followed by **Orthopedics** (65).

---

## 🛠️ Tech Stack & Excel Capabilities Used

* **Data Analysis & Processing:** `XLOOKUP`, `INDEX-MATCH`, `SUMIFS`, `COUNTIFS`, Data Cleaning, Handling Nulls.
* **Summarization:** Dynamic Pivot Tables & Pivot Charts.
* **Dashboard Design:** Customized Slicers (Year, Month), Conditional Formatting, Custom KPI Cards, Progress Bar Indicators, Sparklines.

---

## 📂 Project Repository Structure

```text
Hospital-Emergency-Room-Dashboard/
│── data/
│   └── raw_hospital_data.xlsx
│── dashboard/
│   └── Hospital_ER_Dashboard.xlsx
│── screenshots/
│   └── dashboard_preview.png
└── README.md
