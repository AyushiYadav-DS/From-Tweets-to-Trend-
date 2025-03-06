# From-Tweets-to-Trend(analyse the impact of social media sentiments on stock price)

<b> Objective </b> 
This project analyzes the impact of social media sentiments on stock price movements using sentiment analysis and data visualization. By leveraging machine learning techniques and interactive dashboards, the project helps uncover correlations between public sentiment and stock trends. An interactive Tableau dashboard was created to visualize key insights.

<b> Data Collection & Preprocessing </B>
Dataset:
1) Collected stock price data from financial APIs (Yahoo Finance, Alpha Vantage)
2) Extracted tweets related to stocks using Twitter API & Kaggle datasets
3) As part of the preprocessing step,
- Tweet Cleaning: Remove links, hashtags, stopwords 
- For tweets cleaning  I used NLTK (natural language tool kit)

5) I performed sentiment analysis on tweet data to extract insights about market sentiment.

• Also, calculated the Sentiment Score, This sentiment analysis helped quantify social media sentiment, allowing for a deeper understanding of its impact on stock price movements.<br>
For this analysis I used TextBlob, a natural language processing (NLP) library.<br>
TextBlob analyzes the polarity of each tweet, assigning a sentiment score ranging from -1 to +1.<br>
Based on these scores, tweets were categorized as<br>

1) positive

2) neutral

3) negative

<b> Exploratory Data Analysis (EDA) </b>

1) Stock Price Trends Over Time:
>> Helps track how stock prices change over time.
>> Identifies patterns before and after major sentiment shifts.

2) Sentiment Distribution:
>> This shows how many tweets were positive, negative, or neutral.
>> Helps understand market mood.

3) Sentiment Score vs. Stock Price Change:
>>  Compares sentiment score with % change in stock price.
>> Identifies correlation between social media sentiment and stock movement.

4) Sentiment Impact by Stock:
>> Helps compare different stocks and how much their prices react to sentiment.
>> Identifies which stocks are most affected by social media sentiment

5) Volume & Price Movement Comparison
>> Helps determine if high trading volume aligns with sentiment shifts.
>> Shows whether negative sentiment leads to panic selling

6) Frequency of stock mention:
>>  Analyzes which stocks are discussed most frequently on social media.

7) Candlestick graph:
>> Provides a detailed view of stock price movements (open, high, low, close).
>> Helps traders analyze market trends and price reversals.

   





