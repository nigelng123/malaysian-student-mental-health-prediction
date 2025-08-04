# Predicting Mental Health Among Malaysian University Students Using Machine Learning Models

This project marks the beginning of my journey into machine learning. As I graduated university not long ago, I wanted to choose a topic that I could relate to, and not just another house price or stock market predictor.
By choosing a topic like this, and analysing a dataset conducted from a university in my home country, Malaysia, just makes this project feel even more personal. It allows me to not only apply what I've learnt, but to explore a deeper issue that resonates deeply with my own experiences and peers.

The dataset used in this project is available on Kaggle:

**[University Students' Mental Health](https://www.kaggle.com/datasets/junnn0126/university-students-mental-health/data)**
# Project Summary

This project explores the mental health status of Malaysian university students and attempts to predict the likelihood of **depression, anxiety,** and **panic attacks** using machine learning models.

Using a publicly available dataset from Kaggle, the analysis includes:
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Machine Learning
- Hyperparameter Tuning
- Model Comparison

Despite relatively low predictive scores (maximum achieved ~58% accuracy), the results highlighted the complexity and unpredictability of mental health collected from survey-based data.

## Key Takeaways
- Tree based models (RandomForest, Decision Trees, XGBoost) achieved higher predictive performance over Non-Tree based models.
- Differenct preprocessing strategies were applied:
    - Ordinal encoding for tree-based models; OneHotEncoding + StandardScaling for non-tree based models (Logistic Regression, SVC, KNN).
    - Feature importance was assessed, but removing low-importance features was only adopted for tree-based models.
- Mental health prediction remains a challenging task due to its complex nature.

## Future Improvements
- For a more fair model comparison, future improvements should:
    - Integerate feature selection techniques into all models.
    - Apply consistent preprocessing steps across models.
