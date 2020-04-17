

### 1)Which topic did you choose to apply the data science methodology to? 

I have chosen as topic for this task the application of data science in the field of credit cards.


### 2)You are required to:
- Describe the problem, related to the topic you selected.
- Phrase the problem as a question to be answered using data  

So the main problem for banks regarding credit cards is that they have to create a model to know to who they can provide them. Because it is not possible for everyone to provide a credit card. That's why an automation procedure is necessary to check the legibility of holding a credit card . 

So our question would be **_Can we automatically determine if a client is suitable to obtain a credit card?_**

### 3)Main the followings:
- Analytic Approach
- Data Requirements
- Data Collection
- Data Understanding and Preparation
- Modeling and Evaluation  


1. **Analytic Approach**: As the problem requires a yes/no answer we will use a classification model

2. **Data Requirements:**   
           - Client's Profession
           - Client's Yearly income
           - Client's Yearly expenses
           - Client's VAT certificate ID
           - National ID card Number
           - Statement Of purpose ID(Bank provides) 
           - Respective Bank's interest amount 

3: **Data Collection:**   
              - Every bank's current account holder
              - Local Voter office
              - Local VAT office
              - National Bank which controls all the banks  
              
4: **Data Understanding and Preparation:** In this step we need to evaluate the different variables of our data in order to understand it better. As we  have to collect a vast amount of data, there can be some data for consequences of misinterpretation or void values.In that case we will assume that values as null values and filled that values by calculating uni variate statistics, such as mean or median and the correlation between variables. In that way we can evaluate the quality of the data. In the data preparation phase we can apply feature engineering ,principal component analysis to reduce the dimension  as well as can prepare the data in an specific way depending on the model that we have intended to use.  

5: **Modeling and Evaluation:** For this criteria we can use the naive bayes classifier model (machine learning approach). Multinomial naive bayes can be applied here as there will be too much features . Split the dataset into train ,test method. Then apply the proposed model . We will evaluate this through F1 score, precision score(ratio of true positive and false positive).
