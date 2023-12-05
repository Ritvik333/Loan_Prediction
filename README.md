# Loan Prediction System

This GitHub repository contains a Python-based Loan Prediction System using data analysis and machine learning techniques. The project involves predicting loan approval status based on various features using a variety of machine learning models.

## Prerequisites
Make sure you have the following dependencies installed:
- pandas
- scikit-learn
- matplotlib

Install the dependencies using the following command:
```bash
pip install pandas scikit-learn matplotlib
```

## Dataset
The project uses a dataset (`train.csv`) containing information about loan applicants, including features such as Gender, Marital Status, Education, Applicant Income, and more.

## Data Preprocessing
The dataset undergoes preprocessing to handle missing values and convert categorical variables into numerical form. The code utilizes techniques such as iterative imputation and label encoding to ensure the data is suitable for machine learning models.

## Exploratory Data Analysis (EDA)
The EDA section includes an analysis of missing values in the dataset and their treatment. Additionally, it visualizes the distribution of key variables using bar plots.

## Machine Learning Models
The project implements several machine learning models for loan prediction:
- Decision Tree Classifier
- Random Forest Classifier
- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)
- Linear Discriminant Analysis (LDA)

The accuracy scores of each model on the test set are printed, providing insights into their performance.

## Model Evaluation
The project evaluates the models using accuracy scores and AUC-ROC curves. The AUC scores for Logistic Regression and Random Forest models are displayed, and a bar plot of feature importances from the Random Forest model is generated.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/loan-prediction-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd loan-prediction-system
   ```
3. Run the main Python script:
   ```bash
   python loan_prediction_system.py
   ```

Feel free to customize the code, experiment with different models, and further enhance the project based on your requirements. Contributions and feedback are welcome!
