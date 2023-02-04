# 💰 Bank Loan Eligibility Prediction

[![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)](https://www.python.org) [![](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/) [![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org) [![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org) [![](https://img.shields.io/badge/Matplotlib-007cb1?style=for-the-badge&logo=matplotlib&logoColor=white)](https://matplotlib.org/)

![loan-bank](https://user-images.githubusercontent.com/76781033/216749170-048091af-8734-43e9-ad1c-88e5d9073eaf.jpg)

## TABLE OF CONTENTS

* [Introduction](#introduction)
* [Objectives](#objectives)
* [Tools and Packages](#tools)
* [Results](#results)
* [Conclusion](#conclusion)
* [References](#references)
* [Challenges and Future Work](#challenges-and-futurework)

### Introduction
The loan approval process is a challenging task for any financial institution. Before giving credit loans to borrowers, the bank decides whether the borrower is bad (defaulter) or good (non-defaulter). This project focuses on developing Machine Learning (ML) models to predict loan eligibility, which is vital in accelerating the decision-making process and determining if an applicant gets a loan or not.

Dream Housing Finance company deals in all home loans. They have a presence across all urban, semi-urban, and rural areas. Customer-first applies for a home loan after that company validates the customer eligibility for a loan.

The company wants to automate the loan eligibility process (real-time) based on customer detail provided while filling the online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and others. To automate this process, they have given a problem to identify the customer's segments, those are eligible for loan amount so that they can specifically target these customers.

### Objectives
- Analyze customer data provided in data set (EDA)

- Build various ML models that can predict loan approval

### Tools
<table style="width:100%">
  <tr>
    <th>Task</th>
    <th>Technique</th> 
    <th>Tools/Packages Used</th>
  </tr>
  <tr>
    <td>Data Collection</td>
    <td>Using dataset available in Kaggle </td> 
    <td></td>
  </tr>
  <tr>
    <td>Data Cleaning</td>
    <td>Drop unwanted columns, add new columns, deal with missing values</td> 
    <td>pandas</td>
  </tr>
  <tr>
    <td>Data Visualization</td>
    <td>Multi-attribute plots</td> 
    <td>matplotlib, seaborn</td>
  </tr>
  <tr>
    <td>Data Preprocessing</td>
    <td>Feature Encoding, Feature Engineering (deal with ouliersa and imbalanced data), Feature Scaling (Normalization data)</td> 
    <td>sklearn (LabelEncoder, SMOTE, MinMaxScaler), pandas (get_dummies), numpy(log)</td>
  </tr>

   <tr>
    <td>Data Modeling</td>
    <td>Supervised Machine Learning Models using Logistic Regression and Random Forest</td> 
    <td>sklearn </td>
  </tr>
  <tr>
    <td>Environments & Platforms</td>
    <td> </td> 
    <td>Jupyter Notebook, Kaggle</td>
  </tr>
</table><br>

### Results

Below are some key insights that were generated as a result of exploratory data analysis (EDA).
- The one whose salary is more can have a greater chance of loan approval.
- The one who is graduate has a better chance of loan approval.
- Married people would have a upper hand than unmarried people for loan approval .
- The applicant who has less number of dependents have a high probability for loan approval.
- The lesser the loan amount the higher the chance for getting loan.
- Better credit history will have the higher chance of loan approval.

Below are the machine learning models used for predicting whether a bank loan is approved or not. 

| __Machine Learning Models__| __Accuracy__| __Precision__|__Recall__| __AUC Score__|
| :-:| :-:| :-:| :-:| :-:|
| [__1. Logistic Regression__](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)| 0.83 | 0.81 | 0.98 | 0.72 |
| [__2. Random Forest Classifier__](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)| 0.79 | 0.81 | 0.92 | 0.75|









