# Oasis Infobyte Data Analytics Internship

This repository contains projects completed as part of the Oasis Infobyte Data Analytics Internship.

## Intern Details
- **Name:** Vijayadharshini S
- **Domain:** Data Analytics
- **Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook

## Task 1: Retail Sales Exploratory Data Analysis (EDA)

### Objective
Analyze retail sales data to understand customer purchasing behaviour, sales trends, and product category performance.

### Work Performed
- Loaded and inspected the dataset.
- Checked missing values and data consistency.
- Calculated descriptive statistics.
- Analyzed monthly sales trends.
- Explored customer demographics and product categories.
- Created visualizations and derived business insights.
- Provided recommendations based on the findings.

### Files
- `Vijayadharshini_Task1.ipynb`
- `retail_sales_dataset.csv`

## Task 2: Customer Segmentation Analysis

### Objective
Segment customers based on purchasing behaviour using Recency, Frequency, and Monetary (RFM) analysis and K-Means clustering.

### Work Performed
- Loaded and cleaned the online retail dataset.
- Calculated RFM metrics.
- Standardized features using StandardScaler.
- Used the Elbow Method to select a suitable number of clusters.
- Applied K-Means clustering.
- Visualized customer segments.
- Compared cluster profiles and historical customer spending.
- Suggested targeted marketing strategies.

### Files
- `Vijayadharshini_Task2.ipynb`
- `Online Retail.xlsx`

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## How to Run
1. Install Python and Jupyter Notebook.
2. Install the required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn`.
3. Download or clone this repository.
4. Open the required notebook in Jupyter Notebook.
5. Ensure the corresponding dataset is available in the correct folder.
6. Run the notebook cells in order.

## Conclusion
These projects demonstrate data cleaning, exploratory data analysis, data visualization, customer behaviour analysis, and unsupervised machine learning for customer segmentation.

## Task 3: Data Cleaning

### Objective
Clean a deliberately incomplete Titanic passenger dataset and prepare it for further analysis.

### Technologies Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

### Work Performed
- Generated a data quality report covering missing values, duplicates, data types, and numeric summaries.
- Handled missing Age values using median imputation.
- Replaced missing Cabin values with "Unknown".
- Filled missing Embarked values using mode imputation.
- Checked and removed duplicate rows.
- Standardised text formatting in categorical and text columns.
- Detected potential outliers using the Interquartile Range (IQR) method.
- Retained potential outliers because they may represent genuine passenger values.
- Corrected data types for identifiers, numeric columns, and text columns.
- Generated a before-and-after cleaning summary.
- Exported the cleaned dataset as `Titanic_Cleaned.csv`.

### Project Files
- `Vijayadharshini_Task3.ipynb` — notebook containing the data cleaning process.
- `Titanic_Cleaned.csv` — cleaned dataset.
- `train.csv` — original dataset.

### Outcome
The cleaned dataset preserves the original 891 rows, has no missing values, and has no duplicate rows. Data types and text formatting were standardised for further analysis.

### Note
Potential outliers were identified using IQR and retained rather than automatically removed, since unusual values are not necessarily data errors.

## Level 2 – Task 1: House Price Prediction Using Linear Regression

### Project Overview

This project focuses on predicting house prices using machine learning regression techniques. The dataset contains 2,000 records with features such as area, bedrooms, bathrooms, floors, year built, location, condition, garage availability, and house price.

### Objectives

- Analyze the house price dataset using exploratory data analysis.
- Identify numerical and categorical features.
- Preprocess the data using missing-value imputation and One-Hot Encoding.
- Train a Linear Regression model to predict house prices.
- Evaluate model performance using MSE, RMSE, and R² score.
- Compare Linear Regression with Ridge Regression.

### Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

### Project Workflow

1. Load and inspect the dataset.
2. Perform data cleaning and exploratory data analysis.
3. Visualize house price distributions and numerical feature correlations.
4. Separate input features and the target variable, Price.
5. Preprocess numerical and categorical features using a pipeline.
6. Split the dataset into 80% training data and 20% testing data.
7. Train the Linear Regression model.
8. Evaluate predictions using MSE, RMSE, and R² score.
9. Visualize actual versus predicted prices and analyze residuals.
10. Compare Linear Regression with Ridge Regression.

### Model Evaluation

| Model | RMSE | R² Score |
|---|---:|---:|
| Linear Regression | 279859.73 | -0.0067 |
| Ridge Regression | 279859.01 | -0.0067 |

The Ridge Regression model achieved a very small reduction in RMSE. However, both models produced a negative R² score, indicating that their predictive performance was weak on the test dataset. Further feature engineering and evaluation of alternative regression models may help improve performance.

### Conclusion

This project demonstrates the machine learning workflow for house price prediction, including data exploration, preprocessing, model training, visualization, and evaluation. The comparison shows that further improvements are needed to obtain more accurate predictions.

### Project Files

- `House Price Prediction Dataset.csv` – Dataset used for analysis.
- `Vijayadharshini_Level2_Task1.ipynb` – Jupyter Notebook containing the analysis, preprocessing, model training, visualizations, and evaluation.

## Level 2 - Task 2: Wine Quality Prediction

### Objective
Build and evaluate machine learning classification models to predict wine quality categories using physicochemical properties.

### Dataset
- Dataset: UCI Wine Quality — White Wine
- File: `winequality-white.csv`
- Original records: 4,898
- Records after duplicate removal: 3,961
- Input features: 11 physicochemical measurements
- Target: Low, Medium, High wine quality groups

### Data Preprocessing
- Inspected dataset structure and missing values.
- Removed 937 duplicate records.
- Explored quality score distribution and feature correlations.
- Grouped quality scores into Low (5 or below), Medium (6), and High (7 or above).
- Applied an 80:20 stratified train-test split.
- Used StandardScaler within machine learning pipelines.

### Algorithms
- Random Forest Classifier
- SGD Classifier
- Support Vector Classifier (SVC)

### Model Comparison

| Model | Accuracy |
|---|---:|
| Random Forest | 60.03% |
| SVC | 56.37% |
| SGD Classifier | 50.69% |

### Feature Importance
The Random Forest model identified alcohol, density, and volatile acidity as the three most important features.

### Conclusion
Random Forest achieved the highest test accuracy of 60.03% among the evaluated models. It was selected as the preferred prototype model. Further tuning and independent validation are recommended before deployment.

### Technologies Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook.

### Files
- `winequality-white.csv` — dataset
- `Vijayadharshini_Level2_Task2.ipynb` — analysis and model training notebook

### Limitations
The model has moderate accuracy and may misclassify wine quality groups. Predictions should not be treated as definitive quality assessments.

## Level 2 - Task 3: Credit Card Fraud Detection

### Project Overview
This project uses machine learning classification algorithms to identify potentially fraudulent credit card transactions. It focuses on handling highly imbalanced data and evaluating models using fraud-specific performance metrics.

### Dataset
- **Dataset:** Credit Card Fraud Detection
- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Features:** Transaction time, anonymised numerical features (V1–V28), transaction amount, and class label.
- **Target:** Class 0 represents legitimate transactions; Class 1 represents fraudulent transactions.

### Tools and Technologies
- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

### Project Workflow
1. Loaded and inspected the transaction dataset.
2. Checked missing values and measured class imbalance.
3. Performed exploratory data analysis on transaction amounts and transaction timing.
4. Used stratified train-test splitting.
5. Applied class weighting to address the imbalance during model training.
6. Trained Logistic Regression and Random Forest classifiers.
7. Evaluated the models using Precision, Recall, F1-score, ROC-AUC, and confusion matrices.
8. Analysed Random Forest feature importance and Logistic Regression coefficients.
9. Discussed scalability requirements for processing one million transactions per hour.

### Evaluation
The models were compared using fraud detection metrics rather than accuracy alone. The final model should be selected by considering fraud recall, precision, ROC-AUC, false positives, and the cost of missed fraudulent transactions.

### Scalability
A production deployment could use a message queue, a containerised prediction API, horizontal scaling, monitoring, and regular model updates. Actual throughput and latency must be validated through load testing.

### Conclusion
This project demonstrates a machine learning workflow for credit card fraud detection and highlights the challenges of severe class imbalance. It provides a foundation for further improvements through threshold tuning, hyperparameter optimisation, and testing with newer transaction data.

### Notebook
`Vijayadharshini_Level2_Task3.ipynb`

**Note:** Download the dataset from the Kaggle source above. The raw dataset is not included in this repository due to its file size.

## Internship
**Oasis Infobyte — Data Analytics Internship**
