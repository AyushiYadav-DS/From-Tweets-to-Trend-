# 📊 From Tweets to Trend - Analyzing the Impact of Social Media Sentiment on Stock Price Movements

## 📌 Objective
This project explores how **social media sentiment influences stock price movements**. By processing tweet sentiment scores and mapping them to stock market data, the project visualizes market behavior through a comprehensive **Tableau dashboard**.

## 📥 Data Sources

  **Stock Price Data & Tweet Sentiment Data: Kaggle**


## 🧹 Preprocessing (Done in Python)
**Steps Performed:**

>> Load and clean tweet data

>> Dropped missing values in tweet text or date fields

>> Convert datetime

>> Converted created_at to datetime and extracted only date

>> Assign sentiment labels using textblob

>> Based on sentiment_score: Positive, Negative, Neutral

>> Count tweets by sentiment

>> Total tweets per sentiment per stock

>> Group by date

>> Averaged daily sentiment scores

>> Merge datasets <br>
Combined tweet data with stock prices on the date field  

>> Prepared final data for Tableau visualization


## 📊 Tableau Visualizations

An interactive Tableau dashboard was built to show insights and relationships:

### ✅ Visual Components:

1. **Sentiment Distribution**

   >> Bar chart showing count of Positive, Neutral, and Negative tweets

2. **Sentiment vs. Price**

   >> Line chart or scatter plot comparing sentiment levels with stock prices over time

3. **Sentiment vs. Average Stock Movement**

   >> Comparison of average stock change per sentiment category

4. **Sentiment Score vs. Stock Price Change**

   >> Scatter plot showing correlation between tweet sentiment score and stock price shift

5. **Frequency of Stock Mentions**

   >> Bar chart for most mentioned stocks across tweets

6. **Candlestick Chart**

   >> Technical stock visualization (Open, High, Low, Close)



## 🛠️ Tools Used

| Tool        | Purpose                      |
| ----------- | ---------------------------- |
| **Python**  | Data preprocessing & merging |
| **Pandas**  | Data wrangling               |
| **Tableau** | Dashboard & Visualization    |



## 📌 Conclusion

The analysis reveals strong connections between public sentiment and market movement. By tracking what people say about stocks and when, this project shows how sentiment can provide **early signals** for price trends.




   





