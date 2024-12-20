# Students Adaptability Level in Online Education

Welcome to the **Student Adaptability in Online Education** project! This repository contains a custom implementation of machine learning models for classification tasks, built with Python. The project focuses on analyzing and predicting students' adaptability levels in online education using data from Kaggle.

## Components

1. **Dataset**: Kaggle - Students Adaptability Level in Online Education.
2. **Feature Extraction**: Data preprocessing and feature engineering.
3. **Machine Learning Models**: Decision Tree, Random Forest, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and XGBoost.

## Dataset

The dataset contains information about students' adaptability levels in online education, including various demographic, social, and technical factors that influence their learning experiences. The data helps in training and testing predictive models to classify students' adaptability into distinct levels.

### Dataset Features

1. **Gender**: Male/Female.
2. **Age Group**: Different age categories.
3. **Educational Stage**: Primary, Secondary, or Higher Education.
4. **IT Usage**: Frequency and comfort with technology.
5. **Adaptability Level**: Target variable (Low, Medium, High).

The dataset is publicly available on Kaggle.

## Project Workflow

### 1. Data Preparation

Ensure the dataset is formatted correctly, with features stored in a CSV file. Preprocess the data to:

- Handle missing values.
- Normalize/scale features.
- Encode categorical variables.

### 2. Model Implementation

We use the following machine learning models to classify students' adaptability levels:

- **Decision Tree**: A tree-based algorithm that splits data based on feature values.
- **Random Forest**: An ensemble of decision trees for improved accuracy and robustness.
- **K-Nearest Neighbors (KNN)**: A distance-based classifier.
- **Support Vector Machine (SVM)**: A model that finds the hyperplane maximizing class separation.
- **XGBoost**: A gradient boosting algorithm for high-performance classification.

### 3. Training the Models

Each model is trained through:

- Splitting the data into training and validation sets.
- Hyperparameter tuning for optimal performance.
- Training the models and calculating metrics.

### 4. Evaluation

Evaluate the trained models using:

- **Accuracy**: Percentage of correctly classified instances.
- **Precision, Recall, F1 Score**: Additional metrics for detailed analysis.
- **Confusion Matrix**: Visualize prediction results.

### 5. Results

The best accuracy achieved was **90.7%**, using the **XGBoost** model. This demonstrates strong performance in predicting students' adaptability levels.

### Contributing
We welcome contributions to improve the model and its performance. If you'd like to contribute, please fork the repository, make your changes, and submit a pull request. We appreciate your contributions and will review them promptly.

### License
MIT

This project is licensed under the MIT License, allowing you to freely use, modify, and distribute the software.

