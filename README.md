# Classification and Ensemble Model - Titanic Dataset

This project involves building and training an ensemble model to predict survival on the Titanic dataset. The ensemble model consists of Random Forest, XGBoost, and Gradient Boosting classifiers.

## Project Structure

- `main_model.joblib`: Serialized file containing the trained ensemble model using joblib.
- `titanic_dataset.csv`: CSV file containing the Titanic dataset.
- `user_input.json`: JSON file for providing user input to make predictions.
- `main_model.ipynb`: Jupyter Notebook containing code for training and evaluating the ensemble model.
- `Outout.ipynb`: Python script to load the model and make predictions based on user input.

## Getting Started

1. Install the required dependencies:
   ```bash
   pip install pandas scikit-learn xgboost joblib matplotlib


1) Run model_training.ipynb to train the ensemble model on the Titanic dataset.
2) Store user input in user_input.json for making predictions.
3) Run predict_user_input.py to load the model and make predictions based on user input.



## Usage
main_model.ipynb: Open the Jupyter Notebook and execute the cells to train and evaluate the ensemble model.

Outout.ipynb: Run the script to make predictions based on user input stored in user_input.json.
