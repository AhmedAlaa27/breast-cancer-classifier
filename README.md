# Breast Cancer Prediction Project

This project is focused on predicting breast cancer using a machine learning model. The primary goal of this project is to practice and refine skills in data preprocessing, model selection, and evaluation.

## Project Structure

- **`breast-cancer.ipynb`**: The Jupyter notebook containing the code.
- **`README.md`**: Project documentation.
- **`datasets/`**: Directory containing the breast cancer dataset (not included in the repository; users should download it from [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/data)).
## Steps Followed

1. **Data Loading**:
   - The breast cancer dataset was loaded into a pandas Data Frame for analysis, containing features like tumor size, texture, smoothness, etc.

2. **Data Exploration**:
   - The dataset was explored to understand the distribution of features, check for missing values, and analyze relationships between them.

3. **Data Cleaning**:
   - Missing values were handled appropriately, and irrelevant features were removed to prepare the data for modeling.

4. **Feature Engineering**:
   - Categorical variables were encoded, and additional features were created to enhance the model's predictive power.

5. **Data Splitting**:
   - The data was split into training and testing sets, typically in an 80/20 ratio, to ensure robust model evaluation.

6. **Model Selection**:
   - Various models, including XGBoost and Random Forest and Logistic Regression, were tested to find the best one for predicting breast cancer.

7. **Model Training**:
   - The selected model was trained on the training data, and hyperparameters were fine-tuned for optimal performance.

8. **Model Evaluation**:
   - The model was evaluated using accuracy, precision, recall, and F1-score to ensure its reliability.

9. **Prediction**:
   - The trained model was used to predict the presence of breast cancer in the test set, with predictions compared to actual outcomes.

## Technologies Used

- **Python**
- **pandas**
- **scikit-learn**
- **xgboost**
