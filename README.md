# AxionRay Assignment – Task 1: Data Tagging & Classification

This repository contains my completed solution for **Task 1** of the AxionRay Data Analyst assignment.  
The objective of this task was to tag free-text complaint data into structured categories using a strict, predefined taxonomy.

---

## 📌 Task Description

The dataset included:
- Complaint descriptions  
- Causes  
- Corrective actions  
- A taxonomy file with allowed labels  

The goal of Task 1 was to classify each record into:
- **Root Cause**
- **Symptom Condition(s)**
- **Symptom Component(s)**
- **Fix Condition(s)**
- **Fix Component(s)**

All tags were required to be selected **exclusively from the provided taxonomy**, with no new terms introduced.

---

## 🧠 Approach

- Carefully read each complaint, cause, and correction to understand the issue.
- Used **data validation drop-down lists** in Excel to ensure:
  - Only taxonomy-approved terms were selected  
  - No new labels or typos were introduced  
  - Consistency in classification
- Applied **closest-match mapping** when the text didn’t exactly align with a taxonomy term.
- Used **“Not Mentioned”** when a component didn’t exist in the taxonomy list.
- Filled all required columns, including secondary and tertiary conditions/fixes where applicable.

---

## 📊 Deliverables

### Files included:
- **Tagged_Task1.xlsx** — Fully tagged dataset  
- **Summary_Report.md / .pdf** — Explanation of approach + insights  
- Any supporting files that were provided in the assignment  

---

## 🔍 Key Insights from the Data

- Many issues were caused by **assembly inconsistencies** (e.g., loose fittings, missing components).
- **Leak-related failures** (oil, hydraulic, product) were common across multiple records.
- Several failures were **sensor-related**, often due to contamination or misalignment.
- These problems point toward opportunities for stronger **quality checks**, better **installation procedures**, and improved **pre-delivery inspections**.

---

## 🛠 Tools Used

- Microsoft Excel  
- Data Validation  
- Manual tagging based on taxonomy interpretation  

---

## 📝 Task 2 (to be added later)

This repository will be updated with Task 2 once completed.

---

## 📬 Contact

Feel free to reach out if you need additional information about this submission.
