# hw12-crypto_NLP

* To run this notebook, you will need to add a .env file with an API key to NewsAPI

## Sentiment Analysis

### Questions:

Q: Which coin had the highest mean positive score?

A: Ethereum had the highest mean positive score with 0.08349 compared to Bitcoin at 0.05951

Q: Which coin had the highest compound score?

A: Ethereum had the highest mean compound score at 0.224866 compared to Bitcoin at 0.128253. However, Bitcoin had the highest/max compound score at 0.9127, compared to Ethereum at 0.8581.

Q. Which coin had the highest positive score?

A: Ethereum had the hightest mean positive score of 0.08349 compared to Bitcoin at 0.05951. However, Bitcoin had the highest/max positive score of 0.351 compared to Ethereum at 0.252.

## Frequency Analysis

Both BTC and ETH share similar Bigrams including "expressed/entrepreneur" and "elon/musk". Bitcoin seems to like "accelerating", which Ethereum seems to reference other coins.

The Top 10 word count doesn't really say much

# Named Entity Recognition

NER does a good job of pulling out people and organizations, making it easy to filter out who is working in which space. For example, ARK Invest and Mark Cuban show up in Ethereum and not Bitcoin.