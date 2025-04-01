# Regression-of-rental-apartmens-price

This project is aimed at analyzing housing prices in the city of Rostov-on-don, Russia, predicting them and evaluating models for the possibility of working with a small amount of data. In this project, a regression model has been created to predict rental prices based on data (area, area, number of rooms, number of floors, floor of an apartment for rent, etc.) and a summary file is provided to demonstrate the regression results of various models. Two MLP and ML approaches were used.

### Project structure:

Avito House.xlsx - Excel spreadsheet with unprocessed data

Avito_ML.ipynb - Jupiter laptop with ML model

Avito_MLP.ipynb - Jupiter laptop with MLP model

Clean_Std_Data_Avito - Excel spreadsheet prepared and cleaned data format 

mlp_model3.h5 - serialized model Avito_MLP.ipynb

model_rf_ML.pkl - serialized model Avito_ML.ipynb

Software of models.ipynb - Jupiter laptop, comparison of the best ML and MLP models 

### Project stages:
-Working with data
-Download dataset
-Data cleaning (deletion of omissions, processing of outliers)
-Analysis of the main characteristics
-Visualization
-Construction of histograms and distribution diagrams
-Analysis of dependencies between variables
- Standardization
-Data transformation (normalization, encoding of categorical variables)
-Processing of unbalanced data
-Data separation and training
-Division into training and test samples
-Machine learning model training
-Model quality assessment
-Serialization
-Saving the trained model for later use

### How to install and run:

1.Cloning the repository
git clone https://github.com/your-username/avito-analysis.git
cd avito-analysis

2.Creating a virtual
python environment -m venv venv
source venv/bin/activate # For Linux/macOS
venv\Scripts\activate # For Windows

3.Installing
pip install -r dependencies requirements.txt

4.Launching Jupyter Notebook
jupyter notebook Avito.ipynb

### Technologies used:

Python is the main programming language
Pandas – working with tabular data
Matplotlib, Seaborn – data visualization
Scikit-learn – ML machine learning
Pickle - data serialization
Tensorflow - MLP Machine Learning
