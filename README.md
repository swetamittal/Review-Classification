# REVIEWS CLASSIFICATION

## Description:

The project aims on sentiment analysis on movie reviews using Python and Natural Language Toolkit (NLTK). Sentiment Analysis means analyzing the sentiment of a given text or document and categorizing the text/document into a specific class or category.

This project focuses on classifying the given movie reviews into two categories namely positive and negative.The positive reviews are the reviews in the appreciation of the movies while the negative ones contains its drawback according to the viewers.
A total of 2000 movie reviews are taken into account and both the categories are equal in number i.e. 1000 positive reviews and 1000 negative reviews. The reviews are divides into sets: one used for training the classifier and one used to test its performance. Before feeding to the classifier, the reviews need some cleaning step first to remove the undesirable information form it. This  task is done using NLTK. After this is over, NaiveBayesClassifier of NLTK is used to train the classifier.
Further, the prepared training set is used to train other classifiers as well for comparing the performance.
