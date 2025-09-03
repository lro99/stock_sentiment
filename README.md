# stock_sentiment

Using Sentiment Analysis to get general sentiment of the day.

For negative sentiment, the market most often turns down, which could present a buying opportunity.
For positive sentiment, the market most often turns up, which could present a selling opportunity.

The notebook analyzes different techniques, including a baseline of rolling average, LSTM, random forest.

For sentiment analysis, two different methods are attempted: FinBERT from hugging face, and FinHub API

Next Steps:
- Get daily sentiment in score, attempt to get historical daily scores.
- Create rule for daily scores, track profit from buying/selling from sentiment signal
