# Predict-Credit-Card


### Summary of the Capstone Project: ML - Predicting Credit Consumption

#### **Business Context**
The credit card industry generates vast amounts of data, offering opportunities to analyze customer spending behavior. A better understanding of individual consumption patterns allows banks to develop targeted marketing strategies and enhance customer relationship management.

#### **Business Objective**
The goal is to predict future credit card consumption for a leading bank's customers based on:
1. **Customer Demographics** (age, income, account type, etc.)
2. **Customer Behavioral Data** (credit/debit card transactions, loans, investments, etc.)
3. **Credit Consumption Data** (historical credit card spending and future targets)

The objective is to build a machine learning model to estimate credit consumption for customers with missing future consumption values.

#### **Data Description**
- **CustomerDemographics.csv**: Includes details like customer ID, gender, age, income level, account type, employment tenure, tenure with the bank, region code, and net banking usage.
- **CustomerBehaviorData.csv**: Contains credit/debit card spending and transaction counts for April, May, and June, along with information on card limits, loans, investments, and loan inquiries.
- **CreditConsumptionData.csv**: Contains the target variable, which is the average credit card spend for the next three months (July, August, September).

#### **Key Challenge**
The task requires handling missing values for credit consumption and accurately predicting these using the available data.

#### **Evaluation Metric**
The model performance will be assessed using **Root Mean Square Percentage Error (RMSPE)**, comparing the predicted and actual credit consumption values.

#### **Expected Deliverables**
1. Code with detailed comments.
2. Exploratory data analysis (EDA) results.
3. Model validation outputs.
4. Comprehensive model documentation.
5. Predicted credit consumption values for customers with missing targets.

#### **Note**
Only data without missing values for the target variable should be used for model training, while predictions are required for the remaining customers with missing values.
