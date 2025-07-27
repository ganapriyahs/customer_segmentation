### Customer Segmentation using RFM Analysis

#### Overview
This project focuses on customer segmentation for an eCommerce dataset using RFM (Recency, Frequency, Monetary) analysis.
By grouping customers based on their purchase behavior, we derive actionable insights for targeted marketing, retention strategies, and revenue maximization.

#### Project Objectives
Perform RFM analysis to segment customers based on purchasing behavior
Identify high-value, at-risk, and loyal customer groups
Use clustering (K-Means) to refine segmentation
Provide data-driven marketing recommendations

#### Dataset
Contains:
Customer IDs
Order dates
Product details
Quantity & price information

#### Methodology
Data Preparation
Handle missing values & duplicates
Remove outliers using IQR method

Exploratory Data Analysis (EDA)
Visualize purchase patterns (bar charts, histograms, heatmaps)

RFM Scoring
Recency: Days since last purchase
Frequency: Number of purchases
Monetary: Total spend

Clustering
K-Means clustering to group customers into segments

Visualization
Segment distribution, monetary contribution, and scatter plots

#### Tools & Technologies
Python (Pandas, NumPy, Scikit-learn)
Matplotlib & Seaborn for visualizations
Jupyter Notebook for analysis & documentation

#### Key Insights
Champions & Potential Loyalists are the highest value segments.
At-Risk & Lost Customers appear in low-frequency ranges (1–4 purchases).
Spending clusters between $1,000–$3,000 indicate stable revenue segments.

#### Future Work
Include seasonal trends & product preferences
Predictive churn prevention using segment movement tracking
Add cross-channel behavior for better segmentation