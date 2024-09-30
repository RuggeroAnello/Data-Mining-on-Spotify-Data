# Data Mining 2 Project

### University of Pisa - A.Y. 2023/24

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Tasks Covered](#tasks-covered)
3. [Libraries Used](#libraries-used)
4. [Authors](#authors)

---

## Project Overview
This project was conducted for the Data Mining 2 course (A.Y. 2023/24) at the University of Pisa. It covers the following tasks: Data Understanding and Preparation, Time Series Analysis, Outlier Detection, Imbalanced Learning, Advanced Regression and Classification (SVM, XGBoost, Deep Neural Networks), Explainability.

---

## Tasks Covered
The project covers the following tasks:
- **Data Understanding and Preparation**: Initial exploration and cleaning of the data. Two datasets were merged: one with 109547 Spotify tracks and 34 features and another with 30141 artist records. Key tasks included removing duplicates, handling missing values, and feature engineering. Correlation analysis led to the removal of redundant features, and key insights were gained from variable distributions.
- **Time Series Analysis**: A dataset of 20000 time series records, each containing 1280 data points, was analyzed. Structural and shape-based similarity measures were explored. Euclidean distance and Dynamic Time Warping (DTW) served as the basis for K-Means clustering with both distance measures. Motifs and discords were extracted to identify patterns and anomalies, and shapelet analysis was conducted for classification tasks. The classification methods employed included K-Nearest Neighbors (K-NN) using both Euclidean and DTW distances, shapelet-based classification with decision trees, and the ROCKET algorithm. The focus was on predicting the tracks' genre, or classifying instances into three cluster classes.
- **Outlier Detection**: The top 1% of outliers were identified and removed using these techniques: Local Outlier Factor (LOF), Histogram-based Outlier Score (HBOS), Lightweight On-line Detector of Anomalies (LODA), and Isolation Forest, including its advanced variant, Deep Isolation Forest (DIF). A "bottom-up" approach was used to first remove small numbers of pure outliers, followed by a "top-down" approach for broader detection. The final dataset, merging both strategies, reduced from 89270 to 88000 records.
- **Imbalanced Learning**: The goal was to classify tracks from Japanese genres (minority class) versus all other genres (majority class), focusing on high precision. To address the imbalance (4% minority, 96% majority), several techniques were applied. These techniques include: Random Undersampling, Cluster Centroid, Condensed Nearest Neighbor (CNN), Random Oversampling, SMOTE, ADASYN, BalancedRandomForest, and hybrid methods like SMOTEENN and Random OverSampling + Edited Nearest Neighbor.
- **Advanced Classification**: The main goal was to classify the tracks genre using advanced classification techniques, focusing on achieving high accuracy and f1 score. Several techniques were applied, including: Logistic Regression, Support Vector Machines (SVM), Gradient Boosting (XGB, LGBM, CatBoost),  Deep Neural Networks.
- **Advanced Regression**: The goal was to predict a track's popularity using advanced regression techniques. We utilized Random Forest and XGBoost regressors, testing different configurations of features to address multicollinearity and enhance results while tuning hyperparameters.
- **Explainability**: The goal was to explore the workings of an XGB model for binary classification between "explicit" and "non-explicit" tracks. We employed explainability techniques such as SHAP and LIME and identified "speechiness" and "genre" as key features influencing predictions, while also addressing challenges in interpreting complex models.

---

## Libraries Used
This project makes use of the following libraries:
- **Python**:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`
  - `xgboost`
  - `pytorch` (for Deep Neural Networks)
  - `shap` and `lime` (for Explainability)
    

Make sure to install these libraries using `pip install` if they are not already present.

---

## Authors
- **Ruggero Anello** [GitHub Profile](https://github.com/RuggeroAnello)
- **Marco Poiani** [GitHub Profile](https://github.com/MarcoPoiani00)
