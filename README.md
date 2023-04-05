Project Name : Credit Card Fraud Detection

Abstract : Credit card frauds are easy and friendly targets. E-commerce and many other online sites have 
increased the online payment modes, increasing the risk for online frauds. Increase in fraud rates, 
researchers started using different machine learning methods to detect and analyse frauds in 
online transactions. It is important that credit card companies are able to recognize fraudulent 
credit card transactions so that customers are not charged for items that they did not purchase 
also to retain the customer without disturbing them as well as companies can learn about 
fraudulent.The main aim of the project is Predict the accuracy of Anonymized credit card 
transactions labeled as fraudulent or genuine, with an objective, to analyse the past transaction 
details of the customers and extract the behavioural patterns And then the machine learning 
algorithm with better accuracy score can be chosen to be one of the best methods to predict 
frauds.

Proposed algorithm: After analyzing with various algorithms how it works for the project also based on the accuracies 
obtained for each algorithm. finally, I have come to the conclusion as Random Forest Classifier 
is well suited for credit card fraud detection project because compare to other algorithms(SVM, 
KNN, and Logistic regression) Random Forest obtained more accuracy where accuracy score is 
99.49.

About the Dataset : Dataset name : creditcard.csv
• Dataset from : Kaggle 
• Kaggle link : https://www.kaggle.com/mlg-ulb/creditcardfraud
• It contains only numerical input variables which are the result of a PCA transformation. 
Unfortunately, due to confidentiality issues, we cannot provide the original features and 
more background information about the data. Features V1, V2, … V28 are the principal 
components obtained with PCA, the only features which have not been transformed with 
PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each 
transaction and the first transaction in the dataset. The feature 'Amount' is the transaction 
Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 
'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Technical Modules : 
● In The Credit Card Fraud Detection process, Credit cards payments need to 
pass a first terminal check and if not rejected then the user credit card 
transaction data from the database will be passed to a predictive model that 
raises alerts (transaction labeled as fraud or genuine). If the predictive 
model alerts as fraud then the company administrator will block the credit 
card and send the alert message to the user.
● There are four modules in the predictive model which is mentioned below.
● Data collections : collecting data or using the data set from kaggle. 
● Data pre-processing : cleaning of data , instance selection and feature 
extraction.
● Evaluating the data : will evaluate the data by splitting the data into 80/20 
ratio. 
● Calculating the accuracy : By using the Random Forest classifier model will 
calculate the accuracy of the model for the dataset.

Conclusion and Future scope :
In this project, I studied applications of machine learning like Logistic regression, Random 
forest , K-Nearest Neighbor and SVM and shows that it proves accurate in deducting fraudulent 
transaction . Supervised learning algorithms are novel one in this literature in terms of 
application domain. If these algorithmsare applied into bank credit card fraud detection system, 
the probability of fraud transactions can be predicted soon after credit card transactions. The 
objective of the project was taken differently than the typical classification problems in that I 
had a accuracy which is used to evaluate the performance for the proposed system. By 
comparing all the four methods, we found that random forest classifier is better than the logistic 
regression, K-Nearest Neighbor and SVM.

From the above comparative analysis of the various credit card fraud detection techniques it is 
clear that Random Forest performs best in this scenario. But the drawbacks of this project by 
using the above four algorithms I cannot determine the names of fraud for the given dataset 
using machine learning. For the further development of the project I can work to solve this 
problem by using various methods

