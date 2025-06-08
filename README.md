
# Superstore Sales Analysis and Customer Segmentation

This project provides a complete data analysis case study using the Superstore dataset. It includes data cleaning and analysis using SQL, interactive dashboard creation using Power BI, and customer segmentation using Python. The goal is to understand sales trends, identify profitable segments, and support business decision-making with data.

## Objective

The main goals of this project are:
- To identify the most profitable products, categories, and customers
- To understand how discounts impact overall profit
- To build a clear and interactive dashboard for business users
- To segment customers based on purchasing behaviour using machine learning

## Dataset Overview

The dataset is available on Kaggle:  
[Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

It was divided into four structured CSV files:
- `customers.csv`: Customer information
- `orders.csv`: Order details and dates
- `order_details.csv`: Sales, quantity, discount, profit
- `products.csv`: Product categories and sub-categories

## Tools Used

- MySQL and phpMyAdmin for data extraction and SQL queries
- Power BI for visualisation and dashboard creation
- Python (Jupyter Notebook) for analysis and customer segmentation
- Libraries: pandas, seaborn, matplotlib, scikit-learn

## Project Workflow

### Phase 1: SQL Analysis
- Created relational tables from CSV files
- Wrote queries to calculate sales, profit, profit margin
- Identified top products and customers
- Analysed the impact of discounts and category-level profitability

### Phase 2: Power BI Dashboard
- Connected MySQL to Power BI
- Created KPI cards, sales trend charts, profit margin visuals
- Added slicers for region, segment, and order month
- Included insights and back buttons using bookmarks

### Phase 3: Exploratory Data Analysis (Python)
- Loaded and explored the dataset in Jupyter Notebook
- Created visualisations like histograms, boxplots, and heatmaps
- Confirmed SQL insights and analysed data distribution

### Phase 4: RFM Customer Segmentation
- Calculated Recency, Frequency, and Monetary metrics
- Normalised data and applied K-Means clustering
- Identified and labelled customer segments such as Loyal, Lost, and Potential customers
- Exported final segmentation data for reporting

## Project Files

- `SQL_Analysis.sql`: All key SQL queries used
- `PowerBI_Dashboard.pbix`: Interactive Power BI dashboard
- `RFM_Segmentation.ipynb`: Python notebook for customer segmentation
- `rfm_customer_segments.csv`: Final clustered customer dataset
- `Project_Report.docx`: Detailed documentation and explanation
- `README.md`: This file

## Business Value

This analysis helps businesses:
- Focus on high-value customers
- Adjust discount strategies to protect profit
- Improve decision-making through interactive reporting
- Personalise marketing using customer segments

## License

This project is released under the MIT License. You can use or adapt the work with proper credit.

Author: Nihar Nandanwar  
GitHub: https://github.com/niharn02
