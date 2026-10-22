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

## Internship
**Oasis Infobyte — Data Analytics Internship**
