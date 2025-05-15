# rbac_2024_round2

**Situation:**  
This project was conducted as part of Round 2 of the RMIT Business Analytics Champion Season 5. The task was to analyze customer data from SHB Finance and build insightful customer profiles, with the goal of identifying potential customer segments for consumer lending products.

---

**Task:**  
Based on the problem statement, my key responsibilities included:

- Cleaning and preprocessing data from two sources: `demographics` and `loan_origin`.
- Conducting exploratory data analysis to understand customer behavior.
- Performing feature engineering to enhance insights.
- Segmenting customers based on demographic and loan-related variables.
- Providing data-driven business recommendations tailored to each customer segment.

---

**Action:**  

- Used `pandas` and `numpy` to handle missing values based on variable types (e.g., mode imputation, -1 for unknown categories).
- Engineered new features such as customer age, working years, and loan-to-interest ratios.
- Used **KMeans clustering** to identify meaningful customer segments.
- Visualized and interpreted cluster characteristics with **Plotly** to ensure clarity and business relevance.
- Summarized each segment with distinct behavioral and demographic traits.

---

**Result:**

- Successfully segmented customers into three main groups with distinct financial behaviors and risk profiles.
- Proposed actionable strategies for each segment:
  - Increase credit limits for high-potential customers.
  - Bundle insurance products for customers with high loan volumes.
  - ...
