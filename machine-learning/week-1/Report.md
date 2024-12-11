
# Task 1

1 . First, I found a dataset on kaggle related to credit card fraud. link for the dataset : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data

2 . Cleaned the data for null and duplicate data points.

3 . Scaled the Time and Amount Columns.

4 . Applied SMOTE on the dataset to reduce imbalance between classes

5 . Then used multiple models and analysed their performance on accuracy and on their confusion matrix

Models used  : 

Logistic Regression

                   pre       rec       spe        f1       geo       iba       sup

          0       0.91      0.97      0.90      0.94      0.93      0.87       120
          1       0.96      0.90      0.97      0.93      0.93      0.86       105
         avg      0.93      0.93      0.93      0.93      0.93      0.87       225


Random Forest Classifier

                   pre       rec       spe        f1       geo       iba       sup

          0       0.89      0.97      0.87      0.93      0.92      0.85       120
          1       0.97      0.87      0.97      0.91      0.92      0.84       105
        avg       0.93      0.92      0.92      0.92      0.92      0.85       225

XGBoost

                   pre       rec       spe        f1       geo       iba       sup

          0       0.90      0.92      0.89      0.91      0.90      0.81       120
          1       0.90      0.89      0.92      0.89      0.90      0.81       105
        avg       0.90      0.90      0.90      0.90      0.90      0.81       225

LightGBM

                   pre       rec       spe        f1       geo       iba       sup

          0       0.91      0.97      0.90      0.94      0.93      0.88       120
          1       0.97      0.90      0.97      0.93      0.93      0.87       105
        avg       0.94      0.94      0.93      0.94      0.93      0.87       225

Neural Network using Keras

                   pre       rec       spe        f1       geo       iba       sup

          0       0.92      0.97      0.90      0.94      0.94      0.88       120
          1       0.96      0.90      0.97      0.93      0.94      0.87       105
        avg       0.94      0.94      0.93      0.94      0.94      0.87       225

