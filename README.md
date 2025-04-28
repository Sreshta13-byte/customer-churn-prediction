# customer-churn-prediction

1-Project Objective

The objective of this project is to predict whether a customer will leave a service (churn) based on their demographic and transactional information.  Techniques used include data preprocessing, feature engineering, model training (Logistic Regression, Random Forest), evaluation ROC-AUC curve and feature importance analysis.


2-About the dataset
The dataset used is "Churn_Modelling.csv" which contains 10,000 customer records including demographics, account information, and churn labels. This dataset is ideal for binary classification problems.


3- Technologies Used

Python 
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Google Colab 
Joblib

4-Project Structure

customer-churn-prediction/
├── data/
│   └── Churn_Modelling.csv
├── notebook/
│   └── customer_churn_prediction.ipynb
├── README.md


5- To Run the Project follow the below steps:

Step1:Clone the repositary
git clone https://github.com/Sreshta13-byte/customer-churn-prediction.git

Step2: Navigate to the project directory
cd customer-churn-prediction

Step3:Open the notebook
customer_churn_prediction.ipynb
using either Google colab or Jupyter notebook

Step4: Run all the cells to train the models and view the evaluation metrics.


6- Model Overview
Logistic Regression was used initially but achieved limited performance.

Random Forest Classifier was selected as the final model after hyperparameter tuning.

Final Model Performance:

Accuracy: 84%

ROC AUC Score: 0.79

Important Features:

Age
Credit Score
Balance
IsActiveMember

7-Conclusion
The Random Forest model successfully predicts customer churn with high accuracy.

Important customer features were identified, which businesses can use to create targeted retention strategies.