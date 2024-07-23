# End-to-End-Neural-Network
This repo provides an introductory level project that allows you to implement a full end-to-end small neural network using real data to compare against traditional machine learning predictive models and build upon it.

## 1. Foundations

Please reference the following notebook in the repo for a live example to following along with this Foundations section of the readme:

```
nn_vs_ml.ipynb
```

### Project: Predicting House Prices
### Objective:
Implement a neural network to predict house prices and compare its performance with traditional machine learning models like Linear Regression and Random Forest.

### Dataset:
Use the california housing dataset or ames data set (california data set has more data and less features, and ames has less data but more features), which can be accessed from the sklearn library or other sources like Kaggle.
Steps:
1. Data Preparation:

    - Load the dataset.
    - Perform exploratory data analysis (EDA) to understand the data.
    - Handle missing values, if any.
    - Encode categorical variables.
    - Split the data into training and test sets.

2. Traditional Machine Learning Models:
  
    - Implement Linear Regression.
    - Implement Random Forest.
    - Evaluate the performance of these models using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

3. Neural Network Implementation:
  
    - Normalize the data.
    - Define the neural network architecture using a library like TensorFlow/Keras.
    - Compile and train the neural network.
    - Evaluate the performance of the neural network using the same metrics (MAE and RMSE).

4. Comparison:
  
    - Compare the performance of the neural network with the traditional machine learning models.
    - Analyze the results and draw conclusions.

### Explanation:
  - Data Preparation: Load the dataset, perform EDA, and split the data into training and test sets.
  - Traditional Machine Learning Models: Implement Linear Regression and Random Forest models, train them, and evaluate their performance.
  - Neural Network Implementation: Normalize the data, define a neural network architecture, compile and train the neural network, and evaluate its performance.
  - Comparison: Compare the performance of the neural network with the traditional machine learning models using the same evaluation metrics.

This project covers the full process from data preparation to model comparison and provides a comprehensive understanding of how neural networks stack up against traditional machine learning models.
