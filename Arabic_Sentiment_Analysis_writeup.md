
# Arabic Sentiment Analysis
Sarah Alsubhi

## Abstract
The goal of this project was to use classification models to predict the sentiment of Arabic tweets considering emojies using different models. I worked with data provided by [Motaz Saad](https://www.kaggle.com/mksaad/arabic-sentiment-twitter-corpus)  and word embedding features along with machine learning and deep learning models to achieve promising results for this binaryclass problem. 

## Design
Sentiment analysis is a kind of text mining, which is to predict human mind, specifically the emotional state of a person by extracting specific emotional expressions from the text. Therefore, it can be useful for product reviews and predicting consumer attitudes towards new products.

## Data
The dataset we collected in April 2019. It contains 58K Arabic tweets (47K training, 11K test) tweets annotated in positive and negative labels. The dataset is balanced and collected using positive and negative emojis lexicon. 

## Algorithms

*Feature Engineering*
1. Length of tweets
2. Number of words count
3. Number of characters
4. Number of sentences
5. Average words length
6. Average sentence length.
7. Word embedding. e.g. tfidfvectorizer, Word2vec
8. Bag of Words.


*Models*
  
Logistic regression, MultinomialNB, LSTM, and Bi-LSTM classifiers were used before settling on Bi-Lstm as the model with strongest performance.

*Model Evaluation and Selection*
  
The entire training dataset of 85,000 records was split into 70/30 train. The official metric for DrivenData was classification rate (accuracy).

*Bi-LSTM* 
   - Accuracy 0.87
   - Loss 0.22


## Tools
- Numpy and Pandas for data manipulation
- Scikit-learn for modeling
- Matplotlib and Seaborn for plotting
- Keras
- gensim

