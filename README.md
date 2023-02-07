# Customer_churn_prediction

Customer churn is when a customer decides to stop using services, content, or products from a company. Reasons for customer churn can be various and the most typical are poor customer service, not finding enough value in a product or service, lack of customer loyalty and lack of communication.

## DATA

Telco's customer churn dataset,downloaded from Kaggle. 

The Telco customer churn data contains information about a fictional telco company that provided home phone and Internet services to 7043 customers in California. 

It indicates which customers have left, stayed, or signed up for their service.

## DATA CLEANING AND TRANSFORMATION

--Replaced yes and no with 1 and 0, respectively.

--Handled missing values by replacing them with Nan in the TotalCharges column.

--Changed the data type for TotalCharges to float.

--Dropped Null values.

--Normalized continuous variables.

--Performed one-hot encoding for categorical variables.

## MULTILAYER PERCEPTRON MODEL

Multilayer perceptron model (MLP) (aka vanilla feed-forward neural network, or sometimes just neural networks) can be viewed as generalizations of linear models that perform multiple stages of processing to come to a decision.

Prediction by linear regression is given as:

![image](https://user-images.githubusercontent.com/117385630/217272916-c0c53419-3624-40cb-ac44-38eb23b1c72f.png)

![image](https://user-images.githubusercontent.com/117385630/217273167-13de21f6-f9f2-41f8-9531-aff7f9393f12.png)

## SUMMARY
We trained the multilayer perceptron model and got AUC for the test set=0.87, which shows that the model can predict well whether a customer will churn or not.

Usually, neural networks take time to train, which can be difficult in a real-world situation. Therefore, it is better to start with a benchmark model like logistic regression and then, if high accuracy is needed to train other more complicated models.


