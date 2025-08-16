# RiskGuard: Credit Card Risk Analysis


This project aims to develop a credit scorecard model to predict loan default risk using the Lending Club loan dataset. The notebook covers data preprocessing, feature engineering, model development, and evaluation.

Table of Contents
Introduction
Dataset
Project Structure
Installation
Usage
Results
Contributing
License
Introduction
Credit scorecards are widely used in the finance industry to assess the risk of lending to individuals. This project builds a logistic regression model to predict whether a loan will be fully paid or default based on various features provided in the dataset.

Dataset
The project utilizes the Lending Club loan data. The dataset includes various features such as loan amount, interest rate, employment length, annual income, and more.

Note: The dataset used in this project is not included in the repository due to its size. You can download the dataset from Lending Club's website.

Project Structure
The project is structured as follows:

credit_scorecard.ipynb: The main notebook containing the code for data preprocessing, model development, and evaluation.
data/: Directory where the dataset should be placed (not included in the repository).
models/: Directory to save trained models (optional).
Installation
To run this project, you'll need to install the following Python libraries:

bash
Copy code
pip install pandas numpy scikit-learn matplotlib seaborn
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/credit-scorecard.git
Navigate to the project directory:

bash
Copy code
cd credit-scorecard
Open the Jupyter notebook:

bash
Copy code
jupyter notebook credit_scorecard.ipynb
Run all cells to preprocess the data, train the model, and evaluate its performance.

Results
The project provides a binary classification model predicting whether a loan will be fully paid or will default. The model's performance metrics are calculated using accuracy, precision, recall, and the ROC-AUC curve.

Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

mail at suraj@smail.iitm.ac.in
