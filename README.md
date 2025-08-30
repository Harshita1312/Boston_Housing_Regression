🏠 Boston Housing Regression Project

This project applies Supervised Machine Learning (Regression) to predict the median house value (MEDV) in the Boston Housing dataset.
It demonstrates data preprocessing, model training, evaluation, visualization, and model comparison using Linear Regression, Ridge Regression, and Lasso Regression.

📂 Project Structure
BostonHousingProject/
│── boston_regression.py        # Main script with preprocessing, training & evaluation
│── HousingData.csv             # Dataset (Boston Housing data)
│── HousePricingResult.png      # Visualization of Actual vs Predicted
│── requirements.txt            # Dependencies
│── README.md                   # Project description
│── .gitignore                  # Ignored files

⚙️ Features

Data Preprocessing

Handling missing values with median imputation

Feature scaling using StandardScaler

Model Training

Linear Regression

Ridge Regression

Lasso Regression

Evaluation Metrics

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

Visualization

Residual plot

Actual vs Predicted scatter plot

Model Comparison

R² scores of Linear, Ridge, and Lasso regression

📊 Results

Linear Regression provides a baseline performance.

Ridge and Lasso are compared to check improvements from regularization.

Diagnostic plots (residuals & scatter) are included to analyze model fit.

🚀 How to Run

Clone the repository:

git clone https://github.com/<your-username>/Boston-Housing-Regression.git
cd Boston-Housing-Regression


Install dependencies:

pip install -r requirements.txt


Run the script:

python boston_regression.py


Outputs:

Console prints evaluation metrics

Residual plot is displayed

Actual vs Predicted plot saved as HousePricingResult.png

📚 Dataset

The dataset (HousingData.csv) is a version of the Boston Housing dataset, originally from the UCI Machine Learning Repository.
It contains 13 features (e.g., crime rate, rooms per dwelling, property tax rate, etc.) and the target variable MEDV (Median value of owner-occupied homes).

🛠️ Tech Stack

Python 3

Pandas, NumPy

Matplotlib

Scikit-learn

✨ Future Work

Hyperparameter tuning with GridSearchCV

Cross-validation for better generalization

Adding advanced regression models (ElasticNet, Decision Tree, Random Forest)

Deploying the model with Streamlit or Flask

📜 License

This project is licensed under the MIT License – see the LICENSE
 file for details.

👩‍💻 Author: Harshita Jalan
📌 GitHub: Harshita1312

👉 You only need to replace:

*Your Name* → with your actual name

your-username → with your GitHub username
