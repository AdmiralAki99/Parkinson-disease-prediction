README for G52
------------------

Our project relies mainly on numpy, pandas, matplotlib, sklearn, seaborn, eli5, skopt, lightgbm, catboost, xgboost, mlxtend.
Open the command, and navigate to the project folder, run
*** pip install -r requirements.txt *** to install all required packages

Our code submission contains the following files:

parkinson-disease_prediction.ipynb                   <-- script to run the main program
requirements.txt                                                 <--  text file for installing required packages
parkinson-disease_prediction.html                     <-- html file for the codes and results
dataset/parkinsons.csv                                        <-- row data set

* GPU is not required
* Traning takes about 1.5~2 hours

The parkinsons data downloaded from https://archive.ics.uci.edu/ml/datasets/Parkinson%27s+Disease+Classification#

Primary Architecture of program:
1. Data loading
    1.1 Extract features and labels
    1.2 Show the summary statistics
    1.3 Split samples to training dataset and test dataset

2. Data Processing
    2.1 Data preprocessing - Standard scale
    2.2 Feature selection

3. Guassin Naive Bayes

4. GridSearchCV on LogisticRegression

5. GridSearchCV on SVM

6. GridSearchCV on KNN

7. BayesSearchCV on ExtraTress classifier

8. GridSearchCV on AdaBoost classifier

9. BayesSearchCV on XGBoost classifier

10. GridSearchCV on CatBoost classifer

11. BayesSearchCV on LightGBM classifier

12. Grid Search on MLP classifer

13. Summary
      13.1 Determine the best classifier with its parameters
      13.2 Determine the most import features that affect Parkinson's disearse