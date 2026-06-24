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
---
 ## EDA( Descriptive statistics) 
 - we see both the percentage and the number of people who stayed with company or resigned in the chart below :
   - In this plot, `0` indicates `NO` and `1` indicates `Yes`.
   - `Yes`: The employee has left the company (resigned, fired, or is no longer with the company).
   - `No`: The employee is still working for the company.
<img width="704" height="547" alt="image" src="https://github.com/user-attachments/assets/bd7429ce-50cc-49e0-9bdb-0beac5bc4f83" />

- we are seeing `16% `of employees either resign or be fired .

---
-In this plot, we have divided age into groups for better understanding:

<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/0d8ae3ea-0f2b-4226-9fdb-0ec1b77b8442" />

- Here we see the distribution of the age column, where most employees are middle-aged.

---

- In this plot, we divided the distance from home to work for employees into three groups (near, medium, and far):

- <img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/edfb3a20-14f1-451a-9b05-2caa4fcdf4d1" />

- What is notable here is that most employees live close to their workplaces, with only `16%` of employees living a long distance from their workplaces.

- ---

As you can see in this plot, the level of education of each employee shows that most employees have a bachelor's degree:

<img width="889" height="490" alt="image" src="https://github.com/user-attachments/assets/a9393070-d936-47c2-a617-d91c5eab10f6" />

---

This plot shows the level of satisfaction of each employee with the work environment:

<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/8ef84981-c8d8-4d38-bd9c-e6b3275d00bb" />

---

This plot shows that 60% of the employees are male and 40% are female:

<img width="690" height="490" alt="image" src="https://github.com/user-attachments/assets/a131a3fe-c20d-4d25-9306-5ae38e222022" />

---
