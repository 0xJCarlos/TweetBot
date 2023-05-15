# Video Game Journals Tweet Scrapper and Analysis
## The API Used in the TweetFetcher script has been Deprecated
These Python Scripts scrape over 30,000 of tweets from video game journal accounts. They performs the following tasks:

1. Extract Tweets from Specified Twitter Accounts
2. Determines the general opinion (Positive, Negative, Intermediate) on the mentioned topics.
3. Displays the results using tables and charts.

## Dependencies

- Python 3
- pandas
- spacy
- nltk
- matplotlib
- tqdm
- nltk's VADER lexicon (sentiment analysis)

## Scripts

### TweetFetcher
This Script fetches or scraps Tweets from different stablished accounts using the Twiter API (Deprecated) and the TweePy Library.

### Preprocessing
Using Natural Language Processing and Sentiment Analysis we find out the most mentioned Entities 
As well as the general consensus or opinion of these Entities.
