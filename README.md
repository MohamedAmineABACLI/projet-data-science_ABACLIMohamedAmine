# projet-data-science_ABACLIMohamedAmine

Titanic Survival Prediction

This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques.

Getting Started

The first step is to download the Titanic dataset from Kaggle (https://www.kaggle.com/c/titanic/data) and extract the files into a directory named data. The dataset contains a training set and a test set in CSV format.

Prerequisites

This project requires Python 3 and the following libraries:

pandas
numpy
sklearn
xgboost

You can install these libraries using pip:

Copy code
pip install pandas numpy scikit-learn xgboost

Data Preparation

The data preparation process involves loading the dataset into memory, exploring the data, and cleaning it.

The data exploration step involves checking for null values and understanding the distribution of features in the dataset.

The data cleaning step involves filling in missing values, transforming categorical variables, and removing irrelevant features.

The data is then split into a training set and a testing set for model evaluation.

Model Selection

The model selection step involves evaluating the performance of different machine learning algorithms on the training set using cross-validation.

The following models were evaluated:

Logistic Regression
Decision Tree
Random Forest
SVM
XGBoost
Gradient Boosting Classifier
AdaBoost Classifier

The model with the highest accuracy score on the cross-validation set was selected for further evaluation.

Model Evaluation

The selected model was trained on the entire training set and evaluated on the testing set.

The evaluation metrics used were accuracy, precision, recall, and F1 score.

Prediction and Submission

The final step is to generate predictions for the test set using the selected model and create a submission file for Kaggle.

The submission file contains the PassengerId column and the predicted survival values.

Conclusion

This project demonstrates the process of building a machine learning model for survival prediction on the Titanic dataset. By following this process, it is possible to achieve high accuracy on the test set and create a submission file for Kaggle.
