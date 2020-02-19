# Naive Bayes Classifier

This project implements the Naive Bayes classifier from scratch, in order to predict the diagnosis of diabetes in the diabetes dataset.

This project attempts to implement the Naive Bayes Classifier from scratch (with minimal to no use of pre-written libraries) as an excercise. The data is shuffled and split manually. All training & testing steps were done manually in order to deeply understand how probabilistic classifiers work. 

## Dataset
The diabetes data set consists of 768 data points, each having 9 features:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome (Label)

The original source of the data is [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/index.php). Download it from [here](https://github.com/susanli2016/Machine-Learning-with-Python/blob/master/diabetes.csv).


## Libraries
- [Numpy](https://numpy.org) was used in order to perform vector maths.
- [Pandas](https://pandas.pydata.org) was used to store & traverse tabulated data.
- [SKLearn](https://scikit-learn.org/stable/) was used to compare the results of this implementation of Naive Bayes with the SKLearn reference implementation.

## Implementation
**See [notebook](https://github.com/ANFALATAWI/NaiveBayesClassifier/blob/master/NaiveBayes_Classifier.ipynb)**.

## Conclusion
This project successfully implements the Naive Bayes classifier based on the theory, producing results that match the reference implementation of the SKLearn library.
