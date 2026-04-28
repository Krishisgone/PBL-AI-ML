# PBL-AI-ML

**An end-to-end machine learning system that preprocesses campus Wi-Fi data, performs EDA and feature selection, and builds classification models to accurately predict network congestion.**

Question_Statement--> Design and develop an end-to-end machine learning classification system to analyze and predict congestion in campus Wi-Fi networks using network performance data. The project involves selecting a suitable campus Wi-Fi dataset containing numerical features such as the number of connected devices, network latency, packet loss rate, bandwidth usage, and access point load. Data preprocessing steps including data cleaning, normalization, and transformation are applied to ensure data quality and consistency. Exploratory Data Analysis is performed to study the distribution of network metrics, visualize network behavior, identify congestion periods, detect anomalies, and analyze relationships between different network parameters using statistical summaries and visualizations. Correlation analysis is used to understand how network features 
influence congestion. Based on insights obtained from EDA, relevant features are selected to improve model performance(PCA,Forward Selection,Backward Selection). Machine learning classification models are then developed to predict network congestion using appropriate algorithms. The trained models are evaluated using standard classification performance metrics(accuracy) to assess their effectiveness, supporting improved network management and decision-making.

🔍 Phase 1: Data Cleaning & Exploratory Data Analysis

In this phase, the dataset was first loaded and carefully examined to understand its structure, features, and data types. Data cleaning steps were performed to handle missing values, remove duplicates, and fix inconsistencies to ensure data quality. After preprocessing, exploratory data analysis (EDA) was conducted using statistical summaries and visualizations to identify patterns, distributions, and potential outliers. This phase helped build a strong understanding of the dataset and revealed important relationships between features that would guide further processing and modeling.

⚙️ Phase 2: Feature Engineering & Preprocessing

This phase focused on transforming the cleaned data into a suitable format for machine learning. Features were analyzed and grouped based on their relevance, and correlations were studied to understand their impact on the target variable, Disease Risk. Outliers were detected and handled to improve data reliability. Categorical variables (if present) were encoded, and important features were selected to reduce noise. Additionally, feature scaling techniques were applied to standardize the data, and dimensionality reduction (such as PCA) was used to improve efficiency while preserving essential information.

🤖 Phase 3: Model Building & Evaluation

In the final phase, the processed dataset was split into training and testing sets to ensure proper evaluation of model performance. Various machine learning models were implemented and trained using the prepared data. The models learned patterns from the features and were evaluated using appropriate metrics such as accuracy and performance scores. A comparison of different models was carried out to identify the best-performing one. This phase provided insights into prediction capability and highlighted the effectiveness of preprocessing and feature engineering steps in improving overall model performance.
