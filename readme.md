# Algerian Forest Fire Prediction

This project aims to analyze and predict forest fires in Algeria using the Fire Weather Index (FWI). The analysis includes data processing, visualization, and model training using Logistic Regression. Additionally, cross-validation and hyperparameter tuning are applied to improve model performance, and the final model is saved for testing on unseen data.

## Project Structure

- `Assignment_one.ipynb`: Jupyter notebook containing the data analysis, visualization, logistic regression model, cross-validation, and hyperparameter tuning.
- `model.pkl`: Pickle file of the trained model.
- `README.md`: Project documentation.
- `requirements.txt`: List of dependencies to set up the environment.

## Dataset

The dataset used for this project focuses on forest fires in Algeria. The dataset includes various meteorological factors such as temperature, humidity, and rain, which contribute to the Fire Weather Index (FWI), a critical measure for predicting forest fires.

## Analysis Steps

1. **Data Processing**: Cleaning and preprocessing of the dataset, including handling missing values and encoding categorical variables.
2. **Visualization**: Exploratory Data Analysis (EDA) using graphs to understand trends and patterns in the data.
3. **Model Training**: A logistic regression model is trained to classify fire occurrence based on FWI-related features.
4. **Cross-Validation and Hyperparameter Tuning**: Model performance is evaluated and optimized using cross-validation techniques.
5. **Model Persistence**: The trained model is saved as a pickle file for testing on new, unseen data.

## Installation

To run this project, install the necessary dependencies using:

```bash
pip install -r requirements.txt
