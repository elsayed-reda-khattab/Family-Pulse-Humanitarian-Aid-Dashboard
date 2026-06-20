# Family Pulse - Humanitarian Aid & Impact Dashboard
!<img width="600" height="497" alt="Family Pulse Dashboard" src="https://github.com/user-attachments/assets/fef606c7-ae13-4e9a-a3a2-14b16630775e" />

## 📌 Project Overview
The **Family Pulse Dashboard** is a comprehensive Business Intelligence solution built using **Power BI**. It is designed to analyze and track humanitarian aid distribution, demographic needs, and financial support across multiple conflict-affected countries (**Syria, Yemen, Iraq, and Libya**). 

The primary goal of this project is to provide actionable insights into family demographics, income status, regional distribution, and specific urgent needs (such as housing types like tents and support for non-working mothers) to optimize aid delivery.

---

## 📊 Key Insights & Metrics (KPIs)
* **Total Beneficiaries (Members):** 11,905 individuals supported.
* **Total Funds Managed:** $58,385 distributed across registered families.
* **Total Families Supported:** 1,701 families.
* **Average Income/Support per Family:** $85.61.

---

## 🔍 Deep-Dive Analytics & Visualizations

### 1. Demographic & Household Insights
* **Gender Distribution:** The dataset reveals a balanced demographic split with **54.68% Male** and **45.32% Female** beneficiaries.
* **Shelter Vulnerability (Tent by Country):** Analyzes the distribution of families living in temporary shelters (tents). **Syria** records the highest number with **138 families**, closely followed by **Yemen** with **120 families**.

### 2. High-Risk Group Target Analysis
* **Mother and Non-Working (By Country):** A critical component of the dashboard that highlights vulnerable female-headed households where the mother is unemployed. 
  * **Syria:** 133 families
  * **Yemen:** 106 families
  * **Iraq:** 58 families
  * **Libya:** 45 families

### 3. Geographical Distribution
* **Families & Cities Distribution:** * **Syria** and **Yemen** represent the largest areas of support, with **647** and **606** families respectively.
  * The dashboard tracks metrics across a designated number of cities per country (Yemen: 6, Syria: 5, Iraq: 4, Libya: 4).

---

## 🛠️ Tech Stack & Data Architecture

* **Tool:** Power BI Desktop
* **Data Model:** Structured utilizing a relational schema connecting **4 core tables**:
  1. `Needs Table` (Core facts regarding aid types like food, clothes, cash, education, and housing)
  2. `Family Info` (Demographics, household sizes, and employment status)
  3. `City Info` (Regional tracking)
  4. `Country Info` (High-level geographical mapping)
* **DAX & Power Query:** Used for data cleaning, structural normalization, and calculating dynamic measures (Average Income, Total Members, Filter-responsive KPIs).

---

## 🚀 How to Use the Dashboard
1. Use the **House Type** and **Country** slicers at the top right to filter the entire report dynamically.
2. Cross-filter by clicking on specific country bars in the **Families by Country** chart to see localized demographic and shelter insights instantly.
