# Customer Churn Prediction using ANN

### Project Overview
Customer churn prediction plays a vital role in the banking industry, as retaining existing customers is more cost-effective than acquiring new ones. This project focuses on predicting customer churn using an Artificial Neural Network (ANN) by analyzing customer demographic, financial, and behavioral data.An Artificial Neural Network is implemented using TensorFlow and Keras, consisting of multiple dense layers with ReLU activation functions and a Sigmoid-activated output layer for binary classification. The model is trained using the Adam optimizer and binary cross-entropy loss function.

### Dataset Description: Customer Churn Dataset KAGGLE

This dataset contains detailed information about bank customers and is designed to analyze and predict customer churn, i.e., whether a customer is likely to leave the bank. It is commonly used for classification tasks in machine learning and data analytics.
The dataset includes 10,000 customer records with a mix of demographic, financial, and behavioral attributes. The target variable indicates whether a customer has exited the bank.

### Approach

### 1. Problem Understanding
&#9679; Identified customer churn as a binary classification problem where the objective is to predict whether a customer will exit the bank based on historical customer data.

### 2. Dataset Loading
&#9679; Loaded the customer churn dataset using Pandas and examined its structure, dimensions, and data types.

### 3. Data Exploration
&#9679; Performed exploratory analysis to check for missing values, duplicates, and basic statistical summaries to ensure data quality.

### 4. Feature Selection
&#9679; Removed non-informative and identifier columns such as RowNumber, CustomerId, and Surname to improve model relevance.

### 5. Categorical Feature Encoding
&#9679; Converted categorical variables (Geography and Gender) into numerical form using one-hot encoding.

### 6. Feature Scaling
&#9679; Applied StandardScaler to normalize numerical features, ensuring stable and efficient ANN training.

### 7. Train–Test Split
&#9679; Split the dataset into training and testing sets using an 80:20 ratio to evaluate model generalization.

### 8. ANN Model Design
&#9679; Designed an Artificial Neural Network using TensorFlow and Keras with multiple dense layers and ReLU activation functions.

### 9. Model Compilation
&#9679; Compiled the model using the Adam optimizer and binary cross-entropy loss function for binary classification.

### 10. Model Training
&#9679; Trained the ANN over multiple epochs to learn complex non-linear relationships in the data.

### 11. Model Evaluation
&#9679; Evaluated the trained model on test data using accuracy metrics and performance analysis.

### 12. Prediction & Analysis
&#9679; Generated churn predictions and analyzed results to assess the effectiveness of the model.

### Result
