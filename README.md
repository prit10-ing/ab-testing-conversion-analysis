# 📊 A/B Testing Analysis: Landing Page Optimization

## 🚀 Project Overview

This project analyzes an A/B test conducted to evaluate whether a new landing page improves user conversion rates compared to the existing (old) landing page.

The goal is to make a **data-driven business decision** on whether to implement the new design.

---

## 🎯 Business Problem

A company introduced a new landing page to increase conversions. However, it is unclear whether the new design performs better or if observed differences are due to randomness.

**Key Question:**

> Does the new landing page significantly improve conversion rates?

---

## 📦 Dataset Description

The dataset contains user-level interaction data:

* `user_id` → Unique user identifier
* `timestamp` → Time of visit
* `group` → control / treatment
* `landing_page` → old_page / new_page
* `converted` → 0 (No) / 1 (Yes)

---

## 🧹 Data Cleaning & Preparation

* Removed duplicate users
* Eliminated mismatched group & landing page records
* Validated binary conversion values
* Ensured balanced experiment groups

---

## 📊 Exploratory Data Analysis

* Calculated conversion rates for both landing pages
* Compared total users and conversions
* Analyzed trends over time

---

## 📈 Key Metrics

* **Old Landing Page Conversion Rate:** ~12.03%
* **New Landing Page Conversion Rate:** ~11.87%
* **Lift:** -1.3% (decline)

---

## 🧪 Hypothesis Testing

* **Test Used:** Two-Proportion Z-Test
* **Null Hypothesis (H₀):** No difference in conversion rates
* **Alternative Hypothesis (H₁):** Difference exists

### Result:

* **P-value > 0.05**
* Fail to reject H₀

👉 The difference is **not statistically significant**

---

## 📉 Insights

* The old landing page slightly outperforms the new landing page
* The observed difference is minimal and statistically insignificant
* The new design does not provide measurable improvement

---

## 💡 Business Recommendation

* Do NOT implement the new landing page
* Conduct further experiments with improved variations
* Focus on alternative optimization strategies

---

## 📊 Dashboard (Power BI)

The project includes an interactive Power BI dashboard with:

* KPI cards (conversion rates, lift)
* Conversion comparison (bar chart)
* Trend analysis (line chart)
* Final business insights

---

## 🛠️ Tech Stack

* Python (Pandas, NumPy)
* Statistics (Z-test)
* Power BI (Visualization & Dashboard)
* GitHub (Version Control)

---

## 📁 Project Structure

```
ab-testing-conversion-analysis/
│
├── data/
│   └── ab_data.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── dashboard/
│   └── powerbi_dashboard.pbix
│
├── reports/
│   └── business_report.pdf
│
├── README.md
└── requirements.txt
```

---

## 🎯 Key Takeaways

* Importance of statistical testing in decision making
* Difference between observed vs significant results
* End-to-end data analysis workflow (Python → Power BI)

---

## 📬 Contact

If you found this project useful or have suggestions, feel free to connect!
