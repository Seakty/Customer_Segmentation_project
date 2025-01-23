# Customer Segmentation Analysis and Prediction

## Overview
This project focuses on analyzing customer data to classify individuals into predefined segments based on their demographic and behavioral attributes. The segmentation helps businesses better understand their customers and tailor strategies for improved engagement and personalization.

## Key Objectives
1. Perform data preprocessing and feature engineering to prepare the dataset for machine learning.
2. Build, evaluate, and optimize multiple classification models to predict customer segments.
3. Derive insights into the most significant features contributing to customer segmentation.

## Process
1. **Data Exploration**: Cleaned, encoded, and analyzed the dataset to understand patterns and address class imbalances.
2. **Feature Selection**: Used Gradient Boosting and Recursive Feature Elimination to identify key features.
3. **Modeling**: Trained and evaluated Logistic Regression, SVM, Decision Tree, Random Forest, and Gradient Boosting Classifier models.
4. **Tuning**: Optimized the Gradient Boosting Classifier using GridSearchCV for the best hyperparameters.
5. **Evaluation**: Assessed models using metrics such as accuracy, F1-score, precision, recall, and ROC-AUC.

## Results
The Gradient Boosting Classifier emerged as the best-performing model, providing reliable predictions and insights into the drivers of customer segmentation.

## Repository Contents
- **Jupyter Notebook**: Contains the full analysis, code, and model implementation.
- **Dataset**: Preprocessed data used for modeling (if allowed to share).
- **Model**: Saved final model for deployment.
- **Report**: A detailed explanation of the methodology and findings.

## How to Use
1. Clone this repository: `git clone <repository-url>`
2. Install the required libraries: `pip install -r requirements.txt`
3. Run the Jupyter Notebook to explore the analysis and train the model.
4. Use the saved model (`final_model.pkl`) for predictions on new customer data.

## Next Steps
- Deploy the model as an API or web app for real-world use.
- Integrate new data for continuous model improvement.

Feel free to explore the repository and reach out for any questions or feedback!
