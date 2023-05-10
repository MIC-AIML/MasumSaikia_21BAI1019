This project demonstrates how to use Scikit-learn's _Pipeline_ , _CountVectorizer_ , and _LogisticRegression_ to detect the emotions of a sentence. The dataset used for this project is the Emotion Recognition in Text dataset (EmoContext), which consists of text messages in English and their corresponding emotions (happy, sad, angry, and others). The goal of this project is to train a machine learning model that can accurately predict the emotions of new text messages.

This program will perform the following steps:

* Load the Emotion dataset into a Pandas DataFrame.
* Remove stop words.
* Split the dataset into a training set and a validation set.
* Define a Scikit-learn Pipeline that consists of a CountVectorizer transformer and a LogisticRegression estimator.
* Train the pipeline on the training data.
* Evaluate the performance of the pipeline on the validation data.
