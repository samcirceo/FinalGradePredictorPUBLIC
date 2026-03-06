# Final Grade Predictor Overview

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/ScikitLearn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?logo=matplotlib&logoColor=white)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-4CAF50)


This project aims to predict students’ final grades in a math course using academic and lifestyle data. The goal is to identify students who may need additional support, allowing educators to implement targeted interventions to improve outcomes.

_This repository provides a high level overview of the project. The [complete project](https://github.com/samcirceo/FinalGradePredictor), including code and detailed results, is available in a private repository. If you would like access, please contact me with your GitHub username._

<p align="center">
  <img src="https://raw.githubusercontent.com/samcirceo/samcirceo/main/images/grades.jpeg" width="350">
</p>

### Overview of Project
- **Data Preparation**: Cleaned missing values, corrected data types, combined attendance features, encoded categorical and ordinal variables, and separated data into training and test sets
- **Exploratory Data Analysis**: Visualized relationships between grades and other features to identify key predictive features to use in the model
- **Feature Engineering**: created a **Custom Transformer** to combine student's absence from different semesters into one feature to use seamlessly in a pipeline
- **Create Pipelines**: Built automated preprocessing pipeline to handle numeric, categorical, and ordinal data consistently to ensure new student data can be transformed and fed into the model efficiently
- **Modeling**: Compared multiple regression models including **Linear Regression, Lasso Regression, Support Vector Regression**, and **Random Forest Regression**
- Finetuning: Performed a **Grid Search** to determine the best hyperparameters 
- **Evaluation**: Used **RMSE** and **R<sup>2</sup>** metrics to compare model performance

### Conclusions
- Previous semester grades are the strongest predictor of final grades and models using these features achieve high accuracy
- Predicting final grades without previous grades is more challenging and less accurate, highlighting the importance of early academic performance

_See the complete project for key insights, business reccomendations, & future improvements._

