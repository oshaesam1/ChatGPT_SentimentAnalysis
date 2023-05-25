# ChatGPT_SentimentAnalysis
 
Given the dataset of several tweets about ChatGPT where users post their opinions towards it.  which classifies each tweet into three classes (i.e., positive “good”, negative “bad”, or neutral) perform text classification ,building a classifier that can accept user comments (sentence) and outputs positive, neutral, or negative opinions.


### Dataset Preview:

|<img src="example/datasetExample.png">|
|:-:|


### Details of project:
- Applying the pre-processing steps which include “Tokenization,lemmatization" to clean up and extract the valid final dataset from your data, which will be used to train the model.
- Applying the concept of “word embeddings” to be one of the pre-processing steps while preparing  dataset.
- Spliting  dataset by 80 % - 20 %. The first 80 % will be used as training data for the classifier. While the other 20 % will be used as testing data for model to be able to 
identify the “accuracy percentage” of classifier

-  Training a classification model to predict the label of the tweet. Train with 2 Models (CNN, LSTM) each model train multiple times to optimize hyper parameters.
