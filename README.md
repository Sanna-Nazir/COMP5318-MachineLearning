# COMP5318-MachineLearning
University Coursework for COMP5318: Machine Learning and Data Mining (Semester 2, 2019)

The assignments were completed as part of the COMP5318 unit of The University of Sydney by [Sanna Nazir](https://github.com/Sanna-Nazir), [Anshu Kumar](https://github.com/anshukr5) and [Samarth Sehgal](https://github.com/samarthsehgal97). There were two assignments undertaken. Details of each assignment are as follows:

1. [Assignment 1](https://github.com/Sanna-Nazir/COMP5318-MachineLearning/tree/main/Assignment_1):
	
The aim of this assignment was to compare different Machine Learning and Deep Learning algorithms **built from scratch**. To compare the models, the publically available 'Fashion MNIST Data' was taken. Various data pre-processing techniques like **standardization** and  **Principal Component Analysis** were used. Data Analysis was also done using python. The algorithms that were implemented and compared are:

    1. Naive Bayes Classifier
    2. Logistic Regression Classifier
    3. K-Nearesr Neighbours Classifier
    4. Neural Network Classifier
  
2. [Assignment 2](https://github.com/Sanna-Nazir/COMP5318-MachineLearning/tree/main/Assignment_2):

The purpose of this assignment is to evaluate various regressors for the prediction of forest fire affected area. Each regressor is evaluated on industry standard metrics such as Root Mean Square Error (RMSE) and Negative Log Likelihood (NLL) of the predicted results versus the actual test results. The data used for performing this task is the data collected by Cortez and Morais from the Montesinho Natural Park of Portugal. The same is publicly available on the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Forest+Fires). For the purpose of our project, we have chosen a wide variety of regression algorithms to cover variety of scenarios within the dataset. Reasons for the same may be discussed as under:

  1. **Linear Regression** is the classical choice for regression problems and thus, was included in the experiment process. It is chosen for its simplicity, ease of understanding, ubiquity and wide scientific acceptance.
  2. **Support Vector Regression** technique was employed for its ease of generalizing capabilities and high prediction accuracy.
  3. **K-Nearest Regression** technique is employed for its novelty, usability for non-linear data and relatively good accuracy.
  4. **Decision Trees Regressor** Method was used because of its comprehensive nature in tracing each outcome to its end. Thus, considering all possible outcomes for the data.
  5. **Random Forest** technique was employed to understand the impact of ensemble algorithms on our dataset. It’s known advantages of being reducing variance and over-fitting (such as in decision trees) were also consider while choosing the same.
  6. **Adaboost algorithm** was chosen to understand the difference of a boosting technique on the dataset (as compared to the bagging technique of Random Forest). Furthermore, Adaboost considers the combination of features by itself, something which would be manual in techniques like Linear Regression.
  7. **Neural Networks** were chosen for their ability to detect all possible interactions between the variables with least statistical pre-processing. We also wanted to analyze the success of a neural network over a regression task
