# Prediction-Assignment

John Hopkins' Data Science Machine Learning Project

##Introduction

Many people pay more attention on exercise's time rather than performance. Recently, there is a research about human activity recognition, which focused on discriminating between different activities. And this assignment is using Weight Lifting Exercises Dataset to predict different kinds of activities.

Data source and more information on the Human Activity Recognition's website: http://groupware.les.inf.puc-rio.br/har
Train Data: https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv
Test Data: https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv

##Steps

First, cleaning the dataset and removing the variables, which are almost near zero values. Then, removing variables which contain most of NA values. After that, using generalized boosted, random forest and tree-based prediction methods, and comparing their accuracies. Finally, I choosed random forest method to fit the model, and applied it into test set.

##Conclusions

By using random forest, this project successfully discriminated testset's activities.
