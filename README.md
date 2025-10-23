# MIT Data Science and Machine Learning Projects

This repository contains my project implementations from MIT's **Data Science and Machine Learning: Making Data-Driven Decisions** course. Each project applies machine learning techniques to solve real-world business problems, from customer segmentation to lead conversion prediction and recommendation systems.

## Projects

### Project 1: Customer Segmentation Analysis
**Using K-Means clustering to identify distinct customer groups for targeted marketing**

A retail company seeks to understand customer personalities and purchasing behaviours to create personalised marketing strategies. The project segments customers based on demographics, spending patterns, and engagement metrics.

- **Dataset:** Customer demographics and 2-year purchasing behaviour data
- **Techniques:** K-Means Clustering, Elbow Method, Silhouette Analysis, Feature Scaling
- **Key Results:** Identified optimal customer segments with distinct characteristics and spending patterns
- **Business Impact:** Enabled personalised marketing campaigns, targeted retention strategies, and optimised resource allocation

---

### Project 2: Lead Conversion Prediction (EdTech)
**Predicting high-potential leads using classification models to optimise sales resource allocation**

ExtraaLearn, an EdTech startup, needs to identify which leads are most likely to convert to paid customers. The project builds predictive models to prioritise leads and uncover key conversion drivers.

- **Dataset:** Lead interaction data with demographics, website engagement, and conversion status
- **Techniques:** Decision Trees, Random Forests, Hyperparameter Tuning (GridSearchCV), Feature Importance Analysis
- **Key Results:** Identified top predictors, prioritised Recall metric to minimise missed conversion opportunities
- **Business Impact:** Improved lead prioritisation, website engagement strategies, and student demographic targeting

---

### Project 3: Amazon Product Recommendation System
**Building collaborative filtering models to provide personalised product recommendations**

Amazon requires accurate recommendation systems to enhance customer experience and drive sales. The project implements multiple recommendation algorithms to predict user ratings and suggest relevant products.

- **Dataset:** Amazon Electronics reviews (65,290 ratings from 1,540 users on 5,689 products)
- **Techniques:** Rank-Based Recommendation (Popularity), User-User Collaborative Filtering (KNN with Cosine Similarity), Item-Item Collaborative Filtering (KNN with MSD), Matrix Factorization (SVD)
- **Key Results:** User-User Collaborative Filtering achieved best F1-Score, Matrix Factorization achieved lowest RMSE
- **Business Impact:** Improved product discovery, personalised recommendations, and customer engagement

---

## Technologies and Tools

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, Surprise
- **Development Environment:** Jupyter Notebook, Google Colab

## Key Concepts Covered

- **Unsupervised Learning:** K-Means Clustering, Customer Segmentation
- **Supervised Learning:** Classification (Decision Trees, Random Forests)
- **Recommendation Systems:** Collaborative Filtering, Matrix Factorization
- **Model Evaluation:** Precision, Recall, F1-Score, RMSE, Silhouette Score
- **Model Optimization:** Hyperparameter Tuning with GridSearchCV
- **Business Analytics:** Feature Importance, Actionable Insights, Strategic Recommendations


## Acknowledgments

Course provided by MIT's Professional Education program. All implementations and analyses are my own work completed as part of the course requirements.
