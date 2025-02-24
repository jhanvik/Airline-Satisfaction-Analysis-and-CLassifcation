# Airline Satisfaction Analysis and Classification

## Project Overview

This project aims to analyze airline satisfaction data and classify customer satisfaction levels using various machine learning techniques. The dataset includes various features related to customer experience and demographics. The goal is to build a predictive model that can accurately classify whether a customer is satisfied or not.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [References](#references)

## Data Description

The dataset used in this project contains various features such as:
- Flight Distance
- Inflight wifi service
- Departure/Arrival time convenient
- Ease of Online booking
- Gate location
- Food and drink
- Online boarding
- Seat comfort
- Inflight entertainment
- On-board service
- Leg room service
- Baggage handling
- Checkin service
- Inflight service
- Cleanliness
- Age
- Gender
- Class
- Customer Type
- Type of Travel
- Departure Delay
- Arrival Delay

## Data Preprocessing

Data preprocessing steps include:
- Handling missing values by dropping rows with null values.
- Encoding categorical features, such as Gender, Customer Type, Type of Travel, and Class, into numeric values.
- Replacing white spaces in column names with underscores for consistency.
- Scaling numerical features using normalization.
- Splitting the dataset into training and testing sets.

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) involves understanding the distribution of features, visualizing relationships between features and the target variable, and identifying trends and patterns in the data. Key EDA steps include:
- Counting passenger satisfaction levels.
- Analyzing passenger satisfaction with respect to Gender, Class, and Customer Type.
- Identifying missing values.

## Model Building

Various machine learning models were used to classify customer satisfaction, including:
- Random Forest Classifier
- Naive Bayes Classifier
- Decision Tree Classifier
- K-Nearest Neighbour (KNN) Classifier

## Model Evaluation

Model performance was evaluated using metrics such as accuracy, precision, recall, f1-score, and confusion matrices.

### Random Forest Classifier Results
- **Accuracy:** 96.44%
- **Precision:** High precision for both satisfied and neutral/dissatisfied classes.
- **Confusion Matrix:** Indicates strong performance in distinguishing between the two classes.
- **F1 Score:** 0.96

### Naive Bayes Classifier Results
- **Accuracy:** 86.11%
- **Precision:** Slightly lower precision compared to Random Forest.
- **Confusion Matrix:** Shows some misclassification between satisfied and neutral/dissatisfied classes.
- **F1 Score:** 0.86

### Decision Tree Classifier Results
- **Accuracy:** 94.59%
- **Precision:** Good precision across both classes.
- **Confusion Matrix:** Indicates good performance but slightly lower than Random Forest.
- **F1 Score:** 0.95

### K-Nearest Neighbour (KNN) Classifier Results
- **Accuracy:** 93%
- **Precision:** High precision for both satisfied and neutral/dissatisfied classes.
- **Confusion Matrix:** Indicates strong performance in distinguishing between the two classes.
- **F1 Score:** 0.91

## Conclusion

The project demonstrates the use of various machine learning techniques to classify airline customer satisfaction. The Random Forest Classifier achieved the highest accuracy, with a testing score of 96.44%. The performance metrics of each classifier indicate their respective strengths and areas for improvement.

## Future Work

Future improvements and extensions for this project include:
- Fine-tuning hyperparameters for better model performance.
- Exploring additional features that could impact customer satisfaction.
- Implementing advanced techniques like BiLSTM and attention mechanisms for enhanced predictive capabilities.


---

Feel free to further adjust or expand on this as needed. I hope this meets your requirements!
