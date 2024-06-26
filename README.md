# IPL-Prediction-using-Random-Forest

IPL Prediction using Random Forest Regression
Overview
This project aims to predict the outcomes of Indian Premier League (IPL) matches using Random Forest Regression. The model is trained on historical match data and player performance statistics to provide accurate predictions.

Table of Contents
Project Structure
Installation
Usage
Data Collection and Preprocessing
Model Training and Evaluation
Results
Visualization
Contributing
License
Project Structure
bash
Installation
To set up the project on your local machine, follow these steps:

Clone the repository:
git clone https://github.com/RUCH260920/IPL_Prediction.git

cd IPL_Prediction
Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install the required dependencies:
pip install -r requirements.txt
Usage
Run the Jupyter notebook to see the entire workflow of the project:
jupyter notebook notebooks/IPL_PREDICTION_USING_RANDOM_FOREST_REGRESSION.ipynb
To preprocess the data, train the model, and evaluate it, run the respective scripts in the src directory:
python src/data_preprocessing.py
python src/model_training.py
python src/evaluation.py
Data Collection and Preprocessing
Data Collection: Collected historical IPL match data and player performance statistics from various sources.
Data Cleaning: Handled missing values, removed duplicates, and normalized the data.
Feature Engineering: Created new features to enhance the model's predictive power.
Model Training and Evaluation
Model: Random Forest Regression
Training: Split the data into training and testing sets. Trained the model using the training set.
Evaluation: Evaluated the model using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). Optimized hyperparameters for better accuracy.
Results
The Random Forest Regression model provided accurate predictions for IPL match outcomes.
Feature importance analysis showed the key factors influencing the match results.
Visualization
Created visualizations to analyze feature importance and model predictions.
Plotted error metrics to evaluate model performance.
