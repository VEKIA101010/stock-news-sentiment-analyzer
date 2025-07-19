# stock-news-sentiment-analyzer
A simple news sentiment analysis tool based on Python, using Tkinter for the interface, scraping Yahoo Finance news headlines, and performing basic sentiment analysis.
#  Financial News Sentiment Scanner (GUI)

A simple Python GUI tool that fetches recent news headlines for a given stock ticker from Yahoo Finance,  
performs sentiment analysis on the headlines, and visualizes the sentiment distribution with charts.

---

##  Features

-  Fetches latest news headlines for any stock ticker (e.g., AAPL, TSLA) from Yahoo Finance  
-  Uses TextBlob for basic sentiment classification: Positive / Neutral / Negative  
-  Generates and saves a sentiment bar chart as PNG  
-  Creates a text report summarizing sentiment counts and sample news titles  
-  Easy-to-use GUI built with Tkinter — no command line needed!

---

##  Installation

Make sure you have Python 3.7+ installed.

Install required packages:

```bash
pip install requests beautifulsoup4 textblob matplotlib
python -m textblob.download_corpora
