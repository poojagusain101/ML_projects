
**Credit Card Fraud Detection**

Fraud can be detected in various forms and one of the major forms of it is credit card fraud. Earlier these frauds were detected by human-proposed patterns and rules to rely upon. This was time-consuming as well as the accuracy level of detecting fraud was unmonitored and was incapable of detecting a new fraud pattern.

The ML model will be trained on the dataset so as to detect real-time fraud patterns. This will reduce the time consumption as well as the accuracy level of the model will be defined and could be refined over time. Since the label consisted of only 2 predictable values 0 and 1, it comes under binary classification and hence, the model was developed based on Logistic Regression.

**Dataset:**

The dataset was taken from Kaggle for building the model:

https://www.kaggle.com/code/bannourchaker/frauddetection-part1-eda/input

**Libraries:**

* Numpy
* Pandas
* Matplotlib
* Sklearn
* Seaborn



**Workflow:**

* Data Collection
* Exploratory Data Analysis
* Pre-Processing
* Modeling

  The dataset was split into a ratio of 7:3 for train and test dataset and non-randomization of train and test values was set. We then observed the shape of         features for train and test set and the for the labels of test and train.
  removed the imbalance in the train dataset by using SMOTE and then observed if the dataset was balanced or not for fraudulent and non-fraudulent values.
* Logistic Regression
 
  proceeded to fit the training dataset into the logistics regression model and then observed the precision, recall and f1-score of the model.
* Optimal Result of the model

  created a confusion matrix for the evaluation on the model
  Later, recorded the f1-score , accuracy score, MSE(mean square error) and recall score for the predictions that were made by the model




