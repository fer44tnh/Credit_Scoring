# 💼 Credit Scoring and Survival Analysis Project

## 📘 Project Summary

This project was completed as part of a Master's-level individual assignment in credit scoring. In the scenario, I was hired as a **data scientist by a financial institution** specializing in loans to subprime customers. The institution provided anonymized datasets of both accepted and rejected loan applicants and tasked me with developing a robust **application credit scorecard** to optimize credit risk decisions.

In addition, I performed a **survival analysis** to understand default behavior over time using a second dataset, `mortgage.csv`, which includes borrower and economic indicators.

---

## 🎯 Objectives

### Part 1: Credit Scoring
- Develop a credit scorecard from anonymized applicant data.
- Incorporate **reject inference** to address bias from rejected applicants.
- Use **Weight of Evidence (WoE)** encoding and analyze the number of bins.
- Compare classification models and justify final selection.
- Evaluate performance using industry-standard metrics.
- Minimize expected **operational risk** and **cost of default**:
  - **Loss Given Default (LGD):** 75%
  - **Risk-Free Rate:** 1.5%
- Ensure the process is fully documented and reproducible.

### Part 2: Survival Analysis
- Evaluate **time to default** based on outstanding balance at loan origination.
- Compare survival probabilities at **25** and **50** months for low vs. average/high balances.
- Fit a **Cox Proportional Hazards model** with time-varying covariates.
- Interpret the impact of macroeconomic variables on default risk.

---

## 🧪 Methodology

### 📌 File 1: Credit Scoring
- Data Pre-processing
- Train-test Splitting
- Exploratory Data Analysis (EDA)
- Outlier Treatment
- WoE Transformation and IV Analysis
- Dummy Variable Encoding
- Reject Inference Methods
- Sampling Techniques (Over/Under)
- Cost Function Optimization
- Model Training and Evaluation
- Score Generation and Scaling
- Final Scorecard Interpretation
- Variable Contribution to Scores

### 📌 File 2: Survival Analysis
- Group Comparison Based on Origination Balance
- Kaplan-Meier Estimation
- Probability of Survival at 25 and 50 Months
- Cox PH Model with Time-varying Features
- Interpretation of Coefficients (Economic Factors and Risk)

---

## 📦 Project Structure
credit-scoring-survival-project/
├── Individual_project_part1.ipynb # Credit scorecard modeling
├── Individual_project_part2.ipynb # Survival analysis modeling
├── Credit_scoring_project.pdf # Presentation slides
├── Assignment.pdf # Assignment description
├── data/ # Contains anonymized datasets
│ ├── applicants.csv
│ └── mortgage.csv
├── README.md # This file

---

## 📊 Key Results

### Credit Scoring:
- Developed an interpretable scorecard using logistic regression.
- Integrated reject inference to reduce selection bias.
- Optimized cutoff threshold based on cost minimization.
- Demonstrated strong discriminatory power via AUC, KS, and Gini metrics.

### Survival Analysis:
- Identified significant differences in survival probabilities between groups.
- Found that economic indicators (GDP, unemployment rate, etc.) significantly impact default timing.
- Cox model provided interpretable hazard ratios for policy formulation.

---

## 🧰 Technologies Used

- Python (pandas, numpy, scikit-learn, lifelines, matplotlib, seaborn)
- Jupyter Notebook
- Survival Analysis (Kaplan-Meier, Cox PH)
- Logistic Regression & Reject Inference
- Credit Scoring Best Practices

---

## 🎓 Academic Context

This project was submitted as part of the **Credit Scoring** course at IESEG School of Management.  
Deadline: **July 20, 2023**

Instructor: Dr. P. Borchert  
Contact: [p.borchert@ieseg.fr](mailto:p.borchert@ieseg.fr)

---

## 📬 Author

**Fernando Diaz**  
Feel free to connect on [LinkedIn](https://www.linkedin.com/in/fernando-d%C3%ADaz-gonz%C3%A1lez-manjarrez-18a42711b/) or reach out at [fer44tnh@gmail.com] for questions or collaboration.
