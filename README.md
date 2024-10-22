# Logistic-Regression-Titanic-Survival-Prediction

=> Introduction
- This project utilizes machine learning techniques, specifically logistic regression, to analyze and predict passenger survival from the Titanic disaster. The primary goal is to explore the relationships between different features and passenger survival and build a predictive model with acceptable accuracy.

=> Project Workflow

1. Data Loading and Cleaning:
- Load the dataset and perform basic exploratory data analysis (EDA).
- Check for null values and handle missing data (fill missing Age with mean, Embarked with mode, and drop Cabin due to high null values).
- Convert categorical columns (Sex, Embarked) to numerical values for modeling.

2. ploratory Data Analysis (EDA):
- Analyze survival distribution, class distribution, and survival rate by gender and class using count plots.
- Summarize key statistics using describe().

3. Model Building:
- Split the data into training and testing sets (80% train, 20% test).
- Use LogisticRegression from Scikit-learn to train the model.

4. Model Evaluation:
- Evaluate the performance of the model on both the training and testing data using accuracy scores.
- Training Accuracy: 80.48%
- Testing Accuracy: 80.44%

=> Conclusion
- This project demonstrates the basic steps of building a machine learning model using logistic regression. The model predicts the likelihood of survival of Titanic passengers based on multiple features. Further improvements can be made by tuning the model, exploring more advanced algorithms, and performing feature engineering.

=> Contact Us

1. Email: uttamsojitra.ds@gmail.com

2. LinkedIn: https://www.linkedin.com/in/uttam-sojitra-6aa781236/

Feel free to reach out for any collaboration, job opportunities, or project discussions!
