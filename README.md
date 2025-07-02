
# 📊 Employee Sentiment Analysis

This project analyzes internal employee communications to assess overall sentiment, rank employee engagement, detect flight risk, and build predictive sentiment models using natural language processing and machine learning.

## 🧩 Tasks Overview

### ✅ Task 1: Sentiment Labeling
- Each message was labeled as **Positive**, **Negative**, or **Neutral** using TextBlob sentiment polarity.
- Labels were saved in `test_with_sentiment.csv`.

### ✅ Task 2: Exploratory Data Analysis (EDA)
- Explored sentiment distribution, message volume, and message length.
- Visuals saved in the `visualizations/` folder.

### ✅ Task 3: Monthly Sentiment Score Calculation
- Assigned scores (+1, 0, -1) and calculated employee-wise **monthly sentiment scores**.
- Output stored in `monthly_sentiment_scores.csv`.

### ✅ Task 4: Employee Ranking
- Ranked top 3 most positive and most negative employees for each month.
- Stored in `employee_monthly_rankings.csv`.

### ✅ Task 5: Flight Risk Identification
- Employees with **4 or more negative messages in any rolling 30-day window** were flagged as flight risks.
- Output: `flight_risk_employees.csv`.

### ✅ Task 6: Predictive Modeling
- Built a **Linear Regression** model to predict sentiment scores using message-level features.
- Evaluated using **MAE** and **R²**.
- Charts: `actual_vs_predicted.png`, `residual_plot.png`

## 📦 Files Included

- `employee_sentiment_analysis.ipynb` – Complete code notebook
- `report.docx` – Final report with task descriptions and findings
- `README.md` – Project summary
- `test_with_sentiment.csv` – Dataset with sentiment labels
- `monthly_sentiment_scores.csv` – Monthly score per employee
- `employee_monthly_rankings.csv` – Top positive/negative employees
- `flight_risk_employees.csv` – List of flight risk employees
- `visualizations/` – Folder with all plots

## 📌 Key Insights

- Employees like E001 consistently showed positive sentiment.
- Employees like E007 were flagged as potential flight risks.
- Predictive model achieved good performance with strong correlation between message features and sentiment score.

---

🧠 Built using Python, Pandas, Matplotlib, TextBlob, and scikit-learn.
