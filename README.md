# 📊 Supervised Learning Project Summary

[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue?style=for-the-badge)](https://www.python.org/)
[![GitHub](https://img.shields.io/badge/GitHub-Repo-orange?style=for-the-badge)](https://github.com/fursuf1/Credit-Card-Fraud-Detection)
[![Visual Studio Code](https://img.shields.io/badge/Editor-Visual%20Studio%20Code-green?style=for-the-badge)](https://code.visualstudio.com/)
[![git](https://badgen.net/badge/icon/git?icon=git&label)](https://git-scm.com)
[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)
[![Visual Studio Code](https://img.shields.io/badge/--007ACC?logo=visual%20studio%20code&logoColor=ffffff)](https://code.visualstudio.com/)
[![Windows](https://badgen.net/badge/icon/windows?icon=windows&label)](https://microsoft.com/windows/)

## 📝 Table of Contents
1. [Project Objectives 🎯](#project-objectives-)
2. [Project Process ⚙️](#project-process-)
3. [Project Results 📊](#project-results-)
    - [Exploratory Data Analysis and Feature Engineering 🌐](#exploratory-data-analysis-and-feature-engineering-)
    - [Machine Learning Model Training 🤖](#machine-learning-model-training-)
4. [Challenges 🛠](#challenges-)
5. [Future Considerations 🚀](#future-considerations-)

## 1. Project Objectives 🎯
In this supervised learning project, my primary objective was to leverage machine learning techniques to construct a predictive model capable of determining whether a patient has diabetes based on specific diagnostic measurements.

## 2. Project Process ⚙️
My project encompassed several key stages. It commenced with exploratory data analysis (EDA) and data preprocessing. The dataset used in the project was obtained from [Kaggle](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset), and I meticulously examined it. This process involved visualizing the relationships among different variables, addressing outliers and erroneous data, standardizing feature scales, and carrying out essential feature engineering when necessary.

Having completed the preliminary data preparation steps, I moved on to the machine learning model creation. My objective was to train models capable of predicting the presence or absence of diabetes. I employed various evaluation metrics, such as accuracy, precision, and recall, to assess the model's performance. Additionally, I ensured the inclusion of at least one ensemble model in my analysis to gauge its effectiveness.

## 3. Project Results 📊

### Exploratory Data Analysis and Feature Engineering 🌐
- During the EDA phase, I detected outliers, data imbalances, and incorrect values. Notably, some predictor variables had zero values, which I either removed or replaced with the median value.
- Feature scaling was carried out to address the variations in unit representation and magnitudes across different variables. This ensured fair and effective contributions from all features during the learning process.
- Feature selection, based on correlation with the target variable 'Outcome,' was performed to enhance model performance and interpretability by reducing complexity..

### Machine Learning Model Training 🤖
- I evaluated three distinct machine learning models: logistic regression, support vector machines, and random forest classifiers. My objective was to compare their performance.
- The model comparison considered evaluation metrics, including accuracy, precision, recall, F1-score, and ROC-AUC. A ROC-AUC plot containing all three models was examined, along with confusion matrices for each model.
- Surprisingly, the support vector machine (SVM) exhibited the best performance for this specific binary classification task, despite my initial expectation that the random forest classifier ensemble would excel.

## 4. Challenges 🛠
Several challenges were encountered during the project, including time constraints, decision-making regarding outlier and incorrect data handling, and the selection of the most suitable machine learning models for analysis.

## 5. Future Considerations 🚀
- Future work may involve exploring both feature selection approaches, including top correlated features and the utilization of all available features, to assess their impact on model performance.
- Hyperparameter tuning for the random forest ensemble model could be conducted to potentially enhance its performance.
- Consideration should be given to the incorporation of other machine learning models, such as XGBoost, for further analysis.
