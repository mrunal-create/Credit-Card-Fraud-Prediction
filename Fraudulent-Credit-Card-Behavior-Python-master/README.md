# Credit_Card_Fraud_Detection_Project
* The aim of this project is to predict whether a credit card transaction is fraudulent or not, based on the transaction amount, time and other transaction related data. 
* It aims to track down credit card transaction data, which is done by detecting anomalies in the transaction data. 

**Objective** is to predict whether the instance of a credit card transaction is fraudulent or valid

**Creator**: Anandan Raju
![MIT-Fraud-Detection](https://user-images.githubusercontent.com/110320717/195913923-869b91ad-89dd-4f91-9d9e-f601a15c8069.jpg)

> Credit card fraud detection is typically implemented using an algorithm that detects any anomalies in the transaction data and notifies the cardholder (as a precautionary measure) and the bank about any suspicious transaction.

**To avoid misuse of data, the dataset has been masked. Hence we are unable to explain columns V1 to V28. All the columns between V1 to V28 are used as independent variable**

The other two independent columns are **Amount** and **Time**.
* **Time** indicates the time elapsed when the transaction was captured 
* **Amount** indicates the amount transacted.

**Target column is named as Class Number of categories in Class column is 2 (0 & 1)**

* **"0"** indicated as valid
* **"1"** indicated as fraud

**Synopsis**

1. Import Libraries
2. Reading Dataset
3. Checking Null Set
4. Exploring Dataset
5. Exploratory Data Analysis\
    5.1 Sampling Technique
6. Deterrmining Fraud Data Cases (finding Outliers)
7. Data Preprocessing\
    7.1 . Setting X and Y Variables\
    7.2. Splitting Train and Test DataSet
8. Model Analysis\
    8.1 Random Forest Classifier Model\
    8.2 Confusion Matrix\
    8.3 Determining Accuracy, Recall and Precision Score
