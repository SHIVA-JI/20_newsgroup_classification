# E-mail spam filtering
In this machine learning project I used a sms dataset file name as "sms.tsv" and created a ml model for Email spam filtering.
Also in this i applied two algorithms "Naive Bayes" and "Logistic Regression" to compare that which gives best accuracy score there are some following steps that I used -:
1- Load dataset-: Import dataset using pandas 
2- Cleaned and prepared dataset-: remove unncessary text from the imported dataset for further use
3- Transform text into Numeric-: Did feature extraction using count vectorizer from dataset
4- Train model-: I trained my model first on Naive Bayes algorithms which gives precision score 92.10 % then on Logistic Regression which gives preciosion Score of only 90% so hence result is that naive bayes is good than logistic regression for text classification
5- Evaluated my model-: after my model is trained i passed new text , cleaned it and then applied model which classifies data sucessfully.


# 20_newsgroup_classification
In this project I created a machine learning model in which classify the given news group dataset for different lables.
dataset is imported from "sklearn.dataets" dataset name is "fetch_20newsgroups"
1- Load dataset from sklearn.datasets named as fecth_20newsgroups datset and divided in test and train part
2- Feature extraction using count vectorizer
3- Applied naive bayes algorithm as it has good precision and accuracy score for text classification and get accuracy score of 98.19% and precision score 98.17%
then tested my data on a new data input which classified correctly.
