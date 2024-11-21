# JEErney - JEE Aspirants Support System

**JEErney** is a comprehensive platform designed to assist JEE aspirants in managing stress, predicting JEE Mains percentile based on marks, analyzing JEE Advanced trends, and understanding subject-wise difficulty levels. It leverages machine learning algorithms and exploratory data analysis (EDA) to provide valuable insights and predictions, helping students navigate their JEE preparation journey with ease.

## Features

### 1. **Stress Level Prediction Model**
   - This feature uses machine learning algorithms to predict stress levels in JEE aspirants based on various factors, including:
     - **Psychological**: anxiety, self-esteem, mental health history, depression
     - **Physiological**: headache, blood pressure, sleep quality, breathing problems
     - **Environmental**: noise levels, living conditions, safety, basic needs
     - **Academic**: academic performance, study load, teacher-student relationship, future career concerns
     - **Social**: social support, peer pressure, extracurricular activities, bullying
   - **Algorithms Used**: Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors, Gaussian Naive Bayes
   - **Best Performing Models**: Random Forest and Gradient Boosting
  
### 2. **JEE Mains Marks-Based Percentile Prediction Tool**
   - Predicts JEE Mains percentiles based on marks using historical data from JEE Mains 2024 and 2023.
   - **Algorithms Used**: Linear Regression, Random Forest, Gradient Boosting, Decision Tree, K-Nearest Neighbors
   - **Best Performing Model**: Gradient Boosting with R² = 0.70964 and MSE = 2.533

### 3. **JEE Advanced Analysis**
   - **Marks (in Percentage) vs Rank**: Analysis of the relationship between marks and rank using JEE Advanced data from 2013 to 2024.
   - **Type of Questions**: Exploratory Data Analysis (EDA) on the types of questions asked in JEE Advanced.
   - **Subject-wise Difficulty Levels**: EDA on the difficulty levels for Chemistry, Physics, and Mathematics in JEE Advanced.

### 4. **Exploratory Data Analysis (EDA)**
   - Conducts EDA on various aspects of the JEE exam to help students understand patterns, trends, and strategies.
   - **Insights from EDA**: 
     - Correlation between stress levels and other factors
     - Relationship between marks and rank in both JEE Mains and JEE Advanced
     - Breakdown of subject-wise difficulty levels
    
# Contributing
We welcome contributions! If you'd like to contribute to the project, feel free to fork the repository and create a pull request.
Please follow these steps for contributions:

Fork the repository
Create a new branch (git checkout -b feature-branch)
Make changes and commit them (git commit -am 'Add new feature')
Push to the branch (git push origin feature-branch)
Create a pull request

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgments
PHQ-9 and Rosenberg Self-Esteem Scale: For stress level analysis
JEE Mains 2024 and 2023 Data: For percentile prediction
JEE Advanced 2013-2024 Data: For advanced analysis

### Stress Level Prediction Model Accuracy

| Model                       | Train Accuracy | Test Accuracy |
|-----------------------------|----------------|---------------|
| Logistic Regression          | 89.2%          | 89.1%         |
| Decision Tree Classifier     | 100%           | 88.5%         |
| Random Forest Classifier     | 100%           | 89.4%         |
| K-Nearest Neighbors          | 89.4%          | 88.2%         |
| Gaussian Naive Bayes         | 87.5%          | 90%           |

### JEE Mains Percentile Prediction Model Performance

| Model             | MSE  | R²    |
|-------------------|------|-------|
| Linear Regression | 3.99 | 0.542 |
| Random Forest     | 2.79 | 0.679 |
| Gradient Boosting | 2.533| 0.70964 (Best)|
| Decision Tree     | 3.369| 0.613 |
| K-Nearest Neighbors | 3.19 | 0.63 |


