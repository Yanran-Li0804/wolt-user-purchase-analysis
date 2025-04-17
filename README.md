# 🛍️ Wolt User Behavior Analysis

This project analyzes machine-generated user data from a Wolt-like delivery service to explore how early purchase behavior impacts long-term customer value.

## 📌 Objective

Wolt currently offers free delivery for users who place their first order within 14 days of registration.  
This analysis aims to evaluate the effectiveness of this strategy and assess whether certain time windows (e.g., Week 1 vs. Week 2) are more predictive of long-term user engagement.

## 🧪 Methodology

- Dataset: Synthetic user data provided by Wolt (Sep 2019–Oct 2020)
- Tools: Python, Pandas, Seaborn, Matplotlib
- Key Metrics:
  - Early Purchase Timing:
    - Day 1
    - Within first 7 days (Week 1)
    - Within first 14 days (Week1 & Week 2)
    - No early purchase
  - Purchase Frequency:
    - Defined as: total number of purchases / total days since registration

## 💡 Key Insights

1. 📈 Almost all very high-frequency users made their first purchase within the first 7 days  
2. 🧪 T-Test & OLS Regression:
   - Significant positive correlation between early purchases (Week 1, Week 2) and long-term purchase frequency
   - However, only Week 1 purchases are statistically strong predictors
3. 📊 Users who purchased in Week 1 have the highest average purchase frequency  
4. 📉 Week 2 purchases are not predictive of long-term user behavior

## ✅ Recommendation

🧠 Week 1 is the most critical period for habit formation.

I recommend:

- ✅ Maintain the current 14-day free delivery policy  
- ➕ Add a Week 1 bonus to reinforce early purchase habits:
  - Free delivery + a lottery entry
  - Lottery reward: extra discount or free delivery if the user places another order within a week

🎯 Goal: Reinforce short-term habits → Maximize long-term value

---

## 📁 Project Structure

- `/notebook/Yanran_Li_Task2_code.ipynb`: full analysis in Jupyter Notebook
- `/slides/Yanran_Li_Task2_slides.pdf`: slide deck summarizing key findings
- `/data/dataset_for_datascience_assignment.csv`: Simulated user data provided as part of Wolt’s pre-task

> Note: The dataset is machine-generated and was provided for analytical purposes only as part of the Wolt Data Analyst pre-task. No real user information is included.


Feel free to explore the notebook and slides for full analysis & visualizations.


## 📬 Contact

Feel free to reach out by email at lyrglmlzx@126.com
