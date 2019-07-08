# Naive Bayes Classifier on SMS Spam dataset
## Goal:  Train a Naive Bayes model to classify future SMS messages as either spam or ham.

Steps:

1.  Convert the words ham and spam to a binary indicator variable(0/1)

2.  Convert the txt to a sparse matrix of TFIDF vectors

3.  Fit a Naive Bayes Classifier

4.  Measure your success using roc_auc_score
