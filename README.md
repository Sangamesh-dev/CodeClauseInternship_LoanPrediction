**_Loan Status Prediction using Machine Learning_**

This project is designed to predict loan approval status based on various features such as gender, marital status, income, and credit history. It uses machine learning techniques and a graphical user interface (GUI) to make predictions.

**Prerequisites**
Before running the project, make sure you have the following prerequisites installed:
- Python (3.x recommended)
- Required Python packages (scikit-learn, pandas, joblib, tkinter)
- Jupyter Notebook (for model training, if needed)

**Project Overview**
The project performs the following key tasks:

_1. Data Preprocessing:_
- Loads loan data from a CSV file.
- Handles missing values and data cleaning.
- Encodes categorical variables and scales numeric features.

_2. Model Training:_
- Trains multiple machine learning models (Logistic Regression, Support Vector Classifier, Decision Tree Classifier, Random Forest Classifier, Gradient Boosting Classifier) using the cleaned data.
- Hyperparameter tuning is performed using Randomized Search Cross-Validation.

_3. Model Saving and Loading:_
- The best-performing model (Random Forest Classifier) is saved using joblib.
- The saved model can be loaded for making predictions.

_4. GUI Application:_
- Provides a GUI for users to input loan application details.
- Uses the trained model to predict loan approval status based on user inputs.
- Displays the prediction result on the GUI

**Usage**
To use the loan status prediction GUI:

- Run the Python script loan_status_gui.py.
- Fill in the details in the GUI, such as gender, marital status, income, etc.
- Click the "Predict" button.
- The GUI will display whether the loan is approved or not based on the model's prediction.

**Project Structure**
The project is organized as follows:

- loan_status_gui.py: Main script for the GUI application.
- loan_status_predict.pkl: Saved machine learning model using joblib.
- loan_prediction.csv: Dataset containing loan application data.
- README.md: This README file.

**Dependencies**
This project uses the following Python libraries and packages:

- scikit-learn: Machine learning library for model training and evaluation.
- pandas: Data manipulation and analysis library for data preprocessing.
- joblib: Library for saving and loading machine learning models.
- tkinter: GUI library for creating the user interface.

You can install these packages using pip:
pip install scikit-learn pandas joblib
