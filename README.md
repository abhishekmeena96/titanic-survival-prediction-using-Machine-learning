# titanic-survival-prediction-using-Machine-learning

Project Overview: Titanic Survival Prediction
This project aims to predict the survival of Titanic passengers based on various features like age, gender, class, etc. You used the popular Titanic dataset, handled missing values, and applied logistic regression for the prediction.

Steps Involved:
Libraries and Tools:

Libraries used: Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.
These were used for data preprocessing, visualization, and model building.
Data Understanding:

The dataset consists of features such as PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, and Embarked.
Key features influencing survival include:
Sex (whether the passenger was male or female).
Pclass (passenger class: 1st, 2nd, or 3rd).
Age, Fare, and SibSp (number of siblings/spouses aboard).
Data Cleaning & Preprocessing:

Missing Values Handling:
Missing values in Age were filled using appropriate imputation (mean/median).
Cabin, having many missing values, was ignored or filled with a placeholder.
Missing values in Embarked were filled with the most frequent value.
Label Encoding:
Categorical columns such as Sex and Embarked were encoded numerically using LabelEncoder.
Exploratory Data Analysis (EDA):

Visualized relationships between different features and survival rates using Seaborn and Matplotlib.
Observations:
Higher survival rates for females compared to males.
First-class passengers had higher chances of survival.
Younger passengers and those with higher fares had better survival odds.
Modeling:

Logistic Regression was used to predict the binary target (Survived).
Train-Test Split: The dataset was split into training and testing sets using train_test_split.
The model was trained on the training data and evaluated on the test data.
Model Performance:

Accuracy Score: 0.7877 (78.8% of the predictions were correct).
Precision Score: 0.8475 (high precision indicates that most of the positive predictions were correct).
Recall Score: 0.6329 (showing the model's ability to correctly identify actual survivors).
Evaluated using confusion matrix, F1 score, and classification report.
Insights:

Features like Sex, Pclass, and Age had the highest influence on survival.
Logistic regression provided a solid baseline for predicting survival, but there is potential for improving the model by testing with other algorithms or adding more refined features.
