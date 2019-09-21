# Unstructured-data-classification
Classifier for some sentence corpuses
# Problem statement
1. Extract and load files ‘labeled_articles’,. Each line contains
the label and the statement.
2. Classify the corpus into given labels.
3. Incorporate the below:
a. CountVectoriser -
http://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountV
ectorizer.html
b. kfold crossvalidation:
http://scikit-learn.org/stable/modules/generated/sklearn.model_selection.KFold.html
c. Classifiers:
 DecisionTreeClassifier
 SGDClassifier
 SVC
 SVC
 KNeighborsClassifier
 OneVsRestClassifier(svm.LinearSVC())
 RandomForestClassifier
 MultinomialNB -
http://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.Multinomial
NB.html
d. classification_report
e. Save the classifier model with highest accuracy – Predict using saved model -
http://scikit-learn.org/stable/tutorial/basic/tutorial.html
