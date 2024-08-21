# Diabetes Classification using Machine Learning

## Project Overview
This project focuses on building machine learning models to classify individuals as diabetic or non-diabetic based on a comprehensive dataset comprising health and demographic data. The dataset contains 100,000 records of individuals with features like gender, age, location, race, hypertension, heart disease, smoking history, BMI, HbA1c levels, and blood glucose levels. The goal of this project is to predict diabetes status using various classification algorithms.

## Dataset
- **Source**: The dataset includes detailed health and demographic data of 100,000 individuals.
- **Features**:
  - **Gender**: Male, Female
  - **Age**: Age in years
  - **Location**: State of residence
  - **Race**: AfricanAmerican, Asian, Caucasian, Hispanic, Other
  - **Hypertension**: Whether the individual has hypertension (1: Yes, 0: No)
  - **Heart Disease**: Whether the individual has heart disease (1: Yes, 0: No)
  - **Smoking History**: Smoking history categories such as never, current, former, etc.
  - **BMI**: Body Mass Index
  - **HbA1c Level**: Hemoglobin A1c level, a measure of blood sugar
  - **Blood Glucose Level**: Fasting blood glucose level
  - **Diabetes**: Target variable indicating diabetes status (1: Diabetic, 0: Non-diabetic)

## Project Workflow

### Data Preprocessing
1. **Loading Data**: Loaded the dataset using pandas.
2. **Exploratory Data Analysis (EDA)**: 
   - Checked for missing values and duplicated records.
   - Visualized data distributions and relationships using seaborn and matplotlib.
   - Analyzed smoking history categories and distribution of key features.
3. **Data Encoding**: Categorical features like gender, location, and smoking history were encoded using LabelEncoder for model compatibility.
4. **Data Splitting**: Split the data into training and testing sets using an 80-20 ratio.

### Machine Learning Models
Implemented and compared several classification algorithms:
1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**
4. **Support Vector Machine (SVM)**
5. **XGBoost Classifier**

### Model Evaluation
Evaluated the performance of the models using accuracy scores. Further evaluation with other metrics such as precision, recall, and F1-score can be performed.

### Results
The models were trained on the processed data, and the accuracy of each model was computed. The XGBoost classifier achieved the highest accuracy, demonstrating the effectiveness of ensemble methods in classification tasks.

