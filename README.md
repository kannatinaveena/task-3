🏠 Linear Regression on Housing Price Dataset
This repository contains a complete implementation of Simple Linear Regression using the Kaggle dataset Housing Price Prediction. The goal is to understand and predict housing prices based on selected features using regression modeling.

📌 Objective
Analyze the Housing Price dataset and understand the relationships between features.

Train a Linear Regression model using sklearn.

Evaluate the model with standard regression metrics.

Visualize the regression line and interpret key coefficients.

📊 Linear Regression Steps Covered
✅ Step 1: Import and Preprocess the Dataset
Loaded the dataset from Kaggle (housing.csv).

Cleaned and handled any missing or irrelevant columns.

Focused on important numeric features (like area, bedrooms, bathrooms, etc.).

✅ Step 2: Split Data into Train-Test Sets
Used train_test_split() to divide the data into 80% training and 20% testing sets.

Target variable: price

✅ Step 3: Fit a Linear Regression Model
Trained a Linear Regression model on selected features using LinearRegression() from sklearn.linear_model.

Printed the model's coefficients and intercept.

✅ Step 4: Evaluate the Model
Calculated:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

Interpreted how well the model performed on the test data.

✅ Step 5: Plot Regression Line and Interpret Coefficients
Visualized:

Feature vs. Target with the regression line overlayed

Explained what each coefficient means (e.g., how much price increases with area).

🛠️ Tools Used
Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

📂 Dataset
📁 Dataset: https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction

📄 File Used: housing.csv

Key Features:

area: Area of the house in sq.ft.

bedrooms: Number of bedrooms

bathrooms: Number of bathrooms

stories: Number of floors

mainroad, guestroom, basement, hotwaterheating, etc.

price: House price (target variable)

