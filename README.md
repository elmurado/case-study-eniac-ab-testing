# 🧪 A/B Testing for Homepage Optimization – Boosting Eniac’s CTR

This project explores how **changes to a call-to-action button** can influence user behavior and improve sales conversions for **Eniac**, a fictional e-commerce tech company.

---

## 📖 Case Study Overview

The project consisted of two major parts:
1. A **theoretical research presentation** to establish best practices for A/B testing.
2. A **practical A/B test analysis** based on real web interaction data.

The focus was on optimizing the **“SHOP NOW”** button promoting the iPhone 13, which initially had a low **click-through rate (CTR)**.

---

## 🧠 Theoretical Foundation

Before conducting the test, a **theoretical analysis** was performed to answer key questions:

1. **How many versions should be tested?**
2. **What types of changes can be made (minor, moderate, or major)?**

### Key Takeaways:
- Start with **manageable changes** (e.g., button color, CTA wording) before redesigning entire pages.
- Focus on **high-traffic elements** (like CTA buttons) for initial A/B tests.
- Use **data-driven decisions** and avoid premature conclusions.
- **Plan and document** hypotheses, variations, and expected outcomes carefully.

---

## 🧪 Practical Experiment Setup

Four homepage versions were tested:

| Version | Button Color | Button Text   |
|---------|--------------|---------------|
| A       | White        | SHOP NOW      |
| B       | Red          | SHOP NOW      |
| C       | White        | SEE DEALS     |
| D       | Red          | SEE DEALS     |

### Experiment Details:
- 🎯 **Primary Metric:** Click-through rate (CTR)
- 📅 **Test Duration:** 14 days
- 🧮 **Statistical Approach:** Chi-Square Test + Post-hoc pairwise comparisons
- 🎯 **Significance Level (Alpha):** 0.05
- 🎯 **Minimum Detectable Effect (MDE):** 20%

---

## 📈 Analysis & Key Results

### Statistical Findings:
- ✅ **Chi-Square Test**: Significant difference between versions (p-value = 2.7e-48).
- 🔍 **Post-hoc Tests**:
  - **Version C** (white button + "SEE DEALS") had the **highest CTR**.
  - **Version A** (white button + "SHOP NOW") was **statistically comparable** to Version C.
  - **Versions B and D** performed significantly worse.

| Version | CTR (%) |
|---------|---------|
| C       | 1.57    |
| A       | 1.49    |
| D       | 1.47    |
| B       | 1.40    |

---

## 📦 Deliverables

- 🧠 [**A/B Testing Theory Presentation (PDF)**](https://github.com/elmurado/case-study-eniac-ab-testing/blob/main/AB_Testing_Theory_and_Industry_Best_Practices.pdf)  
  → Conceptual foundation: Best practices for setting up A/B tests, testing strategy, pitfalls to avoid.

- 📊 [**A/B Test Analysis Notebook (Jupyter Notebook)**](https://github.com/elmurado/case-study-eniac-ab-testing/blob/main/AB_Test_Chi_Square_Homepage_Eniac.ipynb)  
  → Full statistical workflow: Data cleaning, Chi-Square test, post-hoc testing, and visualization.

---

## 🧠 Final Conclusions & Business Recommendations

- **Versions A and C** emerged as top candidates, but **no definitive winner** could be statistically declared.
- **Next Steps**:
  - Evaluate **additional KPIs** (e.g., conversion-to-sale rates).
  - Conduct **qualitative user feedback** analysis.
  - Collaborate with **design and marketing teams**.
  - Iterate with **new A/B tests** based on refined hypotheses.

---

## 🛠 Tools & Technologies Used

- **Programming Languages & Libraries**:
  - Python: `pandas`, `numpy`, `scipy`
  - Visualization: `seaborn`
- **Development Environment**:
  - Jupyter Notebook
- **Statistical Methods**:
  - Chi-Square Test
  - Post-hoc pairwise comparisons

---

## 💡 Key Learnings

- **Statistical significance ≠ business significance**: Results must be interpreted in context.
- **Solid experimental design** is crucial for meaningful A/B tests.
- **Documentation and planning** improve test reliability and reproducibility.
- 📢 **Data alone rarely gives the full answer** — combining statistical analysis with business judgment ensures smarter decisions.

