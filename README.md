## Bitcoin Reddit Sentiment Analysis

This project analyzes public sentiment around Bitcoin by scraping posts and top comments from the r/Bitcoin subreddit and applying a transformer-based NLP model for sentiment classification. It visualizes the distribution of sentiment and provides an overall market sentiment summary that can be used for crypto market insights or as an input into trading models.

### Key Features

* Scrapes Reddit posts and top comments using the PRAW API
* Applies a RoBERTa-based sentiment analysis model from Hugging Face
* Classifies text as Positive, Negative, or Neutral
* Calculates aggregate sentiment statistics and averages
* Visualizes results with Matplotlib and Seaborn
* Maps sentiment to market outlook: Bullish, Bearish, or Sideways

### Use Cases

* Tracking community sentiment toward Bitcoin in real time
* Generating features for algorithmic crypto trading models
* Analyzing sentiment trends for research or investing

### Requirements

* Python 3.8+
* PRAW
* Transformers
* PyTorch
* Seaborn, Matplotlib, Pandas, NumPy

### Note

The model is designed for short social media-style text and may not reflect nuanced financial opinions. For production use, further data cleaning and validation is recommended.
