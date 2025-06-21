# 🏠✨ Boston Housing Dataset - EDA Summary  
*Date: June 21, 2025*

Hey folks! 🙋‍♂️  

Today I dived into the **Boston Housing dataset** as part of my data science practice. My main aim was to understand the dataset structure and uncover how different features affect the **Median Home Value (MEDV)** using meaningful visualizations and analysis.

---

## 🧭 Key Insights from the EDA

After briefly exploring the data structure and types, I focused on visualization-driven insights. Here's what I found:

### 📈 Solo Feature Observations:
- The **MEDV** distribution showed some skewness 🪁 and outliers 🧨 — possibly requiring transformation during modeling.
- **TAX** and **AGE** displayed skewed right-heavy distributions 🪜, hinting at locations with unusually high tax rates and older housing stock.

### 🔄 Feature-to-Target Interactions:
- **Scatter plots** showed:
  - A **positive link** between **RM** (average rooms) and **MEDV** 🧱🏡 — more rooms generally meant more value.
  - A **strong negative link** between **LSTAT** (percentage of lower-status population) and **MEDV** 🧮🔻 — confirming socio-economic influence.
  - **PTRATIO** (pupil-teacher ratio) had a mild negative effect on MEDV 🎓⚖️.

### 🗺️ Categorical Feature Influence:
- A **box plot** comparing **CHAS** (Charles River adjacency) vs **MEDV** showed slightly elevated values near the river 🛶, though with wide variability 🌊📊.

### 🧬 Multivariable Analysis:
- The **correlation heatmap** 🧊 helped visualize linear dependencies:
  - Strong correlations: **RM** (↑) and **LSTAT** (↓) with **MEDV**.
  - High correlation between **RAD** and **TAX**, implying potential feature overlap 🔁.
- A **pair plot** for **CRIM, RM, LSTAT, and MEDV** showed clear trends and possible clusters 🕸️📍.

---

## 🧠 Final Thoughts

This analysis helped me understand which features are most predictive and where to focus during preprocessing or model tuning. Given the non-linear patterns and outlier presence, future modeling will likely benefit from thoughtful feature engineering and robust algorithms.

Would love to hear your thoughts or suggestions for taking this deeper! 🎯🧩
