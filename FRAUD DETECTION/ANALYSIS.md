

The aim of this R project is to build a classifier that can detect credit card fraudulent transactions. 
I used a variety of machine learning algorithms like Decision Trees, Logistic Regression, Artificial Neural Networks and finally,
Gradient Boosting Classifier that will be able to discern fraudulent from non-fraudulent ones.

In this section of the project, I scaled the data using the scale() function. 
I applied this to the amount component of our creditcard_data amount. 
With the help of scaling, the data is structured according to a specified range. 
Therefore, there are no extreme values in the dataset that might interfere with the functioning of the model.

After standardizing the entire dataset, I split the dataset into training set as well as test set with a split ratio of 0.80. 
This means that 80% of the data will be attributed to the train_data whereas 20% will be attributed to the test_data. 
I then found the dimensions using the dim() function.

Gradient Boosting (GBM)
Gradient Boosting is a popular machine learning algorithm that is used to perform classification and regression tasks. 
This model comprises of several underlying ensemble models like weak decision trees. 
These decision trees combine together to form a strong model of gradient boosting. 
I implemented gradient descent algorithm in the model.

AUC-ROC Curve
In the last section of the project, I calculated and plotted an ROC curve measuring the sensitivity and specificity of the model. 
The print command plots the curve and calculates the area under the curve. 
The area of a ROC curve can be a test of the sensivity and accuracy of a model.


Conclusion
Concluding our R Data Science project, I learnt how to develop a credit card fraud detection model using machine learning. 
I used a variety of ML algorithms to implement this model and also plotted the respective performance curves for the models. 
I also learnt how data can be analyzed and visualized to discern fraudulent transactions from other types of data.



