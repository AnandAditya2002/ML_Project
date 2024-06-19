
# 🔰Disease Prediction Using Machine Learning

This project aims to develop a reliable machine learning model to predict diseases based on an individual's symptoms. Here’s an overview of our approach:



## 🚀Approach

### 1. Data Collection
Data preparation is the initial step in any machine learning task. We are using a Kaggle dataset for this project, consisting of two CSV files—one for training and one for testing. The dataset has 133 columns, where 132 columns represent various symptoms and the last column indicates the prognosis.

### 2. Data Cleaning
Data cleaning is vital in a machine learning project as the data quality directly impacts the model's performance. In our dataset, all columns are numerical except for the target column, prognosis, which is a string. We use a label encoder to convert the prognosis column into numerical values, ensuring the data is ready for model training.

### 3. Model Training
Once the data is cleaned, it is ready for model training. We will train three different machine learning models using this data:

Support Vector Machine (SVM) Classifier
Naive Bayes Classifier
Random Forest Classifier
We will utilize a confusion matrix to assess the performance of each model.

### 4. Making Predictions
After training the models, we will predict diseases based on input symptoms by aggregating the predictions from all three models. This ensemble approach improves the overall accuracy and robustness of our predictions.

### 5. Prediction Function
We will create a function that accepts symptoms (separated by commas) as input, predicts the disease based on these symptoms using the trained models, and returns the predictions in a JSON format.

Output of Model : 
![DISEASE](https://github.com/AnandAditya2002/ML_Project/assets/96615239/91dc5e6b-3423-4cbb-9422-2bbd4101b4ae)
