# Tales from the Crypto

The crypto_sentiment notebook applies natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. The code also applies fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

---

## Technologies

Language: Python3, Pandas 

Imports: os, pandas, dotenv, re, punctuation from string, matplotlib inline, SentimentIntensityAnalyzer from nltk.sentiment.vader, NewsApiClient from newsapi, word_tokenize and sent_tokenize from nltk.tokenize, stopwords from nltk.corpus, WordNetLemmatizer and PorterStemmer from nltk.stem, Counter from collections, and ngrams from nltk

External Resources: News API

Developed with JupyterLab

---

## Installation

JupyterLab - [Install JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)

---

## Examples

Example of wordcloud:
![bitcoin_wordcloud](Resources/bitcoin_wordcloud.png)

Example of NER visualization:
![bitcoin_ner](Resources/bitcoin_ner.png)

---

## Contributors

Drew Disbrow Marnell: dldmarnell@gmail.com

---

## License

MIT License
Copyright (c) 2021 Drew Disbrow Marnell