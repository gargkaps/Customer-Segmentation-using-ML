# Customer-Segmentation-using-ML
This project explores the Online Retail Dataset from the UCI Machine Learning Repository. It contains transactions from a UK-based online gift retailer between December 2010 and December 2011.

Dataset Link : https://archive.ics.uci.edu/ml/datasets/online+retail

Project Workflow:
Data Understanding: Explored variables like InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, and Country.

Data Cleaning: Handled missing Customer IDs, removed canceled transactions (InvoiceNo with 'C'), and dropped duplicates.

Feature Engineering: Created new variables such as TotalPrice (Quantity × UnitPrice) and aggregated metrics per customer.

Exploratory Data Analysis (EDA): Identified top-selling products, customer segments, and sales trends.

RFM Analysis: Used Recency, Frequency, and Monetary value to segment customers and identify key groups.

Clustering: Applied K-Means to classify customers based on RFM scores.

Outlier Treatment: Detected and handled outliers in quantity and price.

Time-Series Analysis: Analyzed monthly sales trends to detect seasonality.

Market Basket Analysis: Performed association rule mining using the Apriori algorithm.

Visualization: Created insightful plots using Seaborn and Matplotlib to communicate findings.

🔍 The project provides actionable insights into customer behavior, sales trends, and inventory performance.
