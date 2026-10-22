# Customer Segmentation Analysis

## Project Overview
Customer Segmentation Analysis is a data analytics project completed as part of the Oasis Infobyte Data Analytics Internship. It uses customer purchase data to identify different customer groups based on their purchasing behaviour.

## Objective
The main objective is to segment customers using Recency, Frequency, and Monetary (RFM) analysis and provide insights that can support targeted marketing strategies.

## Tech Stack
- Python
- Pandas
- Scikit-learn
- K-Means Clustering
- StandardScaler
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow
1. Load and inspect the dataset.
2. Clean missing, invalid, and inconsistent records.
3. Perform descriptive statistical analysis.
4. Calculate RFM features.
5. Standardize the clustering features using StandardScaler.
6. Apply K-Means clustering.
7. Use the Elbow Method to select a reasonable number of clusters.
8. Visualize customer segments using scatter plots.
9. Analyse cluster profiles and customer counts.
10. Calculate historical Customer Lifetime Value (CLV).
11. Develop marketing insights and recommendations.

## Customer Segmentation Results
The analysis used K-Means with K = 3 as a reasonable clustering choice based on the Elbow Method.

The customer segments were compared using their RFM characteristics and historical revenue.

- Cluster 0: Lower average historical customer spending.
- Cluster 1: Regular-value segment with the largest customer count and highest total revenue.
- Cluster 2: High average historical customer spending, representing a small customer group.

## Historical CLV Analysis
The analysis identified 4,338 unique customers. The average historical CLV was 2,048.69, the highest was 280,206.02, and the lowest was 3.75.

These figures represent historical purchase revenue, not predicted future customer value.

## Marketing Recommendations
- Lower-value customers: Offer relevant promotions and repeat-purchase incentives.
- Regular-value customers: Encourage loyalty and cross-selling.
- High-value customers: Provide personalized rewards and retention campaigns.

## How to Run
1. Install Python.
2. Install the required libraries:

   `pip install pandas numpy scikit-learn matplotlib seaborn jupyter`

3. Open Jupyter Notebook.
4. Open `Customer_Segmentation_Analysis.ipynb`.
5. Run the notebook cells in order.

## Conclusion
The project demonstrates how RFM analysis and K-Means clustering can be used to understand customer purchasing behaviour and develop data-driven marketing recommendations.

## Internship
Oasis Infobyte – Data Analytics Internship

## Disclaimer
The clustering results depend on the dataset, preprocessing steps, and selected features. Historical CLV should not be interpreted as a prediction of future revenue.