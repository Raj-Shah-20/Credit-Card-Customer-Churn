# Credit-Card-Customer-Churn

## Introduction
<p align = "justify">The main objective is to select the model that predicts credit card customer churning best by comparing them with the performance of different Machine Learning models using R. Customer churn is a common measure of lost customers. By minimizing customer churn, a company can maximize its profits. Companies recognize that existing customers are one of the most valuable assets a company could have and customer retention is critical for a good marketing strategy. The prevention of customer churn through customer retention is the core problem of Customer Relationship Management. Here, an analysis is done on purchasing behavior of bank customers from a certain dataset. A detailed analysis is worked out to convert raw customer data into meaningful and useful data that suits the buying behavior and in turn, converts this meaningful data into knowledge for which predictive data mining techniques are adopted.</p>


## Dataset 
https://www.kaggle.com/varunbarath/credit-card-customers-bank-churners

## Conclusion & Future Scope 
<p align = "justify">We can conclude with certainty that ‘Random Forest’ will be the best model for 
predicting credit card customer attrition for both datasets since it predicted customer 
attrition with the highest accuracy in both datasets – with reduced dimensions and 
principal components, and the regular one. </p>
<p align = "justify">We also observed that Naïve Bayes and SVM perform a tiny bit better with PCA data 
whereas the accuracy of Decision Tree and Random Forest dipped a bit when we used 
the PCA data. Also, as we observe the graphs, we can see few models performed a 
bit better with the transformed PCA data instead of the regular ones and vice versa. 
Dataset is of 20 dimensions (features), which might not be considered large enough 
to perform dimentionality reduction or even PCA, but performing PCA altered the 
model accuracy to an extend. Accuracy of all the models before PCA differed a lot 
from each other, but after PCA all the models gave the same accuracy in the range of 
90%. This shows that all the models were able to train and fit the data correctly and 
capture the variablitiy of the features, which was not the case when we considered all 
the features from the dataset. </p>
<p align = "justify">For future scope, we could implement more models and try deep learning and see if 
we get more accurate predictions. We can also build a web application and/or mobile 
application and sell our product to banks and financial institutions where they can 
make use of it to determine if they should issue a new credit card to a customer based 
on the details provided by him as well as the customers past credit card usage history 
and patterns. </p>

## References

1.	Dataset  https://www.kaggle.com/code/varunbarath/credit-card-customers-bank-churners/data<br><br>
2.	Logistic-Regression https://www.javatpoint.com/logistic-regression-in-machine-learning<br><br>
3.	SVM  https://www.javatpoint.com/machine-learning-support-vector-machine-algorithm<br><br>
4.	Decision-tree  https://www.javatpoint.com/machine-learning-decision-tree-classification-algorithm<br><br>
5.	https://towardsdatascience.com<br><br>
6.	https://medium.com<br><br>
