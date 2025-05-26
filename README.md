# Turtle Games Customer Loyalty Analysis – 87% Final Grade

This project was completed as part of the LSE Data Analytics Career Accelerator (Course 3). I analysed customer-level data from Turtle Games, a fictional global game manufacturer and retailer, to uncover what drives loyalty point accumulation, how to segment customers, and how review sentiment can inform marketing. The analysis informed data-backed strategies to improve customer retention, engagement, and campaign targeting.

---

## 🛠️ Tools Used

- **Python** (Pandas, Scikit-learn, TextBlob, Matplotlib)
- **R** (ggplot2, car, moments, stats)

---

## 📁 Files

- 📘 [Presentation Slides](./Turtle%20Games%20Presentation.pdf)  
- 📄 [Project Report](./Turtle%20Games%20Report.pdf)  
- 📓 [Analysis Notebook](./Turtle%20Games%20Notebook.ipynb)

---

## 🧠 Business Problem

Turtle Games wanted to improve overall sales performance by:
- Understanding how customers earn and engage with loyalty points  
- Segmenting customers for smarter campaign targeting  
- Using customer reviews to extract marketing-relevant feedback  
- Evaluating if loyalty point data is suitable for predictive modelling

---

## 📊 Analytical Approach Highlights

- Cleaned and transformed customer data using Python  
- Built a **multiple linear regression model** in R using log-transformed loyalty points  
- Performed **decision tree modelling** to visualise loyalty point drivers  
- Used **K-means clustering** to identify 5 customer segments  
- Applied **TextBlob sentiment analysis** on reviews and summaries  
- Ran statistical tests for skewness, kurtosis, multicollinearity, and residual assumptions

---

## 🔍 Key Insights

- **Spending score** and **remuneration** are strong, independent predictors of loyalty  
- MLR model explains ~80% of the variance in log loyalty points  
- Top 1% of customers (loyalty points > 4000) are high-income and high-spending  
- Demographics (age, gender, education) are weak predictors of loyalty behaviour  
- Review text is richer in actionable sentiment than summary fields  
- Sentiment scores can flag pain points and positive themes for marketing and product teams

---

## ✅ Recommendations

- Allocate 70% of loyalty marketing to high-income, high-spending customers  
- Introduce a premium loyalty tier for the top 1% earners  
- Use negative review sentiment (< 0) to trigger interventions  
- Drop the summary field from text analysis due to limited value  
- Redirect ad spend to high spenders with low loyalty point accumulation  
- Design targeted campaigns using the 5 customer segments identified

---

## 🚀 Professional Development

This project sharpened my ability to:
- Combine behavioural, demographic, and text data for customer analysis  
- Use both Python and R in a structured workflow to clean, model, and visualise results  
- Translate technical analysis into strategic recommendations for marketing and retention  
- Design segmentation frameworks that support real-world decision-making  
- Apply sentiment analysis to product feedback and link it to campaign priorities

It also gave me deeper experience working with mixed data types and refining predictive models to support business action.

Presentation: https://youtu.be/GdSSm70vJn0 
