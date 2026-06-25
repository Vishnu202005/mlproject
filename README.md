# 🎓 Student Performance Prediction

## 📌 Overview

This project is an end-to-end Machine Learning application that predicts a student's **Mathematics Score based on academic and demographic information.

The application is built using **Python**, **Flask**, and **Scikit-learn**, and is deployed on **AWS Elastic Beanstalk** with **AWS CodePipeline** for continuous deployment.

## 🌐 Live Demo

Try the deployed application here:

**Application URL: **http://studentperformance-env.eba-9bdkr6fb.us-east-1.elasticbeanstalk.com/prediction

WE can enter the required student information and receive the predicted Mathematics Score instantly.

---

## 🚀 Features

* Student performance prediction
* Interactive Flask web application
* Data preprocessing and feature engineering
* Model training and evaluation
* AWS Elastic Beanstalk deployment
* CD using AWS CodePipeline

---

## 🛠️ Technologies Used

* Python
* Flask
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* CatBoost
* AWS Elastic Beanstalk
* AWS CodePipeline
* GitHub

---

## 📊 Model Selection

Several regression models were trained and evaluated using the R² Score.

| Model                   | R² Score     |
| ----------------------- | ------------ |
| Ridge Regression        | 0.880593     |
| Linear Regression       | 0.880433     |
| CatBoost Regressor      | 0.851632     |
| Random Forest Regressor | 0.851463     |
| AdaBoost Regressor      | 0.849450     |
| XGBoost Regressor       | 0.827797     |
| Decision Tree Regressor | 0.742622     |

Although Ridge Regression achieved the highest R² score, **Linear Regression** was selected as the final model because 
the performance difference was negligible while providing a simpler and more interpretable solution.

---

## 🎯 Input Features

The model uses the following features:

* Gender
* Race_Ethnicity
* Parental Level of Education
* Lunch Type
* Test Preparation Course
* Reading Score
* Writing Score

---

## 📈 Output

* Predicted Mathematics Score


## ☁️ Deployment

The application is deployed using:

* AWS Elastic Beanstalk
* AWS CodePipeline
* GitHub
