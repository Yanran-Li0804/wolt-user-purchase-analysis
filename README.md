# wolt-user-purchase-analysis

# Wolt Pre-task: User Purchase Behavior Analysis

## 📌 Project Overview

This project explores the relationship between when a user makes their first purchase and how frequently they order in the long term.

The analysis was completed as part of a pre-task for a Data Analyst position at Wolt.

The dataset contains machine-generated customer data from a Wolt-like service, covering user registration and order behavior from Sep 2019 to Oct 2020.

---

## 🧠 Business Question

Does the timing of a user’s first purchase (e.g. within Day 1 or Week 1) influence their long-term purchase frequency?

---

## 📊 Methodology

Defined two key metrics:

- 🕐 Early Purchase Behavior: categorized users based on their first order timing  
  → Day 1 | Week 1 | Within 14 Days | No early purchase

- 🔁 Purchase Frequency: total orders divided by number of days since registration

Key analysis techniques:
- Group comparison
- T-tests
- OLS linear regression

---

## 💡 Key Insights

- Almost all very high-frequency users made their first purchase within the first week.
- T-tests show significant correlation between early purchases (especially Week 1 and 14 days) and frequency.
- Week 1 buyers have the highest average frequency.
- Regression results confirm: early purchase (especially within Week 1) positively predicts purchase frequency.

📄 Full results and charts are in the Jupyter notebook and slide deck.

---

## 🧰 Tools Used

- Python (Pandas, Matplotlib, Seaborn, Statsmodels)
- Jupyter Notebook
- T-test & OLS Regression
- Data visualization

---

## 📂 Files

- `/notebook/analysis.ipynb`: full analysis in Jupyter Notebook
- `/slides/wolt-insights.pdf`: slide deck summarizing key findings
- `/data/dataset_for_datascience_assignment.csv`: Simulated user data provided as part of Wolt’s pre-task

> Note: The dataset is machine-generated and was provided for analytical purposes only as part of the Wolt Data Analyst pre-task. No real user information is included.

---

## 📬 Contact

Feel free to reach out by email at lyrglmlzx@126.com
