# Unit-12-Tales-from-the-Crypto
There's been a lot of hype in the news lately about cryptocurrency's regarding Bitcoin and Ethereum.  Only if we could get a better feel for the current public sentiment around each coin (we can).
- I will apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum.
- I will also apply NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.
## Libraries Needed:
- os
- re
- pandas
- dotenv
- newsapi.newsapi_client
- alpaca_trade_api 
- nltk.sentiment.vader
- nltk.tokenize
- nltk.corpus
- nltk.stem
- string
- collections 
- wordcloud 
- matplotlib.pyplot  
- spacy 
## Tips:
- Remember to restart kernel incase of "bugs".
- Have the environment(.env) file with the alpaca key, alpaca secret key, and a news api key in the same location as the python file.
- The free developer version of the News API limits the total monthly requests, so be careful not to exceed the free limits.