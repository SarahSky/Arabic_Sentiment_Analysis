
# Arabic Sentiment Analysis
Sarah Alsubhi

## Abstract
The goal of this project was to use classification models to predict the sentiment of Arabic tweets considering emojies using different models. I worked with data provided by [Motaz Saad](https://www.kaggle.com/mksaad/arabic-sentiment-twitter-corpus)  and word embedding features along with machine learning and deep learning models to achieve promising results for this binaryclass problem. 

## Design
This project originates from the [DrivenData competition](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/) "Pump it Up: Data Mining the Water Table". The data is provided by [Taarifa](http://taarifa.org/) and the Tanzanian Ministry of Water, and presents a three-class operational status of **functional**, **functional needs repair**, and **non-functional** for waterpoints across the country. Classifying statuses accurately via machine learning models would enable the Tanzanian Ministry of Water to take action to improve operations and maintenance planning of these units, allocate resources more quickly to needed areas, and ensure potable water is accessible to as many people as possible.

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

