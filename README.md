# Disaster-Tweet-Classification

# Problem Statement
Sentiment analysis on tweets to predict real vs metaphorical disasters.

# Dataset
Training set - 7503 tweets\
Test set - 3243 tweets\
Information available - ID, location, text, keyword, target of each tweet\
Word clouds to represent high frequency words in real disaster tweets

![image](https://user-images.githubusercontent.com/68511654/129452955-a81d2aeb-cb75-4ac3-be57-07396d3567a1.png)

Word clouds to represent high frequency words in metaphorical disaster tweets

![image](https://user-images.githubusercontent.com/68511654/129452963-1ec4f1f9-17b9-4260-b647-60da23d0411c.png)

# Methodolgy
Two approaches were followed for classification -
1. GloVe embeddings (glove.twitter.27B.50d.txt) followed by sequential LSTM classifier 
2. BERT Model Embeddings (small_bert/bert_en_uncased_L-8_H-768_A-12) followed by single dense layer.

# Results
Better performance was obtained by the BERT Model yielding a classification accuracy of **95.40%** comapred to 79.97% of the GloVe model.

# Requirements
Dataset can be downloaded from: https://www.kaggle.com/c/nlp-getting-started/data\
glove.twitter.27B.50d.txt can be downloaded from: https://www.kaggle.com/baodier/glovetwitter27b50dtxt\





