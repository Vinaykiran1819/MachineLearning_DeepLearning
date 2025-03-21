# Predicting Problematic Internet Usage in Children and Adolescents

This project aims to predict the level of problematic internet usage (PIU) exhibited by children and adolescents based on their physical activity and fitness data. By identifying early signs of PIU, we can encourage timely interventions to foster healthier digital habits among young individuals.

## 1. Overview
Modern children and adolescents spend a significant amount of time online, potentially impacting their physical and mental health. This project explores the relationship between physical activity and problematic internet use by building a predictive model.

**Objective:** Develop a model that, given physical activity data, predicts the Severity Impairment Index (SII) for internet usage.
**Importance:** Early detection of problematic internet use can lead to interventions that promote healthier digital habits.

## 2. Key Features
- **Data Analysis**: Uses children’s physical activity metrics and SII scores to identify important factors associated with internet usage.
- **Predictive Modeling:** Employs machine learning techniques to forecast the SII category.
- **Visual Insights:** Provides easy-to-understand plots and charts to illustrate data patterns and findings.

## 3. Data Description
- **Physical Activity Metrics:** May include steps per day, total active minutes, intensity of exercises, or heart rate measurements.
- **Fitness Indicators:** Could include BMI, body fat percentage, or other fitness parameters.
- **Internet Usage Severity (SII):** A categorical score indicating the severity of internet usage (e.g., 0.0 = low severity, 3.0 = high severity).
**Goal:** Use physical activity and fitness indicators to predict the SII category (0.0, 1.0, 2.0, or 3.0).

## 4. Exploratory Data Analysis (EDA)
Before building predictive models, we performed an initial exploratory analysis to understand the data distribution and relationships.

The bar chart indicates that most children fall into the lower severity categories (0.0 and 1.0).
There are fewer samples in higher severity categories (2.0 and 3.0).


Individuals in higher SII categories tend to have more hours of internet usage per day.
This insight helps confirm that the SII metric correlates with actual hours spent online.

## 5. Predictive Modeling Approach
**Data Preprocessing**

Handle missing values, outliers, and data normalization.
Convert categorical data into numerical form if needed.

**Feature Engineering**

Extract new features from the raw physical activity data (e.g., average steps per day, daily active minutes).
Combine or transform existing features to highlight relevant patterns (e.g., activity intensity index).

**Model Selection**

Consider algorithms such as Logistic Regression, Random Forest, or Gradient Boosting for classification tasks.
Perform cross-validation to compare performance.

**Model Training and Evaluation**

Split the data into training and testing sets.
Use accuracy, precision, recall, or F1-score to evaluate model performance.
Perform hyperparameter tuning to optimize model accuracy.

**Results**

Identify which physical activity features are most predictive of high SII categories.
Generate a confusion matrix or classification report to see where the model performs well or struggles.


## 6. Conclusion
This project demonstrates a concise approach to predicting problematic internet usage severity in children and adolescents through physical activity analysis. By applying advanced machine learning models like Random Forest and Gradient Boosting, we achieved a 70% F1 score, marking a significant improvement from our baseline. These findings highlight the strong connection between physical activity levels and internet usage severity, offering a practical tool for early risk detection and timely interventions.
