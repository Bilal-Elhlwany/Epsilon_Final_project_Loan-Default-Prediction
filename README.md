# Epsilon_Final_project_Loan-Default-Prediction
Its the final project related to Data Science Diploma in EpsilonAI

![1_f7m92eei7PE8gFyaCQnXMw](https://github.com/Bilal-Elhlwany/Epsilon_Final_project_Loan-Default-Prediction/assets/100938358/dacd2a09-d7e2-47f9-8f7c-050e385ace91)

**✔️ Problem Formulation:**

* Define the problem. What is the input? What is the output? What data analysis function is required? What could be the challenges?What is an ideal solution?

**Define the problem**

`The problem related to the loan default dataset is to build a predictive model that can accurately predict whether a loan applicant is likely to default on their loan payments or not, based on a set of input features.`

**What is the input?**

`The input to the model is a set of features for each loan applicant, such as their credit score, income, employment status, loan amount, and other relevant information.`

**What is the output?** 

`The output of the model is a binary prediction of whether the loan applicant is likely to default or not.`

**What data analysis function is required?**

* Data Cleaning or Cleansing 
    * 1) Import the required Python libraries
    * 2) Read Data
    * 3) Some feature engineering
    * 4) Data Preprocessing
    
`In this step we need to clean the data to make it ready for any type of model classification`

* Data Split to Train and Test Sets
* Data Preprocessing Project – Feature Scaling
* Models that will be used:

   1) **Logistic Regression(LogR) Model** 
   
   2) **Support vector machine(SVC) Model**
   
   3) **k-nearest neighbors(KNN) Model**
   
   4) **Random Forest(RF) Model**
   
   4) **DecisionTree(DT) Model**
   
   4) **GaussianNB Model**

`A binary classification function Will be used`

**What could be the challenges?**
* `We should select best classifier for classify more accurate` 
* `The challenges are to clean the data by Preprocessing techniques to make the data pure to predict correctly and choose best classifier for this mission. to increase model performance and the accuracy of machine learning models are affected because of poor quality of data, are considered to be challenging.`
* `The real dataset never comes clean. It consists lot of discrepancies in the dataset. So, we have to clean the dataset for further processing.`
* `Some challenges related to this dataset include missing values in some features and imbalanced classes in the target variable`
   
**What is an ideal solution?**

`The ideal solution is getting high accuracy for predict which accept or refused loan,and which model perfect to train input data are (GaussianNB Model, Random Forest(RF), DecisionTree(DT))`

# <a id="1">What Loan Default Prediction?</a>
* Loans are an essential part of our economy.People borrow money from financial institutions all the time, either for starting a business, emergency expenses, vehicle financing, vacation costs, or education costs.

* However, when lending money to someone, there is always the risk that that person may not be able to pay you back. When it comes to financial institutions, such as banks, that borrow large amounts of money to many different people for many different reasons, the risk of losses from defaults gets exponentially higher.

* For this reason, it is extremely important that financial institutions avoid loans to people that are highly likely to default, and they usually invest a lot of time and resources in background checks on people to avoid having losses. In this notebook, I'll develop a machine learning model that will be able to predict how likely a client is to default based on whether or not he's employed, his bank balance, and his annual salary..

![download](https://github.com/Bilal-Elhlwany/Epsilon_Final_project_Loan-Default-Prediction/assets/100938358/d917f1b8-56af-4b8c-bda3-b9ef8752eff5)
