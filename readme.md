# Boston House Price Prediction

## Overview

This project predicts house prices using machine learning algorithms.
The model is trained on housing data to learn the relationship between different features (such as number of rooms, location, etc.) and the price of a house.

The goal of this project is to demonstrate a complete machine learning workflow including:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Model training
- Model evaluation
- Prediction visualization

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Machine Learning Workflow

### 1. Data Loading

The housing dataset is loaded using Pandas.

### 2. Data Preprocessing

- Handle missing values
- Feature selection
- Train-test split

### 3. Model Training

Multiple machine learning models were trained and evaluated to predict house prices. The models implemented in this project include:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Stacked Ensemble Model

To ensure robust model evaluation, **K-Fold Cross Validation** was applied to each model. This technique helps reduce overfitting and provides a more reliable estimate of model performance by training and validating the model across multiple data splits.

### 4. Model Evaluation

The model performance is evaluated using:

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R-Squared (R2)
- Visualization of Actual vs Predicted values

### 5. Prediction

The trained model predicts house prices based on input features.

---

## Results

The performance of the trained models is evaluated using **residual visualizations**, which show the difference between the actual and predicted house prices.

Residual plots help assess:

- How well the models fit the data
- Whether prediction errors follow any patterns
- The overall accuracy and reliability of the models

These visualizations provide insight into the predictive performance of Linear Regression, Decision Trees, Random Forest, Gradient Boosting, and the Stacked Model.

---

## How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/Madhesh1602/House-Price-Prediction.git
```

### 2. Navigate to the project folder

```
cd House-Price-Prediction
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook

```
main.ipynb
```

## Future Improvements

- Apply advanced feature engineering techniques to create more informative features from the dataset
- Use larger or more diverse housing datasets to improve model generalization
- Build an interactive web application where users can input house features and get price predictions
- Deploy the trained model using frameworks such as Flask or Streamlit.