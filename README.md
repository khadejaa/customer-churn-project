# Customer Churn Prediction

This project aims to predict customer churn for a music streaming platform using historical user activity data. The notebook walks through data cleaning, exploratory data analysis, feature engineering, and machine learning model building.

---

## **Project Overview**
Customer churn is when users stop using a service or unsubscribe. Predicting churn is crucial for implementing retention strategies.  
In this project, we analyze user behavior data and build machine learning models to predict the likelihood of churn.

---

## **Key Steps**
1. **Load and Clean Dataset**  
   - Load JSON files containing user logs.
   - Handle missing values and remove invalid rows.
   - Convert timestamps to datetime format.
   - Derive features such as subscription days.

2. **Exploratory Data Analysis (EDA)**  
   - Analyze distributions of user activity.
   - Compare behaviors of churned vs. active users.
   - Visualize metrics like page visits, session lengths, and artist interactions.

3. **Feature Engineering**  
   - Extract features such as:
     - Number of unique artists listened to.
     - Total number of sessions.
     - Days since registration.
     - Browser and platform information from `userAgent`.
   - Encode categorical variables and scale features.

4. **Model Building**  
   - Split data into training and test sets.
   - Train machine learning models Logistic Regression.
   - Evaluate model using metrics accuracy and F1-score.

---

## **Installation**
To run the notebook, ensure you have Python 3.8+ and install the required dependencies:


## Key Libraries:

pandas
numpy
matplotlib
scikit-learn

## How to Use

Clone the repository:
git clone <repo-url>
Open the notebook:
jupyter notebook Customer_Churn.ipynb
Run the cells step by step to reproduce the analysis and model training.

## Project Structure

.
├── Customer_Churn.ipynb   # Main notebook
├── requirements.txt        # Dependencies
├── data/                   # Folder for datasets
└── README.md               # Project description

## Future Improvements

Deploy the trained model via a FastAPI endpoint.
Add Docker support for reproducible environments.
Implement automated retraining and model monitoring (e.g., using Evidently).
Author

Developed by [Your Name].
Feel free to contribute or raise issues in this repository.
