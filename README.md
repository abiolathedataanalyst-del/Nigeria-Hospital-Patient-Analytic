# 🏥 Nigeria Hospital Patient Analytic Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Healthcare%20Analytics-blue?style=for-the-badge)

---

## 📌 Project Overview

This project is a **multi-page, interactive Power BI dashboard** designed to provide end-to-end analytical visibility into hospital operations, patient outcomes, clinical insights, and financial performance across a Nigerian healthcare setting.

The dashboard consolidates data from **60,000 patient records** spanning **2021–2025**, enabling hospital executives, clinical directors, and operations managers to make data-driven decisions that improve care quality, reduce costs, and optimise resource utilisation.

The analysis covers five thematic areas: Executive Overview, Clinical Insights, Financial Analysis, Hospital Operations, and Strategic Insights — each addressable through a dedicated dashboard page with interactive slicers and drill-through capability.

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard design, data modelling, DAX measures, interactive visualisations |
| **Microsoft Excel** | Data preparation, initial cleaning, and source data structuring |
| **DAX (Data Analysis Expressions)** | KPI calculations, YoY variance measures, conditional logic |
| **Power Query (M Language)** | ETL — data transformation and shaping within Power BI |

---

## ❓ Key Business Questions

The dashboard was designed to answer the following critical business questions:

1. **How has patient volume and treatment cost trended year-over-year?**
2. **Which departments handle the highest patient loads, and are resources distributed equitably?**
3. **What are the most prevalent diagnoses, and how do they compare in cost and outcome?**
4. **Which patient demographics (age, gender, smoking status, exercise level) are most at risk?**
5. **What is the hospital's readmission rate, and which diagnoses drive it highest?**
6. **How does insurance type affect patient distribution and financial exposure?**
7. **What is the average length of stay per diagnosis, and where can it be reduced?**
8. **What proportion of patients require follow-up care, and how does this impact operational capacity?**
9. **How are patient outcomes (recovered, improved, under treatment, deceased, referred) distributed?**
10. **What is the relationship between BMI and patient volume across clinical departments?**

---

## 📊 Dashboard Overview

The dashboard is structured across **five interactive pages**, each serving a distinct analytical audience.

---

### Page 1 — Executive Overview: Hospital Performance

> **Audience:** C-Suite, Hospital Directors, Board Members

**KPI Cards (Top Row):**
- 👥 **Total Patients:** 60,000 ▲ 26.5% YoY
- 💰 **Treatment Cost:** ₦458.8M ▲ 26.3% YoY
- 🔄 **Readmission Rate:** 49.79% ▲ 0.03% YoY
- ⚠️ **Mortality Rate:** 20.1% ▼ -0.3% YoY
- 🛏️ **Average Length of Stay:** 10.48 days

**Visualisations:**
- **Total Patients by Department** — Horizontal bar chart showing near-equal distribution across 8 departments (Nephrology and General Medicine leading at 7.6K each)
- **Total Patients by Year** — Year-on-year volume trend (2021–2025), showing consistent throughput of ~14.6K annually
- **Total Patients by Diagnosis** — Donut chart revealing a balanced spread across 11 diagnoses (Hypertension and Diabetes leading at ~10.2%)
- **Outcome Distribution** — Pie chart segmented into five outcomes: Under Treatment (20.07%), Deceased (20.05%), Referred (20.03%), Recovered (19.94%), Improved (19.91%)

**Filters:** Insurance Type | Gender | Year Slider | Department | Diagnosis

---

### Page 2 — Clinical Insights

> **Audience:** Chief Medical Officers, Clinical Directors, Epidemiologists

**Visualisations:**
- **Total Patients by Age Group** — Column chart showing patients aged 41–60 as the largest cohort (16.6K), followed by 61–80 (16.3K) and 21–40 (16.3K); patients aged 80+ represent 8.2K and 0–20 only 2.6K
- **Total Patients by Diagnosis and Smoking Status** — 100% stacked bar chart showing near-equal smoker/non-smoker split across all diagnoses; Cancer slightly skews toward smokers (50.66%)
- **Average Blood Pressure by Department** — Segmented bar chart revealing uniformly high average BP (~140–141 mmHg) across all departments, flagging a systemic hypertension concern
- **Total Patients and Sum of BMI** — Dual-axis chart indicating that the sum of BMI accounts for 96.77% of the comparative metric, highlighting BMI as a significant clinical risk factor

**Filters:** Smoking Status | Diagnosis | Exercise Level | Gender | Age Group

---

### Page 3 — Financial Analysis

> **Audience:** CFO, Finance Managers, Insurance & Billing Teams

**KPI Cards (Top Row):**
- 💼 **Total Cost KPI:** ₦550.4M ▲ 26.4% YoY
- 💊 **Medication Cost KPI:** ₦91.6M ▲ 26.5% YoY
- 🏥 **Treatment Cost:** ₦458.8M ▲ 26.3% YoY

**Visualisations:**
- **Sum of Treatment Cost by Department** — Nephrology and Cardiology are the costliest departments (₦58M each), followed closely by Neurology and General Medicine
- **Total Patients by Insurance Type** — Donut chart showing near-equal split: Private (25.28%), Government (25.06%), None (24.92%), Employer (24.74%) — indicating minimal insurance concentration risk
- **Average Cost Per Patient by Diagnosis** — Pneumonia, Hypertension, COVID-19, and Heart Disease have the highest average cost per patient (~₦9.2K), while Asthma and Diabetes are slightly lower (~₦9.1K)

**Filters:** Insurance Type | Year Slider | Department | Diagnosis

---

### Page 4 — Hospital Operations

> **Audience:** Operations Managers, Heads of Department, Quality Assurance Teams

**Visualisations:**
- **Readmission Rate by Diagnosis** — Pneumonia leads with a 50.77% readmission rate, followed by Stroke (50.45%) and Asthma (50.16%); Cancer has the lowest at 49.02%
- **Average Length of Stay by Diagnosis** — Hypertension patients have the longest stay (10.6 days); Asthma, Heart Disease, and Stroke the shortest (10.4 days); overall range is narrow (10.4–10.6)
- **Total Patients by Follow-up Required** — Near-equal split: 50.1% (30.1K) do NOT require follow-up vs. 49.9% (29.9K) who do — indicating a high ongoing care burden

**Filters:** Readmission 30 Days | Follow-up Required | Year Slider | Department | Diagnosis

---

## 💡 Key Insights

### 🔵 Patient Volume & Growth
- Patient volume grew by **26.5% YoY** to 60,000, reflecting strong hospital utilisation or catchment area expansion.
- Volume has been **consistent across 2021–2024** (~14.5K–14.7K annually), with 2025 showing a partial-year figure of 1.7K.

### 🔵 Departmental Load
- All departments carry **near-equal patient loads** (7.4K–7.6K), suggesting effective load balancing — but also leaving no department with clear capacity headroom if volumes spike.

### 🔵 Diagnosis Distribution
- All 11 diagnoses account for **roughly 10% each** of total patients, suggesting no single condition dominates, but Hypertension and Diabetes consistently incur the highest costs.

### 🔵 Clinical Risk Profile
- The **41–60 age group** is the most represented, pointing to a predominantly middle-aged patient population with chronic disease risk.
- Average BP across all departments is **~140 mmHg**, which is at the threshold of Stage 2 Hypertension — a systemic concern.
- Smoking status is **evenly split across all diagnoses** (~50/50), suggesting smoking is not a primary differentiator in this cohort, though Cancer and Stroke lean marginally toward smokers.

### 🔵 Financial Performance
- Total hospital costs reached **₦550.4M**, up 26.4% YoY, with treatment costs forming the bulk (₦458.8M) vs. medication (₦91.6M).
- Cost per patient is **nearly uniform across diagnoses** (~₦9.1K–₦9.2K), indicating standardised treatment protocols — but Pneumonia and Hypertension slightly tip the scale.
- Insurance coverage is **evenly distributed** across four types (~25% each), reducing dependency risk but also limiting negotiation leverage with any single insurer.

### 🔵 Operational Concerns
- A **49.79% readmission rate** is critically high — nearly 1 in 2 patients is readmitted within 30 days, with Pneumonia (50.77%) and Stroke (50.45%) as the worst performers.
- **49.9% of patients require follow-up care**, placing enormous pressure on outpatient departments and scheduling capacity.
- Average length of stay at **10.48 days** is relatively long across all diagnoses, presenting an opportunity for discharge optimisation.

### 🔵 Patient Outcomes
- Outcomes are **uniformly distributed** across all five categories (~20% each: Under Treatment, Deceased, Referred, Recovered, Improved).
- A **20.1% mortality rate** — though declining 0.3% YoY — remains a significant concern requiring clinical quality intervention.

---

## 🎯 Strategic Recommendations

### 1. 🏥 Urgent Readmission Reduction Programme
With a near-50% readmission rate, particularly for Pneumonia and Stroke patients, the hospital should implement **structured discharge protocols**, post-discharge monitoring, and a **30-day care transition programme** to reduce avoidable readmissions and the associated cost burden.

### 2. 💊 Chronic Disease Management Clinics
Given the high volume and cost of Hypertension, Diabetes, and Heart Disease — and the fact that the 41–60 age group is the dominant cohort — the hospital should establish **dedicated chronic disease management units** with preventive care pathways to reduce acute admissions.

### 3. 🩺 Blood Pressure & Hypertension Screening Initiative
With average BP across all departments sitting at ~140–141 mmHg, a **hospital-wide hypertension screening and management protocol** should be introduced for all patients regardless of their primary diagnosis, to prevent escalation and reduce stroke and kidney disease risk.

### 4. 💰 Cost Optimisation in High-Cost Departments
Nephrology and Cardiology each incur ₦58M in treatment costs. A **cost-efficiency review** of treatment pathways, medication substitution opportunities, and length-of-stay reduction in these departments could yield meaningful savings.

### 5. 📋 Follow-Up Care Capacity Planning
With ~30,000 patients requiring follow-up, the hospital must **invest in outpatient capacity** — including telemedicine options, appointment scheduling systems, and community health partnerships — to avoid care bottlenecks and prevent readmissions.

### 6. 🚭 Targeted Cancer & Stroke Smoking Cessation
Although the overall smoking split is ~50/50, Cancer and Stroke skew slightly toward smokers. A **targeted smoking cessation programme** for at-risk patients in Oncology and Neurology departments could improve long-term outcomes and reduce readmission risk.

### 7. 📉 Mortality Rate Improvement Plan
A 20.1% mortality rate — even with a slight YoY decline — warrants a formal **clinical quality improvement initiative**, including regular mortality and morbidity reviews, early warning scoring systems, and critical care pathway audits.

### 8. 🏦 Insurance Revenue Diversification & Negotiations
The balanced insurance mix (~25% each) is positive for risk distribution, but the hospital should leverage this volume to **negotiate better reimbursement rates** with private and employer insurers and explore **bulk government health scheme enrolment** for the "None" insurance segment (24.92%).

---

## ✅ Conclusion

The **Nigeria Hospital Patient Analytic Dashboard** delivers a comprehensive, multi-dimensional view of hospital performance that goes far beyond surface-level reporting. By combining clinical, financial, and operational data into a unified Power BI solution, this project enables hospital leadership to move from reactive management to **proactive, data-led decision-making**.

The analysis reveals a hospital that is **growing strongly** (60K patients, ₦550M in costs, +26% YoY) but facing critical structural challenges: a persistently high readmission rate, a substantial follow-up care burden, elevated average blood pressure across all departments, and a mortality rate that requires urgent quality intervention.

Addressing these challenges through the strategic recommendations outlined above will help the hospital reduce unnecessary costs, improve patient outcomes, increase operational efficiency, and ultimately strengthen its position as a leading healthcare provider in Nigeria.

---

## 👤 Author

**Aminu Abiola Friday**
Operations Analyst | Data Analytics & Business Intelligence Specialist

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com)
[![Power BI Portfolio](https://img.shields.io/badge/Power%20BI-View%20Dashboard-F2C811?style=flat&logo=powerbi&logoColor=black)](https://app.powerbi.com)

---

*This project was developed as part of a healthcare analytics portfolio, demonstrating applied skills in Power BI, DAX, data modelling, and business intelligence storytelling.*
