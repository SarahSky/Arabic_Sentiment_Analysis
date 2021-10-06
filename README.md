# Arabic_Sentiment_Analysis
## Question/need:
### •	What is the framing question of your analysis, or the purpose of the model/system you plan to build?

This project addresses the problem of sentiment analysis on Twitter. The goal of this project is to predict sentiment for the given Twitter post using Python. Sentiment analysis can predict many different emotions attached to the text, but in this project, only two majors were considered: positive and negative. 

### •	Who benefits from exploring this question or building this model/system?

Sentiment analysis is a *kind of text mining*, which is to predict human mind, specifically the emotional state of a person by extracting specific emotional expressions from the text. Therefore, it can be useful for product reviews and predicting consumer attitudes towards new products.

## Data Description:
### •	What dataset(s) do you plan to use, and how will you obtain the data?

*Source: https://github.com/komari6/Arabic-twitter-corpus-AJGT*.

The dataset was collected to provide Arabic sentiment corpus for the research community to investigate deep learning approaches for Arabic sentiment analysis.
This dataset we collected in April 2019. It contains 58K Arabic tweets (47K training, 11K test).
### •	What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with? If modeling, what will you predict as your target?

The Arabic tweets annotated in positive and negative labels. The dataset is balanced and collected using positive and negative emojis lexicon.

#### Features:
1. Length of tweets
2. Number of words count
3. Number of characters
4. Number of sentences
5. Average words length
6. Average sentence length.
7. Word embedding
## Tools:
### •	How do you intend to meet the tools requirement of the project?
* Pandas: to Explore and download the Text data files.
*	Numpy
*	Matplotlib
*	Sklearn :  is a machine learning library 
### •	Are you planning in advance to need or use additional tools beyond those required?
* NLTK  is a NLP library.
