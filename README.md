# Credit-Card-Approval-Prediction-using-Machine-Learning
Built a machine learning model to predict if an applicant is 'good' or 'bad' client, different from other tasks, the definition of 'good' or 'bad' is not given. Using some Mechine Learning Algorithm modes for prediction to construct label. Also, unbalance data problem is a big problem in this sample data.

## Team size: 3, Course: Bigdata Warehouse(CS662)
Indira Priyadarshini, Ege Ozcan, and Katie Albany

## Problem
The financial industry has its own ways of assessing risk factors in order to come up with risk control methods. Credit card companies, as part of the financial industry, use credit scores to make decisions about consumer’s credit card applications. Specifically, credit card companies use applicant’s personal information and personal financial data to predict how probable future defaults and credit card borrowings are for consumer’s fitting a certain profile. Credit card companies use historical data and observable trends to make decisions regarding clients’ applications. One of the challenges that they face is to quantify risk in order to assess its magnitude and come up with prevention or mitigation methods.
Our project will analyze the available data and will try to find a good machine learning method for predicting credit card application approval.

## Python Libraries:
Numpy for handling arrays
Pandas for creating DataFrame
Sklearn for Machine Learning

## Mechine Learning Algorithms
1.     Decision Tree
By using this method, we will be breaking down the dataset into small pieces with decision nodes in a tree. As deep as the tree gets, the decision rules get more complex hence the algorithm learns better. So, we believe this may be a good model based on the initial observation we have based on the dataset.
 
2.     Random Forest
With this method, we will be using multiple decision trees. Since there is a lot of trees, it uses a lot of time to train the data which is correlated with its accuracy. In the end, it uses a majority voting and averaging to calculate the result. Since we do have multiple affecting factors, this may also be another useful method to further try.
 
3.     K Nearest Neighborhoods
It can help out to find the k most similar instances that consist in our training set. This method will help to find and explore which instances are similar to each other. This is unlikely to work as each factor is not similar to the other. KNN is mostly used for recommender systems like Netflix movie recommendation based on your history or Amazon shopping recommendations based on what you previously purchased.
 
4.     Support Vector Machines
SVM is built for both non-linear and linear models. Basically, there are hyperplanes that classifies the data points. The goal is to find the best plane with the max-margin and get the best accurate model. It works effectively with models that have a lot of dimensions. SVM works very well with classifying images as well as face recognition which is widely used on our phones nowadays.
 
5.     Naïve Bayes
This classification model helps us calculate the probability of the hypothesis. This means that we will need prior knowledge about the data. This model requires independence between the predictors which makes it questionable for our dataset as some of the dependent variables are probably depending on each other and are either negatively or positively correlated.
 
6.     Linear Regression
This method is the most common one as it is just the representation of y = mx + n in machine learning. It was developed in statistics and has simply been borrowed by machine learning as it became a useful method in this field also

