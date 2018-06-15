# URL Classification

Algorithms used:

*	Multinomial naive bayes classifier
*	Logistic Regression classifier
*	Linear Support Vector Classification
*	Random forest classifier

The system is working only on Lexical features:

*	bag of words
*	additional text features


# results

on test set (20% of data)

Multinomial naive bayes classifier:

tn:252576 fp:1589

fn:630 tp:7344


Logistic Regression classifier:

tn:253161 fp:266

fn:45 tp:8667


Linear Support Vector Classification: (best)

tn:253167 fp:170

fn:39 tp:8763


Random forest classifier:

tn:253175 fp:294

fn:31 tp:8639


missclassified data saved in 'Missclassified' folder.