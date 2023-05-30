
# Student Performance Prediction

# By: Brody Barton, Dean Mazlish, Shloke Meresh, and Tate McLean

## Project Overview
This project focuses on predicting student performance leveraging a broad array of input features. The dataset is sourced from Kaggle, boasting over 26 million observations along with numerous variables.

## Repository Structure
The structure of this repository is as follows:

- 7 Data Sets: These datasets, either created from preprocessing or directly read from Kaggle, have been incorporated to facilitate ease of use within this repository.
- PreProcessing.ipynb: This Jupyter notebook is where we ingest the Kaggle data in batches and subsequently perform feature engineering on that data. The result is a refined dataset, prepped for modeling in the Model_final.ipynb notebook.
- Model_final.ipynb: This Jupyter notebook is where all the modeling takes place. We train and test various machine learning models here including XGBoost, Random Forest, CatBoost, LightGBM, and an ensemble model combining all of the mentioned models.

To run the code, simply open the respective Jupyter notebooks and execute the cells in order.

# How to Run the Code
Start with the PreProcessing.ipynb notebook. Here, you will read in the Kaggle data, process it in batches, and perform feature engineering. Execute all cells in this notebook.
Next, move to the Model_final.ipynb notebook. This notebook will utilize the processed data to train and test the various machine learning models. Again, execute all cells in this notebook.

Please ensure that you have all the necessary Python packages installed and the data files are in the correct location before running the notebooks.

# Dependencies
This project requires the following Python libraries:

pandas
numpy
xgboost
catboost
lightgbm
scikit-learn
matplotlib
