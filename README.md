# Kaggle-RedHat-Challenge

https://www.kaggle.com/c/predicting-red-hat-business-value

the challenge is to create a classification algorithm that accurately identifies which customers have the most potential business value for Red Hat based on their characteristics and activities.

the approach used here is based on :

*Feature selection using SelectFromModel method after fitting a RandomForestClassifier(sklearn) from 41 to 9 features

*10 fold(Stratified) Cross validation on reduced input using linear/non linear classification models scored on AUC-ROC metric

*Hyperparameter Tuning through GridSearchCV on XGBoost Classifier(sklearn)

Public Score on kaggle 0.962

Private Score on kaggle 0.958

Best Score on kaggle 0.995
