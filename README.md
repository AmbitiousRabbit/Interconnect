# Interconnect

The telecom operator Interconnect would like to be able to forecast their churn of clients. If it's discovered that a user is planning to leave, they will be offered promotional codes and special plan options. Interconnect's marketing team has collected some of their clientele's personal data, including information about their plans and contracts.

## Interconnect's services
Interconnect mainly provides two types of services:
  1. Landline communication. The telephone can be connected to several lines simultaneously.
  2. Internet. The network can be set up via a telephone line (DSL, digital subscriber line) or through a fiber optic cable.

Some other services the company provides include:
  * Internet security: antivirus software (DeviceProtection) and a malicious website blocker (OnlineSecurity)
  * A dedicated technical support line (Tech Support)
  * Cloud file storage and data backup (Online Backup)
  * TV streaming (Streaming TV) and a movie directory (Streaming Movies)

The clients can choose either a monthly payment or sign a 1- or 2-year contract. They can use various payment methods and receive an electronic invoice after a transaction.

Description of Datasets & the context around the columns:
* The `contract` dataset:
  * `customerID` - a customer's unique id
  * `BeginDate` - the start of their tenure
  * `EndDate` - the end of their tenure
  * `Type` - the type of contract they have
  * `PaperlessBilling` - Boolean value of `Yes` or `No`
  * `PaymentMethod` - the customers preferred form of payment
  * `MonthlyCharges` - their current contract charges
  * `TotalCharges` - the running total of their account charges

* The `personal` dataset:
  * `customerID` - a customer's unique id
  * `gender` - the customer's gender
  * `SeniorCitizen` - Boolean value of `1` or `0`
  * `Partner` - Boolean value of `Yes` or `No`  
  * `Dependents` - Boolean value of `Yes` or `No`
 
* The `phone` dataset:
  * `customerID` - a customer's unique id
  * `MultipleLines` - Boolean value of `Yes` or `No`

* The `internet` dataset:
  * `Unnamed: 0` - dataset index
  * `id` - a customer's unique id
  * `mb_used` - their current plan's MB usage
  * `session_date` - A date timeformat of YY-MM-DD
  * `user_id` - this is a sub identification of each user's logged historical charges across different session dates


# Project Process

## Step 1 | Access & Study the data
* Open and skim to become familiarize with the data
## Step 2 | Prepare the data
* Convert the data to the necessary types
* Find & Eliminate errors in the data
## Step 3 | Analyze the data
* Conduct EDA & SDA while exercising the 5 analytic frameworks (if applicable):
  * What happened? - Descriptive 
  * Why did it happen? - Diagnostic 
  * What will happen? - Predictive
  * How can we make it happen? - Prescriptive
## Step 4 | Build a predictive, forecasting model 
* Consider and select data that is useful to analyze the information on the customers' behavior that can pinpoint a churning or non-churning customer.
## Step 5 | General Conclusion
* State found insights in a clear, concise manner.
