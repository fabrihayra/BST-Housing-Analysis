# Housing Values in Suburbs of Boston
The Housing Values in Suburbs of Boston project is a machine learning project that involves building a regression model to predict the median value of owner-occupied homes in the Boston area based on 13 input features.

## Project Overview
The project includes the following steps:

1. Data preprocessing: The dataset is loaded and preprocessed to ensure that the input features are in a suitable format for machine learning. This includes scaling the features and splitting the data into training, validation, and test sets.
2. Model building: A regression model is constructed using the Keras API of TensorFlow. The model architecture and hyperparameters are selected based on previous experiments and hyperparameter tuning.
3. Model training: The model is trained on the training data using the mean squared error loss function and the Adam optimizer. Regularization techniques such as early stopping and dropout are used to prevent overfitting.
4. Model evaluation: The model is evaluated on the validation set during training to monitor its performance and determine when to stop training. Finally, the performance of the trained model is evaluated on the test set to obtain an unbiased estimate of its generalization performance.

## Dataset
The dataset contains 506 rows of data, with each row representing a different suburb of Boston and its associated features. The dataset can be found in the Keras API of TensorFlow, specifically in the boston_housing module.

## Evaluation Metrics
The performance of the trained model is evaluated on the test set using two metrics:

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

## Conclusion
The Housing Values in Suburbs of Boston project is an essential problem in the data analysis industry, and the ability to construct accurate and generalizable regression models is a valuable skill for any data analyst. The project can be improved by exploring different model architectures, hyperparameters, and preprocessing techniques.

## Source
Harrison, D. and Rubinfeld, D.L. (1978) Hedonic prices and the demand for clean air. J. Environ. Economics and Management 5, 81–102.
Belsley D.A., Kuh, E. and Welsch, R.E. (1980) Regression Diagnostics. Identifying Influential Data and Sources of Collinearity. New York: Wiley.

## Project Idea:
[Kaggle (Boston Housing Competition)](https://www.kaggle.com/competitions/boston-housing/overview/description)
