# Kaggle Titanic Competition

## Contents
1. About this project: Predicting Survival on Titanic
2. Installation

## 1. About this project: Predicting Survival on Titanic

- This project is a Kaggle project and the goal is to predict which passengers survived on Titanic based on their information.
Link to the official page for this project: https://www.kaggle.com/c/titanic
- There are two Jupyter notebooks in this repository named:
  - Titanic_ExploratoryAnalysis.ipynb
  - Titanic_Main.ipynb
- In the first one (Titanic_ExploratoryAnalysis.ipynb) we perform exploratory data analysis on the Titanic dataset
and look for general patterns or (engineered) features/categories that have a survival/death rate above 80%.
- In the second notebook (Titanic_main.ipynb) using varias pipelines we preprocess the data for machine learning based on the
patterns identified in the first notebook and train different machine learning models like Random Forests, Support Vector Machines,
Logistic Regression, Gradient Boosting Regressor, etc. We will see that the Support Vector Classifier produces the best prediction score.
- The final prediciton score obtained using the above steps is 79.425% which puts the submission in the top 10% on the public leaderboard.
## 2. Installation
- #### Requirements to run this project
  - Python 3 and Jupyter notebook need to be installed before running this project.
  - The python libraries used in this project are listed in the requirements.txt file and are as follows:
    - numpy
    - pandas
    - matplotlib
    - scikit-learn
  - You can install these libraries by running the following in a terminal application: pip install -r requirements.txt
- #### Download the data
  - Download the zip file containing this repository.
  - Unzip the file and get into the folder named: Kaggle_Titanic-master , via a terminal application.
  - Launch a Jupyter notebook and run the notebooks related to this project!
