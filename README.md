#Capstone Project: Measure how news sentiment correlates with stock price changes on the same day or in following days (lag effect)
# 📈 Apple Stock vs. News Sentiment (2012–2022)

This project explores the relationship between **U.S. news sentiment** and **Apple Inc. (AAPL) stock price movements** over a 10-year period (2012–2022). Using Natural Language Processing (NLP) techniques, we analyze whether headlines and article tone can help explain — or even predict — how Apple’s stock behaves.

---

## 🧠 Project Objective

- Investigate whether news sentiment correlates with AAPL stock price changes.
- Explore lag effects (e.g., sentiment today vs. price change tomorrow).
- Visualize relationships and highlight timeframes where sentiment has a stronger effect.

---

## 📁 Files

- `Apple_Share_Sentiment_with Apple_rel_article.ipynb`: Main Jupyter notebook containing all code, visualizations, and analysis.

---

## 📊 Data Sources

- **Stock Data**: Apple (AAPL) daily historical prices (Open, High, Low, Close, Volume). the code to get this is written in `Get_sharePrice.ipunb`
- **News Data**: news articles mentioning Apple, cleaned and pre-processed.
- **Keywords**: Filter list for Apple-related mentions.

---

## 🛠️ Tech Stack

- **Python**: Data processing, analysis
- **Pandas**: DataFrame manipulation
- **Matplotlib**: Plotting
- **TextBlob** & **VADER (NLTK)**: Sentiment analysis
- **Jupyter Notebook**: Code execution and documentation

---

## 📈 Key Metrics & Outputs

- **Sentiment Scores**: Assigned per article using NLP
- **Return Calculations**: Daily % change in AAPL price
- **Correlation Matrix**: Sentiment vs. return/price change
- **Scatter Plots**: Visualizing sentiment-return relationships
- **Lag Analysis**: Impact of previous-day sentiment on stock movement

---

##
