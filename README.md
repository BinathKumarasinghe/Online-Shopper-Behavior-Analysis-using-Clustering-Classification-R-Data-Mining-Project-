📊 Online Shopper Behavior Analysis

This project explores online consumer behavior using advanced data mining and machine learning techniques. It focuses on understanding browsing patterns, segmenting users, and predicting purchase intentions using the Online Shoppers Intention dataset.

🔍 Project Overview

With the rapid growth of e-commerce, understanding customer behavior is essential for improving user experience and optimizing digital strategies. This project applies:

Clustering Techniques to identify customer segments
Classification Models to predict purchase intentions

It also connects insights to public-sector applications, including digital service optimization and policy-making.

⚙️ Technologies Used

R Programming
dplyr, tidyverse – Data preprocessing
ggplot2, factoextra – Visualization
dbscan, cluster – Clustering
class, e1071, rpart – Machine learning models

🧹 Dataset

Dataset: Online Shoppers Intention
Records: 12,330
Features: 18 (behavioral + session-based attributes)
Target Variable: Revenue (Purchase / No Purchase)

🔗 Clustering Analysis

Techniques Used
K-Means Clustering
DBSCAN
Hierarchical Clustering
Key Steps
Feature selection (numerical variables)
Min-max normalization
Elbow method to determine optimal clusters (K = 3)
Silhouette analysis for evaluation

📈 Results

Identified 3 distinct customer segments
Silhouette Scores:
Cluster 1: 0.625
Cluster 2: 0.724
Cluster 3: 0.427

🔑 Insights

Low engagement users → Need UX improvements
High interaction but high exit users → Checkout optimization required
Seasonal buyers → Opportunity for targeted promotions

🤖 Classification Analysis

Models Used
K-Nearest Neighbors (KNN)
Naive Bayes
Decision Tree
Workflow
Data normalization
Train-test split (70/30)
Hyperparameter tuning (K optimization for KNN)
Model evaluation using multiple metrics

📊 Evaluation Metrics

Accuracy
Precision
Recall
F1-Score
ROC Curve (AUC)

📉 Key Results (Decision Tree Example)

Precision: 0.29
Recall: 0.36
F1-Score: 0.32

🔑 Insights

Models perform better at predicting non-purchase behavior
Class imbalance affects predictive performance
Significant opportunity for model improvement

🌍 Real-World Applications

E-commerce customer segmentation
Purchase intent prediction
Marketing campaign optimization
Public-sector digital service improvement
Fraud detection and user behavior monitoring

🎯 Conclusion

This project demonstrates how combining clustering and classification techniques can provide deep insights into user behavior and support both business and public-sector decision-making. It highlights the importance of data-driven strategies in improving digital experiences and optimizing outcomes.
