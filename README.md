# Wine Quality Prediction Project

![Project Overview](Wine_Quality_Prediction.html)

## Project Overview
This project aims to predict the quality of (red and white wine) based on physico-chemical properties using three machine learning models:
1. Logistic Regression
2. Random Forest Classifier
3. Gradient Boosting Classifier

## Dataset
The project uses the "Wine Quality" dataset, which consists of red and white wine samples. The datasets include various chemical properties such as:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (Target variable, 0-10)

## Project Structure
- `Wine_Quality_Prediction.ipynb`: Jupyter notebook containing the complete data analysis, visualization, and model building workflow.
- `Wine_Quality_Prediction.html`: Exported HTML version of the notebook for quick viewing.
- `wine_quality_rf_model.pkl`: Saved Random Forest model.
- `wine_scaler.pkl`: Saved scaler for preprocessing.
- `winequality-red.csv`: Dataset for red wine.
- `winequality-white.csv`: Dataset for white wine.

## Machine Learning Models
Three classifiers were implemented and evaluated:
- **Logistic Regression**: A baseline model for binary/multiclass classification.
- **Random Forest Classifier**: An ensemble learning method for classification.
- **Gradient Boosting Classifier**: A powerful boosting technique for improving prediction accuracy.

## Workflow
1. **Environmental Setup**: Importing necessary libraries (pandas, numpy, scikit-learn, etc.).
2. **Data Acquisition**: Loading the datasets.
3. **Dataset Integration**: Combining red and white wine data.
4. **Descriptive Analysis**: Performing exploratory data analysis (EDA) and checking data integrity.
5. **Advanced Visual EDA**: Generating heatmaps and quality target distribution plots.
6. **Data Preprocessing**: Scaling features and splitting data into training and testing sets.
7. **Model Development**: Training the three classifiers.
8. **Evaluation**: Comparing model performance using accuracy and classification reports.

## Requirements
To run this project, you need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage
Open `Wine_Quality_Prediction.ipynb` in a Jupyter environment to explore the project.

---
*Created by Sagar Dahal*
