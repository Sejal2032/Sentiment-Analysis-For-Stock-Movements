# 📰 Stock Market Sentiment Analysis Using Financial News
## 📊 Overview
This project explores the relationship between financial news sentiment and stock market movements using Natural Language Processing (NLP) and time-series analysis.

It combines news headlines from multiple sources with historical stock price data (Google - GOOG) to analyze whether market sentiment influences next-day stock returns.

---
## 🎯 Objective
To determine whether financial news sentiment can help explain or predict stock price movements.

---
## 🔄 Project Workflow
### 1️⃣ Data Collection
News data collected from:
- CNBC
- Reuters
- The Guardian
- Stock data extracted using Yahoo Finance (yfinance)
### 2️⃣ Data Preprocessing
- Removed punctuation, numbers, and special characters
- Converted text to lowercase
- Removed stopwords using NLTK
- Cleaned and structured timestamps for merging
### 3️⃣ Sentiment Analysis
- Applied TextBlob NLP model
- Generated sentiment polarity scores:
  - Positive (> 0)
  - Neutral (= 0)
  - Negative (< 0)
### 4️⃣ Data Integration
- Merged news dataset with stock prices using date/time alignment
- Calculated:
  - Daily closing price
  - Next-day stock price change
  - Average sentiment per time period
### 5️⃣ Exploratory Data Analysis (EDA)
Performed deep analysis on:
  - Sentiment trends over time
  - Stock price fluctuations
  - Sentiment vs market movement correlation
  - Weekday-based sentiment behavior
---
## 📊 Key Insights
- 🟡 Most news headlines are neutral in tone
- 📉 Weak direct correlation between sentiment and stock movement
- 📈 Positive sentiment slightly aligns with upward price movement
- ⚠️ Stock prices are influenced by multiple external factors beyond news alone
- 🧠 Sentiment is useful for contextual analysis, not direct prediction

--- 
## 📈 Visualizations
### 📊 Sentiment Distribution
Breakdown of Positive, Negative, and Neutral headlines

<img width="558" height="393" alt="image" src="https://github.com/user-attachments/assets/0f16305c-4321-4b2c-98e7-af2a81749e8a" />

### 📉 Sentiment vs Stock Movement
Relationship between sentiment score and next-day price change

<img width="556" height="393" alt="image" src="https://github.com/user-attachments/assets/7064d850-8b80-451e-bb3b-2af4a873c8a7" />

### 📊 Average Stock Change by Sentiment
How stock behaves based on news sentiment

<img width="547" height="393" alt="image" src="https://github.com/user-attachments/assets/9b83d127-284a-482c-857a-75abb03559ef" />

### 📈 Sentiment Over Time
Trend of average sentiment across time

<img width="1049" height="393" alt="image" src="https://github.com/user-attachments/assets/7290a929-21df-4d4c-89ff-a926afa722de" />

### 📊 Stock Price vs Sentiment
Dual-axis comparison of market price and sentiment

<img width="1068" height="393" alt="image" src="https://github.com/user-attachments/assets/664ef861-b7f7-4c63-b5e3-be4436a7bce8" />

### 📊 HeatMap: Sentiment Weekly
Average Sentiment by Weekly

<img width="717" height="393" alt="image" src="https://github.com/user-attachments/assets/dd9edb74-e58d-4c06-8e46-8896348b27e1" />

### 📉 Sentiment Density Plot
Distribution of sentiment polarity scores

<img width="531" height="393" alt="image" src="https://github.com/user-attachments/assets/c544b3dd-9d80-450a-a064-91b877b88e14" />

--- 
## 🧠 Tools & Libraries

| Library | Purpose |
|----------|----------|
| `pandas` | Data cleaning and merging |
| `numpy` | Numerical operations |
| `matplotlib` | Visualization |
| `seaborn` | Stylish visualizations |
| `textblob` | Sentiment analysis |
| `yfinance` | Stock data download |
| `nltk` | Text preprocessing |

---
---


