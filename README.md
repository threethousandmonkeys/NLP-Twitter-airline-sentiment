# NLP-Twitter-airline-sentiment
Perform (unbalanced) binary classification on the tweets from airline passengers in US for six different airlines

<br>

**Project Objective:** The objective is to perform binary classification on the tweets from airline passengers in US for six different airlines. The classes are
1. **Neutral**
2. **Non-Neutral**

Originaly, the dataset contains three different classes, **you may have to merge the positive and negative class in a single class**.

**Dataset**: [Kaggle: Twitter US Airline Sentiment](https://www.kaggle.com/crowdflower/twitter-airline-sentiment)

This data set contains roughly 15K tweets with 3 possible classes for the sentiment (positive, negative and neutral). The data has been already cleaned from the original format, but you can further clean the data if it can increases the accuracy of the model. 

Workflow: start with basic model and then use pre-trained word embedding method such as word2vec, GloVe to compare the results.