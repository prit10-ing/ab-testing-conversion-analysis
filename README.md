# 📊 A/B Testing Analysis: Landing Page Optimization

This project demonstrates a complete, industry-level end-to-end data analytics workflow focused on evaluating the effectiveness of a new landing page using A/B testing.

It covers the full lifecycle of a real-world data analytics project — from data preparation and statistical validation to visualization and business decision-making.

---

## 🚀 Project Overview

The objective of this project is to determine whether a new landing page improves user conversion rates compared to the existing (old) landing page.

The analysis follows a structured workflow:

* 🧹 Data Cleaning & Preparation (Python)
* 📊 Exploratory Data Analysis (EDA)
* 🧪 Statistical Testing (Two-Proportion Z-Test)
* 📈 Visualization & Dashboard (Power BI)
* 📄 Business Insights & Recommendations

---

## 🎯 Business Problem

A company introduced a new landing page to increase conversions. However, it is unclear whether the new design performs better or if observed differences are due to random variation.

**Key Question:**

> Does the new landing page significantly improve conversion rates?

---

## 📦 Dataset Description

The dataset contains user-level interaction data:

* `user_id` → Unique identifier
* `timestamp` → Time of interaction
* `group` → control / treatment
* `landing_page` → old_page / new_page
* `converted` → 0 (No) / 1 (Yes)

---

## 🧹 Data Preparation

* Removed duplicate users
* Eliminated mismatched group and landing page records
* Validated binary conversion values
* Ensured experiment consistency

---

## 📊 Exploratory Data Analysis

* Compared conversion rates across landing pages
* Analyzed distribution of users
* Evaluated trends over time

---

## 📈 Key Metrics

* **Old Landing Page Conversion Rate:** ~12.03%
* **New Landing Page Conversion Rate:** ~11.87%
* **Lift:** -1.3%

---

## 🧪 Hypothesis Testing

* **Test Used:** Two-Proportion Z-Test
* **Null Hypothesis (H₀):** No difference in conversion rates
* **Alternative Hypothesis (H₁):** Difference exists

### Result:

* **P-value > 0.05**
* Fail to reject H₀

👉 The observed difference is **not statistically significant**

---

## 📉 Key Insights

* The old landing page performs slightly better than the new landing page
* The difference in conversion rates is minimal
* The result is not statistically significant

---

## 💡 Business Recommendation

* Do NOT replace the old landing page
* Conduct further A/B testing with improved variations
* Explore alternative optimization strategies

---

## 📊 Dashboard (Power BI)

The project includes an interactive dashboard featuring:

* KPI Cards (Conversion Rate, Lift)
* Conversion Comparison (Bar Chart)
* Trend Analysis (Line Chart)
* Final Business Insight

---

## 🛠️ Tech Stack

* Python (Pandas, NumPy)
* Statistics (Z-test)
* Power BI (Dashboard & Visualization)
* Git & GitHub

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

## 🎯 Key Learnings

* Importance of statistical testing in decision-making
* Difference between observed vs significant results
* End-to-end analytics workflow (Python → Power BI)
* Translating data into business insights

---

## 📌 Conclusion

The analysis shows that the new landing page does not significantly improve conversion rates. Therefore, it is not recommended for implementation without further testing.

---

⭐ If you found this project useful, consider starring the repository.
