
# UIDAI Data Hackathon 2026  
## Teeka Niyojan: Aadhaar-Guided Vaccination Planning

---

## 🧩 Problem Statement

**How can we address the vaccination gap and assist the Union Government in planning and prioritizing vaccination camps, mobilizing volunteers, and allocating clinical support by identifying “invisible” infants?**

Some infants remain under-identified due to access, awareness, or infrastructural constraints. Absolute enrolment numbers alone do not reveal these hidden gaps.

---

## 💡 Approach

We use **Aadhaar enrolment data as a proxy for child presence** and apply normalization to identify regions where infants likely exist but are under-served.  
To strengthen context and interpretation, **publicly available external datasets were also referenced** for demographic and health-related signals.

The approach combines:
- Child enrolment patterns (0–5 age group)
- Demographic consistency checks  
- Biometric quality indicators as an accessibility proxy  

---

## 📊 Data & Methodology

- **Primary Data:** UIDAI Aadhaar Enrolment, Demographic, and Biometric datasets  
- **Reference Data:** Public external datasets (used for contextual validation only)  
- **Analysis:** Univariate, bivariate, and trivariate analysis at PIN-code level  
- **Output:** Priority scoring to highlight regions requiring focused vaccination outreach  

---

## 🎯 Impact

- Enables data-driven prioritization of vaccination camps  
- Supports efficient mobilization of volunteers and clinical resources  
- Helps identify regions with potential clusters of “invisible” infants  

---

## 🛠️ Tech Stack

Python | Pandas | NumPy | Matplotlib | Seaborn | Jupyter Notebook

---

**Outcome:** A concise, explainable framework to support proactive vaccination planning using Aadhaar-based insights, complemented by external reference data.
