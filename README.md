# 🚢 Titanic Survival Prediction - Data Science Project

<p align="center">
  <img src="https://github.com/Sangeetha-K-04/CodsoftTask2/blob/main/RMS_Titanic_3.jpg?raw=true" alt="RMS Titanic" width="400">
  <br>
  <i><b>RMS Titanic</b> — A legendary ship, now your launchpad into machine learning.</i>
</p>


## 🌟 Project Overview

Welcome aboard! This project is a data science journey into one of the most famous maritime disasters in history — the **Titanic sinking**. Our goal? To uncover the factors that influenced survival and **predict who survived** using powerful machine learning models.

Using Python, Pandas, Seaborn, and Scikit-Learn, this notebook delves into the **Titanic dataset** from Kaggle, performing **EDA (Exploratory Data Analysis)**, **data preprocessing**, and **modeling**. We visualize relationships, clean the dataset, and apply classifiers to forecast survival outcomes with clarity and accuracy.

---

## 🚀 Features

- 📊 **Comprehensive Data Exploration**  
  Visual analysis using seaborn and matplotlib to explore key survival factors.

- 🛠️ **Feature Engineering & Cleaning**  
  Smart transformations, imputation, and handling of missing values.

- 🧠 **Machine Learning Models**  
  Trained multiple classifiers to predict survival — Logistic Regression, Random Forest, and more!

- 📈 **Model Evaluation**  
  Metrics like accuracy, confusion matrix, and cross-validation to assess model performance.

---

## 📁 Folder Structure

```plaintext
📦 TitanicSurvivalPrediction
 ┣ 📜 TitanicSurvival.ipynb   ← Jupyter Notebook with full implementation
 ┗ 📄 README.md                ← You’re reading it!
```

---

## 📁 Dataset Used

We used the [Titanic dataset from Kaggle](https://www.kaggle.com/competitions/titanic) which includes:

- PassengerId, Name, Sex, Age
- Ticket, Fare, Cabin, Embarked
- Pclass (Passenger Class), SibSp, Parch
- Survived (Target Variable)

---
 ## 🧪 Technologies & Tools

| Tool/Library     | Usage                        |
|------------------|------------------------------|
| Python 🐍        | Core programming language     |
| Pandas 🧾         | Data manipulation             |
| NumPy ➗          | Numerical operations          |
| Matplotlib & Seaborn 📊 | Data visualization     |
| Scikit-learn 🤖   | Machine Learning models       |
| Jupyter Notebook 📓 | Interactive coding environment |

---

## 📊 Exploratory Data Analysis

Here are some key insights:

- **Women** and **children** had a higher survival rate.
- **First-class passengers** were more likely to survive.
- Passengers boarding from port **'C' (Cherbourg)** had a better chance of survival.

🧠 Feature engineering was done on:
- Title extraction from names
- Family size creation from SibSp & Parch
- Handling missing Age, Embarked, and Fare values smartly

---

## Sample output 
![Titanic Ship](./titanic.jpg)
