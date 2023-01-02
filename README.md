# Personal-Bank-Loan-Model

Dataset Overview

The file Bank.xls contains data on 5000 customers. The data include customer demographicinformation (age, income, etc.), the customer's relationship with the bank (mortgage, securitiesaccount, etc.), and the customer response to the last personal loan campaign (Personal Loan).Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was offered tothem in the earlier campaign.

Dataset Context

This case is about a bank (Thera Bank) whose management wants to explore ways ofconverting its liability customers to personal loan customers (while retaining them asdepositors). A campaign that the bank ran last year for liability customers showed a healthyconversion rate of over 9% success. This has encouraged the retail marketing department todevise campaigns with better target marketing to increase the success ratio with minimal budget

Description of Attributes

    ID : Customer ID

    Age : Customer's age in completed years

    Experience : #years of professional experience

    Income : Annual income of the customer ($000)

    ZIP Code : Home Address ZIP code.

    Family : Family size of the customer

    CCAvg : Avg. spending on credit cards per month ($000)

    Education : Education Level.
    1: Undergrad;
    2: Graduate;
    3: Advanced/Professional

    Mortgage : Value of house mortgage if any. ($000)

    10.Personal Loan : Did this customer accept the personal loan offered in the last campaign?

    11.Securities Account : Does the customer have a securities account with the bank?

    12.CD Account : Does the customer have a certificate of deposit (CD) account with the bank?

    13.Online : Does the customer use internet banking facilities?

    14.Credit card : Does the customer use a credit card issued by

Learning objectives:

* Exploratory Data Analysis
* Prepare and train a model
* Training and making predictions using a classification model
* Model evaluation

Goal:

The classification goal is to predict the likelihood of a liability customer buying personal loans.

Steps you need to take:

1. Read the column description and ensure you undersand each attribute well.
2. Study the data distribution in each attribute, share you findings
3. Get the target column distribution.
4. Split the data into training and testing set in the ratio of 70:30 respectively.
5. Use different classfication models (Logistic, Knn and Naive Bayes) to predict the likelihood of a customer buying personal loans
6. Print the confusion matrix for all the above models
7. Give your reasonin gon which is the best model in this case and why it performs better
