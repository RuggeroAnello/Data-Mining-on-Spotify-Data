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
- **Outlier Detection**: Complete but undergoing code cleaning.
- **Imbalanced Learning**: Complete but code refinement in progress.
- **Advanced Regression and Classification**: Finished, awaiting final code adjustments. Methods include SVM, XGBoost, and Deep Neural Networks.
- **Explainability**: Implementation of explainability techniques (SHAP, LIME) is done, but the code is being optimized.

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
