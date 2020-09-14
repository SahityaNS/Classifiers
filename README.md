# CLASSIFICATION

It is a surpervised learning method, where classification is made when we already know the different outcomes and classify the given input accordingly. The aim is to predict the group to which the current object under observation belongs to.

## 1. Logictic Regression
![example](https://user-images.githubusercontent.com/58341480/93097135-ceb0c100-f6c2-11ea-8430-1001187be4af.png)
* It is used for binomial classification i.e., it gives an output of 0 or 1.
* It measures the relationship between the dependent variable and independent variables by estimating the probabilities using the logistic function.
* These probabilities must then be transformed into binary values in  order to make the prediction.
* These values are transformed into 0 or 1 using a threshold classifier.
### Sigmoid function
  It is an S shaped curve that can take any real valued  number and map it into a value between the range of 0 and 1
* Logistic regression gives a discrete outcome but linear regression gives a continuous outcome.

## K Nearest Neighbours
![KNN](https://user-images.githubusercontent.com/58341480/93097130-cce6fd80-f6c2-11ea-9807-b43d8f91cd58.png)
* It is a simple yet most used classification algorithm.
* It doesnot make any assumption on the data given.
* There are 3 key elements in this approach they are
  1. input data
  2. distance between the objects
  3. K value
* To classify an unlabelled object, the distance of this object to the labelled objects is computed.
* Its K nearest neighbors are identified and the class label of the majority of nearest neighbors is then used to determine the class label of the object.
* The distance used here is mostly Euclidean distance.

## SVM
![SVM](https://user-images.githubusercontent.com/58341480/93097117-c9537680-f6c2-11ea-8526-982650f2e459.png)
![Kernaall SVM](https://user-images.githubusercontent.com/58341480/93097122-ca84a380-f6c2-11ea-9434-50c51c73c612.png)
* It is a supervised machine learning algorithm.
* In this algorithm, we plot each data item as a point in n-dimensional space(where n is the no.of features) with the value of each feature being the value of a particular coordinate
* Classification by finding the hyperplane.
* For SVM, the best hyperplane is the one whose distance to the nearest element of each tag is the largest.
### Key elements
* Kernal
* Regularization
* Margin

## Naive Bayes
  
  


