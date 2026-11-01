# Diabetes Prediction Using Data Mining

## Project Overview

This project is an academic Data Mining project developed by a two-member team as part of the Information Technology program at Aljanad University for Science and Technology.

The project focuses on applying data mining techniques to analyze medical data and identify patterns associated with diabetes. It uses exploratory data analysis, data preprocessing, and machine learning classification to predict the likelihood of diabetes based on selected medical and biological indicators.

The system also provides an interactive interface for exploring datasets, analyzing patterns, entering patient information, generating predictions, and exporting updated data.

## Project Objectives

- Explore and understand diabetes-related datasets.
- Identify patterns and relationships among medical attributes.
- Prepare and transform data for mining and analysis.
- Apply classification techniques to predict diabetes risk.
- Evaluate the performance of the classification model.
- Provide an interactive environment for data exploration and prediction.

## Data Mining Process

### 1. Data Collection and Loading
- Load datasets from CSV files.
- Validate the dataset and its required columns.
- Generate synthetic data as an alternative when the original dataset is unavailable.

### 2. Exploratory Data Analysis (EDA)
- Examine dataset structure and statistical information.
- Analyze distributions of medical attributes.
- Explore relationships and correlations between features.
- Generate visualizations and correlation matrices.

### 3. Data Preprocessing
- Handle missing values.
- Apply standardization to numerical features.
- Build a preprocessing pipeline using Scikit-learn.

### 4. Classification and Prediction
- Apply the Random Forest classification algorithm.
- Train the model using the prepared dataset.
- Predict diabetes risk based on patient input.

### 5. Model Evaluation
Evaluate the classification model using:
- Accuracy
- Precision
- Recall
- ROC-AUC
- Classification Report

### 6. Pattern and Feature Analysis
- Analyze feature importance.
- Identify the medical attributes that contribute to the model's predictions.

## Key Features

- CSV dataset loading and validation.
- Support for synthetic alternative data.
- Exploratory data analysis and visualization.
- Data preprocessing pipeline.
- Random Forest classification.
- Model performance evaluation.
- Feature importance analysis.
- Interactive data exploration and prediction interface.
- Model retraining and dataset updates.
- Export updated datasets to CSV.

## Interactive User Interface

The application uses `ipywidgets` to provide an interactive interface organized into five tabs:

1. **Data Information:** Displays dataset information and statistics.
2. **Data Samples:** Explores available dataset records.
3. **Plots and Analysis:** Displays visualizations and analytical results.
4. **Patient Input:** Accepts medical indicators and generates predictions.
5. **Export:** Exports updated data to CSV.

## Medical Attributes

The prediction process uses the following attributes:

- Glucose
- BMI
- Age
- Blood Pressure
- Insulin

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Random Forest
- ipywidgets
- Jupyter Notebook

## Object-Oriented Programming

The application uses object-oriented programming principles through the `DiabetesApp` class, which encapsulates the application's main functionality and components.

## My Role and Contributions

As one of the two team members, my contributions included:

- Contributing to the application's software architecture and class design.
- Implementing data loading and validation.
- Developing the data preprocessing pipeline using Scikit-learn.
- Participating in Random Forest model training and evaluation.
- Contributing to the interactive user interface.
- Implementing prediction, model retraining, and data export functionality.

## Academic Information

- **Project Type:** Academic Team Project
- **Course:** Data Mining
- **Academic Level:** Fourth Level
- **Field:** Information Technology
- **Team Size:** 2 Members

## Learning Outcomes

- Understanding the data mining workflow.
- Applying exploratory data analysis techniques.
- Preparing and transforming datasets.
- Implementing classification algorithms.
- Evaluating machine learning models.
- Analyzing feature importance and data relationships.
- Integrating data mining techniques into an interactive application.

## Disclaimer

This project is developed for academic and educational purposes only. Its predictions are not intended for medical diagnosis or to replace professional medical advice.
