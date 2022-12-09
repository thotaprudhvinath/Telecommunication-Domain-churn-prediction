# Telecommunication-Domain-churn-prediction
##Business Understanding

The telecommunications sector has become one of the main industries in developed countries. The technical progress and the increasing number of operators raised the level of competition. Companies are working hard to survive in this competitive market depending on multiple strategies. Three main strategies have been proposed to generate more revenues: 
1. Acquire new customers 
2. Upsell the existing customers
3. Increase the retention period of customers 
However, comparing these strategies taking the value of return on investment (RoI) of each into account has shown that the third strategy is the most profitable strategy, proving that retaining an existing customer costs much lower than acquiring a new one, in addition to being considered much easier than the upselling strategy. To apply the third strategy, companies have to decrease the potential of customer’s churn, known as "the customer movement from one provider to another".

Customer churn is a considerable concern in service sectors with high competitive services. On the other hand, predicting the customers who are likely to leave the company will represent a potentially large additional revenue source if it is done in the early phase.

Many research confirmed that machine learning technology is highly efficient to predict this situation. This technique is applied through learning from previous data.


The data set includes information about:

1. Customers who left within the last month – the column is called Churn
2. Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
3. Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
4. Demographic info about customers – gender, age range, and if they have partners and dependents

__Problem Statement -__Given various features about a customer like Gender, SeniorCitizen, Partner, Dependents etc.. , predict if the customer will churn or not.

__Task -__ Prepare the Data and build a model to predict the churn of a customer.
These are the steps that are followed will doing the project

<br><b>step- 1 :-<b/> loading the data<br/>
  
__step- 2 :-__ Document the below mentioned points properly.
1. Identify the input and output/target variables.
2. Here,x dataframe has input variables.
3. and y dataframe has output/target variable.
4. As we know the target variable is given then the type of the problem comes under __supervised learning.__
5. Target variable has __nominal data__ so, __classification algorithm__ and __evaluation metrics__ can be applied on the data

<br>__Step - 3:-__ Split the dataset into Training and Testing<br/>
a. Here, the data is splited into 75:25 ratio
  
<br><b>Step - 4:-</b>Data preparation on train data:<br/>
a. serperating catogorical and numerical data in x_train dataframe
b. applying __Stadardization__ on Numerical data.
c. applying __OneHot Encoding and Lable Encoding__ on Catagorical data.
  
<br>__Step - 5__:- Data preparation on test data:<br/>
  
__Step - 6:-__ Model Training Phase - Use all the algorithms mentioned below to train separate models:
1. KNN
2. Logistic Regression
3. Support Vector Machines
4. Decision Trees
5. Random Forest
6. Support vector mechine
  
__Step - 7:-__ Evaluating the preformance of the model by using accuracy_score metrics 

__Note -__ This case study was done to understand the machine learning algorithms so, no data cleaning was done axcept null values
