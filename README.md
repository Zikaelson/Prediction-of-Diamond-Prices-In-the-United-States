# Prediction-of-Diamond-Prices-In-the-United-States

This project sees to clearly show clear understanding and applications of deep learning course. Dataset used for this project would be collected from the TensorFlow Dataset while focusing on structured dataset. 

## Dataset

For this purpose of this project, the Diamonds Dataset from the Structured dataset list would be used to clearly show understanding of the deep learning concepts. The Diamond dataset contains the prices and other attributes of almost 54,000 diamonds. The variables are as follows 
Prices: the price of the diamond in US dollars ranging from $326 to $18,823
Carat: Carat weight of the diamond from 0.2 to 5.01
Cut: Describe cut quality of the diamond. Quality in increasing order Fair, Good, Very Good, Premium, Ideal
Color: Color of the diamond, with D being the best and J the worst color
Clarity: How obvious inclusions are within the diamond:(in order from best to worst, FL = flawless, I3= level 3 inclusions) FL, IF, VVS1, etc
X: length in mm (0 to 10.74)
Y: width in mm (0 to 58.9)
Z: depth in mm (0 to 31.8)
Depth: The height of a diamond, measured from the culet to the table, divided by its average girdle diameter (43 to 79)
Table: The width of the diamond's table expressed as a percentage of its average diameter (43--95)

## Business Problem
In summary, the business problem here is to predict the prices of diamonds leveraging the different data features provided as well as Artificial Intelligence algorithm (Deep learning) to help businesses and customers makes informed decisions.

## What is the model you will build? 
Artificial Neural Network would be used to build a regression model to predict the prices of diamond based on the historical data and label of our dataset.

## Methodology

The steps that was be employed during the project is stated below:
1. Data Pre-processing: 

This first step involves importing relevant libraries and understanding the dataset using different python code functions. Defining the dependent and independent variables. In addition, the dataset is split into train and test dataset in which the train dataset is used to train the neural network model while the test data is used to check the efficiency of the built model by comparing the actual and predicted test data to ascertain the mean square error.

2. Building the Artificial Neural Network: The following takes places in this step. 


Initializing the ANN
Adding the Input and the first output layer
Adding the second hidden layer
Adding the output layer

3. Training the Artificial Neural Network: 

Compiling the ANN
Training the ANN model on the training set
Parameters tuning to get the lowest possible mean square error by adjusting the parameters such as Activation Function, epoch, Dense units, optimizer, batch size etc
Predicting the result of the test set 


