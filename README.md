# Credit_Risk_Analysis



We are testing the risk of credit cards using machine learning in this challenge. This challenge consists of 4 deliverables with 3 technical part and an overview of the oroject.

After trying different models, the results is tested using a logistic regression. Also Easy Ensemble Classifier and Balanced Random Forest is used in this analysis.


## RESULTS:


* The Native Random Oversampling algorithm produced a balanced accuracy score of 0.65, a precision score of 0.01 and recall score of 0.69.

* The balanced Random Forest Classifier produced a balanced accuracy score of 0.79, a precision of 0.03, and a recall of 0.7.

* The Easy Ensemble Classifier produced a balanced accuracy score of 0.93, a precision of 0.09, and a recall of 0.92.




## SUMMARY:


All the models that is tested in this challenge were so sensetive and resulted in poor precision scores.
The most effective model was Easy Ensemble with a precision score of 0.09 and a recall of 0.92; however, its low precision caused Easy Ensemble model to predict more than ten times as manay false positives as true positives.
It is really hard to recommend any of these models as appropriate for predicting credit risk because of poor precision scores.

