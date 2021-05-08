# SPS-10853-Car-Resale-Value-Prediction
Car Resale Value Prediction

link on the given link for video demonstration: https://drive.google.com/file/d/1WWHvwtzQmYbYWSmUitT-N80s-cQ1uI33/view?usp=sharing

1. INTRODUCTION
1.1 OVERVIEW
The prices of the new manufactured cars in the automobile
industry by the manufacturer with some extra cost which are incurred
by the Government in the form of taxes. So, customers buying a new
car can be assured of the money which they are investing to be worthy.

1.2 PURPOSE
Client will be able to efficiently determine the price that the
chosen resale vehicle must cost. So, that people can invest money
according to their preferences.
2. LITERATURE SURVEY
2.1 EXISTING PROBLEM
Existing models use linear regression algorithm.Decision tree algorithms as the basic models.

2.2 PROPOSED SOLUTION
Proposed model is built on Random Forest regressor
algorithm, instead of using conventional Linear Regression, and
Decision Trees models. This model takes less amount of training time,and the correlation coefficient is high,and low error metrics, thus
making suitable for modelling.

3. THEORITICAL ANALYISIS
3.1 BLOCK DIAGRAM

3.2 SOFTWARE DESIGNING
1. JAVA 16.0
2. WEKA 3.8
3. MAVEN
4. ECLIPSE IDE

4. EXPERIMENTAL INVESTIGATIONS
There are separate datasets, one for the training, and other for
testing the built model.

TRAINING DATASET:
Training data consist of 12 independent variables and 1 dependent
variable.Many attributes consisted of much missing data.

DATA CLEANING:
As depicted in the train dataset properties table.

DATA VISUALIZATION:
Visualizing the data is the most crucial part in analyzing the model. We
use WEKA explorer to visualize the data in the form of Histogram plots. Below
figures shows the modified data in the form of histogram plots.
We are using the following algorithms in selecting the best fit algorithm.
1. Linear Regression
2. Random Forest

When Random Forest regressor is used the model showed an accuracy
measure of 94%, with the following metric evaluations shown below.

5. RESULT:
From the above analysis, the most suitable algorithm for building the
model is to use Random Forest regressor. Hence, the final model was
being built using Random forest regressor Below table, shows the
accuracy percentage of both models for comparative analysis.


MODEL
Accuracy
Lnear regression
80.4%
Random forest
95.0%

The below figure shows the output of the random forest regressor,
which was run on the test dataset. And actual values to that of the predicted
values is also being shown in the figure


6.ADVANTAGES AND DISADVANTAGES:

Advantages:

1. Accuracy
2. Generic model i.e. can be used for any type of raw data
3. Robust
4. Feature Engineering is not needed

Disadvantages:
1. Sometimes may undergo overfitting, if dataset is small.

8. CONCLUSION:

After trying and testing 2 different algorithms,the best accuracy was
found out in Random Forest Regressor (94.4%) while Machine Learning
algorithm produced an accuracy of (83.4%). While new features can be
created via feature engineering which may help in predicting the target variable.
