<h1 align="center">🚗 Car Repurchasing Predictor 📈</h1>

<h2 align="center">Predicting Future Car Owners! 🚘</h2>

## 🚀 Introduction
Welcome to our Car Repurchasing Predictor project! 🎉 Our mission is to build a classification model that identifies customers most likely to repurchase a car. Using various features like gender, age, car model, and more, we've explored different approaches to tackle this challenge.

## 🌐 Business Objective
In the realm of business, customer retention is gold! ✨ The company aims to boost customer loyalty by targeting potential second-time car buyers with tailored marketing strategies, follow-up calls, and personalized services. Our ideal model has a good recall score and a robust precision score to optimize resource allocation.

## 📊 Data Insights
Our dataset boasts 17 diverse features, including gender, age groups, car models, and more. The 'Target' variable distinguishes repurchasers (1) from non-repurchasers (0). Notably, our data is imbalanced, with repurchasers being a tiny fraction.

## 🔧 Data Prep
Our data prep recipe:
1. Drop 'ID' for overfitting.
2. Remove duplicates.
3. Address car model segment inconsistencies.
4. Map age_band and gender to numbers.
5. One-hot encode categorical data.
6. Concatenate numerical and categorical data.
7. Impute missing values with KNN.
8. Round missing data to the nearest integer.

## 🤖 Modeling
Our toolkit:
1. Logistic Regression with SMOTE for balance.
2. K-Nearest Neighbors Classification with ENN sampling.
3. Decision Tree Classifier with hyperparameters.
4. Random Forest Classifier with tuned parameters.
5. Random Forest Classifier with GridSearchCV optimization.

## 📈 Evaluation
Test set recall scores:
- Part 1: 0.80 (Caution: paired with low precision)
- Part 2: 0.54
- Part 3: 0.75
- Part 4: 0.73
- Part 5: 0.59

**Model 3** shines, with a 75% true positive rate, aligning perfectly with our business goal.

## 🚀 Deployment
Our model is set to deploy as Python code, serving marketing and retail sectors. Car sales companies, insurers, and others can harness its power to identify potential repurchasers based on first purchase features, thereby customizing marketing strategies. It's especially adept at handling skewed data scenarios.

## 📚 References
We extend thanks to MLAA for templates and guidance.
