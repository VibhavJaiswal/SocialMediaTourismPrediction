# SocialMediaTourismPrediction

🚀 Social Media Tourism Prediction
🎯 Project Overview

This project aims to help an aviation company optimize its digital marketing strategy by predicting customer interest in travel packages based on their social media behavior. By analyzing user interactions, such as likes, comments, and check-ins, we build machine learning models to enhance targeted advertising.

📌 Key Objectives:

    Analyze social media data to understand customer travel behavior.
    Build predictive models to determine users' probability of purchasing travel packages.
    Optimize targeted digital advertisements to increase revenue while minimizing ad spend.
    Develop separate models for Laptop and Mobile users due to behavioral differences.

    📊 Data Description

The dataset contains social media interaction data from 11,760 users with 17 features, including:

    User engagement metrics: Likes, comments, and check-ins related to travel.
    Demographic data: Family size, working status, and preferred location type.
    Device type: Laptop vs. Mobile users for segmented modeling.

💡 Data Preprocessing:

    Handling missing values using mode/median imputation.
    Outlier detection & treatment using the IQR method.
    Feature scaling using StandardScaler for numerical features.
    Balancing classes using SMOTE due to data imbalance.