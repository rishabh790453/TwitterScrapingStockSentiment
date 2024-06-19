# TwitterScrapingStockSentiment
Twitter Sentiment Analysis for Stock Tickers
This Jupyter Notebook scrapes tweets related to a given stock ticker symbol from Twitter, performs sentiment analysis on the tweet text, and stores the results in a pandas DataFrame.
Features
  Logs into Twitter using Selenium WebDriver
  Searches for tweets containing the specified stock ticker symbol (e.g., $AAPL, $TSLA)
  Scrolls through the Twitter search results and extracts the user, tweet text, and date for each tweet
  Performs sentiment analysis on the tweet text using the VADER (Valence Aware Dictionary and sEntiment Reasoner) model from NLTK
  Stores the data in a pandas DataFrame with columns for user, text, date, and compound sentiment score
Usage
  Install required packages: pandas, yfinance, matplotlib, nltk, selenium, and their dependencies
  Download the ChromeDriver executable for your Chrome version and place it in the specified path
  Replace the Twitter username and password placeholders with your own credentials
  Modify the web variable to search for the desired stock ticker symbol
  Run the notebook cells sequentially
