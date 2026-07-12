# HR Analytics Dashboard — Power BI Portfolio Project

## 📌 Overview
An interactive HR Analytics dashboard built in Power BI that transforms raw employee data into actionable workforce insights. The project covers the full workflow — data import, cleaning with Power Query, KPI design, DAX measures, and interactive visuals — to help HR teams understand attrition, salary distribution, job satisfaction, and department performance at a glance.

---

## 🛠️ Tools Used
* **Power BI Desktop:** Used for data modeling, DAX formulation, and interactive dashboard design.
* **Power Query:** Utilized for advanced data cleaning, shaping, and transforming raw records.
* **DAX (Data Analysis Expressions):** Wrote custom measures (e.g., Attrition Rate %) to build dynamic calculations.

---

## 💾 Dataset
The project utilizes a raw HR employee dataset covering:
* Demographics & Gender
* Department & Job Roles
* Salary Slabs (LPA)
* Job Satisfaction levels
* Attrition Status
* Age & Years of Experience

---

## 🔄 Process

1. **Import Data:** Loaded the raw HR dataset into Power BI Desktop.
2. **Clean & Transform (Power Query):** 
   * Removed null values.
   * Eliminated duplicate records.
   * Fixed inconsistent text formatting (e.g., matching department naming and letter casing).
3. **KPI Cards:** Built headline metric cards summarizing the workforce at a glance (Total Employees, Attrition Rate, Average Salary, Average Job Satisfaction).
4. **DAX Measures:** Created custom calculations, including an accurate `Attrition Rate %` measure, to power the KPI cards and visual filters.
5. **Chart Visuals:** Designed explicit breakdowns to analyze:
   * Attrition patterns and trends
   * Salary distribution across layers
   * Departmental performance metrics
   * Gender metrics and ratios
   * Age group distribution ranges
   * Experience-based attrition insights
6. **Slicers:** Added interactive filtering pane tools (Department, Gender, Age Group) so users can explore dashboard data segments dynamically.
7. **Final Dashboard:** Assembled all active visuals, KPI components, and interactive slicers into one polished, professional canvas layout.

---

## 📊 Key Findings

* **Overall Attrition:** Out of 44 total employees (36 active), 8 have left the company — resulting in an attrition rate of 18.2%. The average employee age is 57.7, with an average of 8.86 years of experience.
* **Department Size:** Operations is by far the largest department at 29 employees (~66% of the workforce), followed by Sales (9), with HR and IT tied as the smallest departments (3 each).
* **Gender Gap in Attrition:** Of the 8 employees who left, 62.5% were women (5) vs 37.5% men (3) — indicating women are leaving at a disproportionately higher rate relative to typical workforce composition.
* **Salary vs. Attrition:** Attrition is heavily concentrated in the mid-salary slabs (3–6 LPA and 6–10 LPA) rather than the lowest (0–3 LPA) or highest (10+ LPA) earners, suggesting retention issues are strongest in the middle of the pay scale.
* **Job Role Attrition:** Laboratory Technicians have the highest attrition among specific roles (3 departures), split across satisfaction levels 2 and 3. Healthcare Representatives, Manufacturing Directors, Research Directors, and Research Scientists each show 1–2 departures.
* **Experience-Based Risk:** Attrition spikes sharply at very low experience (early-career hires) and again around ~20 years of experience, pointing to two distinct risk periods — new employee onboarding and long-tenured staff retention — rather than a steady attrition rate over tenure.

---

## 🖼️ Dashboard Preview

<div align="center">
  <!-- If uploading an MP4 screen recording using the GitHub Issues trick, paste your generated link inside the src="" quotes below -->
  <video src="PASTE_YOUR_POWERBI_VIDEO_URL_HERE" width="100%" controls></video>
</div>
