📊 Multiple Linear Regression on Startup Dataset

This project demonstrates Multiple Linear Regression using the 50_Startups dataset to predict company profits based on R&D Spend, Administration, Marketing Spend, and State.

📌 Project Overview

Understand the relationship between investment factors and startup profit.

Build and evaluate a Multiple Linear Regression model using Scikit-learn.

Perform data preprocessing, visualization, and error analysis.

📂 Dataset

File: 50_Startups.csv

Columns:

R&D Spend 💡 → Money spent on research and development

Administration 🏢 → Administration costs

Marketing Spend 📢 → Marketing budget

State 🌍 → Categorical feature (location of startup)

Profit 💰 → Target variable

⚙️ Installation

Clone the repository and install required dependencies:

git clone https://github.com/yourusername/multiple-linear-regression-startup.git
cd multiple-linear-regression-startup
pip install -r requirements.txt

📌 Dependencies

Python 3.x

pandas

numpy

matplotlib

scikit-learn

🚀 Usage

Open the notebook in Google Colab or Jupyter:

jupyter notebook Multiole_Regression_startup_dataset.ipynb


Run all cells to:

Load and explore the dataset

Encode categorical data (State)

Split into training & test sets

Train a Multiple Linear Regression model

Evaluate using Mean Squared Error (MSE)

📊 Results

The model successfully predicts Profit based on R&D, Administration, and Marketing spends.

Key finding: R&D Spend is the most influential factor in determining startup success.
