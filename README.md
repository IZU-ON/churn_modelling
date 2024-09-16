# Customer Churn Modeling

This repository contains code for predicting customer churn using a deep learning approach. The objective is to use customer data such as tenure, product subscriptions, and customer service interactions to predict whether a customer will churn.

## Steps performed in the Jupyter Notebook:

1. **Data Loading**: Loaded the customer churn dataset using pandas.
2. **Exploratory Data Analysis (EDA)**:
   - Investigated the dataset for missing values and outliers.
   - Visualized data distributions and correlations using matplotlib and seaborn.
3. **Data Preprocessing**:
   - Handled missing values and outliers.
   - Converted categorical variables into numerical using label encoding and one-hot encoding.
   - Scaled numerical features using StandardScaler.
4. **Deep Learning Model Setup**:
   - Built a neural network using Keras and TensorFlow.
   - Defined input layers, hidden layers, and the output layer for classification.
5. **Model Training**:
   - Compiled the model with Adam optimizer and binary cross-entropy loss.
   - Trained the model with the training dataset and validated it on the validation set.
6. **Model Evaluation**:
   - Evaluated the model’s performance using accuracy, precision, recall, and AUC-ROC score.
7. **Conclusion**:
   - Finalized the best model and used it to predict customer churn on the test dataset.

## Requirements:
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, TensorFlow, Keras
