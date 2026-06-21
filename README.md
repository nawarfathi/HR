- the  dataset we have consists of `1470` rows and `35` columns , at frist glance it looks like a clean dataset.
- ## 🎯 Project Objective
- Build a **Binary Classification** model to predict attrition (Yes/No)
- Identify the **most important features** driving employee attrition
- Provide **actionable insights** to HR teams to reduce turnover rate
- Handle **Class Imbalance** using proper techniques (SMOTE / class weighting)
- ---
## 📊 Target Variable 
- **Target column:** `Attrition`
- **Values:** `Yes` (employee left) / `No` (employee stayed)
- **Problem type:** Binary Classification
- **Main challenge:** Class Imbalance (~16% Yes vs ~84% No)
- ---
## 📈 Success Metrics 
Since the dataset is imbalanced, primary evaluation metrics:
- **ROC-AUC Score** — primary metric
- **F1-Score** — especially for the minority class (Yes)
- **Precision & Recall** — balance between both
- **Confusion Matrix** — full error analysis
- ---
## 💡 Expected Output 
Final model output:
1. Probability of attrition for each employee (0 to 1)
2. Top contributing features using **SHAP Values**
3. Actionable HR recommendations based on model findings
