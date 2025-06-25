🚚 **Supply Chain Optimization Project**

**Predicting On-Time vs. Late Deliveries**

This repository contains my end-to-end supply chain optimization work for DataCo, where the goal was to forecast whether shipments would be delivered on time or late, and to surface insights through interactive dashboards.

📂 **Repository Structure**

├── DataCo Transformation.ipynb       # Data cleaning & preprocessing steps

├── Hypothesis_BigData.ipynb         # Exploratory data analysis and hypothesis testing

├── Modelling.ipynb                  # Baseline models and evaluation metrics

├── RF_DT_XGBoost.ipynb              # Random Forest, Decision Tree & XGBoost implementations

├── SVM_Model.ipynb                  # Support Vector Machine regression/classification

├── DataCoSupplyChainDataset.csv     # Raw supply chain dataset

├── DescriptionDataCoSupplyChain.csv # Metadata & feature descriptions

├── tokenized_access_logs.csv        # Tokenized log data used for feature engineering

└── README.md                        # Project overview and instructions (this file)

📝 **Project Overview**

Objective: Predict whether a shipment will arrive on time or late, enabling DataCo to optimize logistics and reduce delays.

**Approach:**

**Data Preprocessing**

Cleaned and merged raw datasets

Handled missing values, encoded categorical variables, and engineered time-based features

**Exploratory Analysis**

Validated hypotheses around delivery times vs. factors like carrier, distance, and order priority

**Model Development**

Built baseline classification models (Logistic Regression, Decision Tree)

Implemented ensemble methods: Random Forest & XGBoost

Explored SVM for classification performance

**Evaluation & Tuning**

Used cross-validation and metrics (accuracy, precision, recall, F1-score)

Performed hyperparameter tuning (GridSearchCV, RandomizedSearchCV)

📊 **Results & Insights**

Random Forest achieved ~92% accuracy in predicting on-time vs. late deliveries.

Feature Importance highlighted that distance, order priority, and carrier reliability are top predictors.
