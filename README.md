# Heart Disease Prediction with Logistic Regression

This repository contains a machine learning model for predicting heart disease using Logistic Regression. The model classifies individuals as either at risk or not at risk for heart disease based on health-related features such as age, cholesterol levels, blood pressure, and more. The project demonstrates how machine learning can be applied to healthcare for early diagnosis and intervention.

## Problem Overview:
Heart disease is one of the leading causes of death globally, and early detection is crucial for effective prevention and treatment. Using machine learning models, we can predict an individual’s risk of developing heart disease and enable timely medical intervention.

The dataset used in this project contains key health metrics such as:
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Serum cholesterol
- Fasting blood sugar
- Electrocardiographic results
- Maximum heart rate achieved
- Exercise-induced angina
- Oldpeak (depression induced by exercise)
- Slope of the peak exercise ST segment
- Number of major vessels colored by fluoroscopy
- Thalassemia (blood disorder)

The objective is to predict whether a person has heart disease (labeled as 1) or not (labeled as 0) using Logistic Regression.

## Dataset:
The dataset used for this project is publicly available and contains information from patients who have been diagnosed with heart disease. It is commonly used for training and evaluating machine learning models in healthcare.

You can find the dataset [here](https://archive.ics.uci.edu/ml/datasets/Heart+Disease).

## Project Steps:

### 1. Data Exploration & Preprocessing:
   - Load and explore the dataset to understand its structure.
   - Handle missing values and encode categorical variables.
   - Scale the features using StandardScaler for better model performance.

### 2. Model Training:
   - Split the dataset into training and testing sets.
   - Train a Logistic Regression model on the training data.
   - Use cross-validation to fine-tune model parameters.

### 3. Model Evaluation:
   - Evaluate the model's performance using metrics such as accuracy, precision, recall, and F1-score.
   - Generate confusion matrices and ROC curves to assess the model's classification ability.

### 4. Prediction & Conclusion:
   - Make predictions on the test set.
   - Summarize the results and draw conclusions about the effectiveness of the Logistic Regression model.

## Libraries Used:
- **`numpy`**: For numerical operations and array handling.
- **`pandas`**: For data manipulation and analysis.
- **`scikit-learn`**: For building and evaluating the Logistic Regression model.
  - **`StandardScaler`**: For scaling features to ensure better model performance.
  - **`accuracy_score`**: For evaluating the model's accuracy.
  - **`train_test_split`**: For splitting the dataset into training and testing sets.
  - **`LogisticRegression`**: For implementing the Logistic Regression model to predict heart disease.
