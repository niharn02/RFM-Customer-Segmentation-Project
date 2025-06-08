
# RFM Customer Segmentation using K-Means Clustering

This project applies RFM (Recency, Frequency, Monetary) analysis and unsupervised machine learning to segment customers based on their purchasing behaviour. The goal is to support data-driven marketing strategies by identifying customer groups with similar characteristics.

## Objective

To group customers into actionable segments using clustering techniques. These segments help businesses:

- Improve customer retention
- Personalise marketing strategies
- Identify and recover at-risk customers
- Focus on high-value customer groups

## Dataset Overview

The dataset is composed of four CSV files derived from customer order data:

- `customers.csv` – Customer information
- `orders.csv` – Order IDs and order dates
- `order_details.csv` – Transaction-level data (sales, quantity, discount)
- `products.csv` – Product information (not used in this analysis)

## Tools and Libraries

- Python
- Pandas, NumPy
- Scikit-learn (KMeans, StandardScaler)
- Matplotlib, Seaborn

## Workflow Summary

1. **Data Loading and Merging**  
   All four CSVs are merged into a single transactional dataset.

2. **RFM Metric Calculation**  
   For each customer:
   - Recency: Days since last purchase
   - Frequency: Number of unique purchases
   - Monetary: Total amount spent

3. **Data Preprocessing**  
   RFM features are scaled using `StandardScaler` to normalise value ranges.

4. **K-Means Clustering**  
   - The elbow method is used to determine the optimal number of clusters
   - K-Means is applied to group customers into distinct behavioural segments

5. **Cluster Interpretation and Segment Labelling**  
   Clusters are interpreted based on their average RFM characteristics and labelled accordingly (e.g., High Value Loyalists, At Risk, Lost Customers).

6. **Data Export**  
   The final customer segmentation dataset is saved as a CSV file for reporting or dashboard use (e.g., in Power BI).

## Deliverables

- `RFM_Segmentation.ipynb` – Python notebook with the full analysis and visualisation
- `rfm_customer_segments.csv` – Final dataset with RFM scores, cluster labels, and segment names
- `README.md` – Documentation describing the purpose, process, and outcome of the project

## Business Impact

RFM segmentation provides valuable insights into customer behaviour, enabling businesses to:

- Target marketing efforts more effectively
- Design loyalty programmes for high-value customers
- Create re-engagement campaigns for at-risk groups
- Optimise budget allocation by focusing on the most impactful customer segments
