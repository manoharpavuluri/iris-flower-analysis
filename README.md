# About the data

This is a generic data about Iris flower. Data is a copy of data from sklearn

# Whats special about this analysis

Unlike other ML analysis, in this multiple below models were evaluated to find the best model

- Logistic Regression (LR)
- Linear Discriminant Analysis (LDA)
- K-Nearest Neighbors (KNN).
- Classification and Regression Trees (CART).
- Gaussian Naive Bayes (NB).
- Support Vector Machines (SVM).
- XGBClassifier (XGBoost).

# Analysis

Data was straight forward so no data engineering methods were applied.

Once above models were applied, Accuracy score and Cross Validation were calculated 

- <b>LogReg</B>\
Accuracy: 83.33%. \
Cross Validation Results Mean: 0.941667. \
Cross Validation Results STD: 0.065085. 

- <b>LnrDisAnal</B>\
Accuracy: 100.00%. \
Cross Validation Results Mean: 0.975000. \
Cross Validation Results STD: 0.038188. 

- <b>KNN</B>\
Accuracy: 100.00%. \
Cross Validation Results Mean: 0.958333. \
Cross Validation Results STD: 0.041667. 

- <b>DecTreeClass</B>\
Accuracy: 96.67%. \
Cross Validation Results Mean: 0.933333. \
Cross Validation Results STD: 0.050000. 

- <b>GausNB</B>\
Accuracy: 96.67%. \
Cross Validation Results Mean: 0.950000. \
Cross Validation Results STD: 0.055277

- <b>SVM</B>\
Accuracy: 96.67%. \
Cross Validation Results Mean: 0.983333. \
Cross Validation Results STD: 0.033333. 

- <b>XGB</B>\
Accuracy: 96.67%. \
Cross Validation Results Mean: 0.958333. \
Cross Validation Results STD: 0.041667. 
\
Based on above, LDA comes out to be best model to go for prediction. 

Visualizing Predicted VS Real Plot using LDA

<img src="https://github.com/manoharpavuluri/iris-flower-analysis/blob/master/photos/CV_plt.png" height="400" width="500">

