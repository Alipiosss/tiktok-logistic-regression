# TikTok Verified Status Prediction using Logistic Regression

## 📊 Overview

This project is part of the **Google Advanced Data Analytics Certificate – Course 5 Final Project**. It involves building a **logistic regression model** in Python to predict whether a TikTok user is verified based on video-level characteristics. The motivation stems from an earlier observation: **verified accounts are more likely to post opinions than factual claims**. Thus, predicting verified status serves as a foundational step to ultimately classify user-generated video content as either opinion or claim.

## 🧠 Objective

The goal was to:

- Perform exploratory data analysis (EDA) and assess data quality.
- Build a logistic regression model using relevant video features.
- Evaluate model performance using metrics such as precision, recall, F1-score, and accuracy.
- Interpret model coefficients to understand which features are most predictive of user verification status.
- Use this information to support the upcoming classification of claim vs. opinion content.

## 📁 Files

- `tiktok-logistic-regression.ipynb`: Complete notebook with EDA, data preprocessing, model training, evaluation, and interpretation.
- `tiktok_dataset.csv`: TikTok video dataset used for regression modeling.
- `Activity-TikTok-Course-5-executive-summary (SA).pdf`: Executive summary presented to the TikTok leadership team.
- `README.md`: Project summary and documentation.


## ✅ Project Status

A logistic regression model was trained on a balanced dataset. It achieved:

- **Precision:** 61%
- **Recall:** 84%
- **Accuracy:** 65%

These results indicate acceptable predictive performance. The strongest insight is that **longer videos slightly increase the odds of the account being verified**, while other features like view count, downloads, and comment count showed weaker associations.


## 🔍 Key Insights

- **Video duration** is the strongest predictor of verification status.
- Other features (views, shares, downloads, comments, ban status) had minimal predictive power.
- The model shows high recall for identifying verified users, aligning with the project’s strategic goal.


## 🚀 Next Steps

The next phase will involve **building a classification model to predict whether a video is a factual claim or an opinion**. Insights from the verified status model will be integrated into this final model to better understand content origin and user behavior.


## 🧩 Technologies Used

- Python 3
- pandas, NumPy
- seaborn, matplotlib
- scikit-learn (LogisticRegression, OneHotEncoder, train_test_split, classification_report, confusion_matrix)


## 🛡️ License

This project is for educational purposes under the guidelines of the Google Advanced Data Analytics Certificate. No commercial use intended.


## 👤 Author

**Suzana Alípio**  
Advanced Data Analytics Student  
Cosmoscenery Analytics

