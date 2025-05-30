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

---

## 🕹️ Visual Storytelling for Insights

Explore the TurtleGames dataset through these slides, highlighting key analytical insights across loyalty, segmentation, sentiment, and strategy.

### 1. Analytical Approach

<img src="Visuals/Visual 1.png" width="800"/>

### 2. How are Loyalty Points Distributed?

<img src="Visuals/Visual 2.png" width="800"/>

### 3. What Influences Loyalty Points?

<img src="Visuals/Visual 3.png" width="800"/>

### 4. Visualising Predictors – Loyalty Points vs Key Variables

<img src="Visuals/Visual 4.png" width="800"/>

### 5. Visualising Loyalty Drivers with a Decision Tree

<img src="Visuals/Visual 5.png" width="800"/>

### 6. Predicting Loyalty Points Using Regression

<img src="Visuals/Visual 6.png" width="800"/>

### 7. Understanding the Top 1% of Loyalty Earners

<img src="Visuals/Visual 7.png" width="800"/>

### 8. Segmenting by Income & Spend (K-Means)

<img src="Visuals/Visual 8.png" width="800"/>

### 9. Customer Profiles & Strategy

<img src="Visuals/Visual 9.png" width="800"/>

### 10. Insights from Customer Reviews – Word Clouds

<img src="Visuals/Visual 10.png" width="800"/>

### 11. Sentiment Patterns – Review vs Summary Polarity

<img src="Visuals/Visual 11.png" width="800"/>

### 12. What Drives Positive and Negative Sentiment?

<img src="Visuals/Visual 12.png" width="800"/>
