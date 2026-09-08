# iris-classification
Iris Flower Classification is a machine learning project that identifies the species of an iris flower based on its sepal length, sepal width, petal length, and petal width. The project uses the Iris dataset containing three species: Setosa, Versicolor, and Virginica. This predicts the species of a new flower and checks .

1. Project Overview

   Iris Flower Classification is a machine learning project used to classify iris flowers into three different species based on their measurements.

2. Objectives

Understand the Iris dataset.
Analyze flower measurements.
Train a machine learning classification model.
Predict the species of a new flower.
Evaluate the model's accuracy.

3. Technologies Used
   
Python
Pandas
Matplotlib
Scikit-learn

4. Dataset
   
The dataset contains four input features:
Sepal Length,
Sepal Width,
Petal Length,
Petal Width,

The target variable is Species, which contains:
Setosa,
Versicolor,
Virginica.

5. Algorithm

The project uses the K-Nearest Neighbors (KNN) classification algorithm with K = 5.

6. Working
   
Load the Iris dataset.
Display and analyze the data.
Separate features and target values.
Split the dataset into training and testing data.
Train the KNN model.
Predict flower species.
Calculate model accuracy.
Display the classification report and confusion matrix.
Predict the species of a new flower.
Visualize the dataset using a scatter plot.

7. Sample Prediction
 
For a flower with:
Sepal Length = 5.1
Sepal Width = 3.5
Petal Length = 1.4
Petal Width = 0.2
The model predicts its species based on the learned data.

8. How to Run
Install the required libraries:
pip install -r requirements.txt
Then run:
python iris_classification.py
The program displays the dataset, species distribution, accuracy, classification report, confusion matrix, and prediction. It also creates an image named iris_classification.png.
