# Titanic Survival Prediction 

A fun machine learning project predicting who survived the Titanic.  
Includes data cleaning, feature engineering, and trying out a bunch of ML models.
I experimented with multiple models, from simple Logistic Regression to advanced ensemble methods like XGBoost, LightGBM, CatBoost,Stacking and Voting.
overall due to the limitations of titanic dataset , after feature engineering and cleaning of the data , almost all the models gave similar results and at the end i went with the XGBoost model for the kaggle submission.

## Project Structure
- `titanic.ipynb` — Jupyter Notebook with full workflow.
- `train.csv`, `test.csv` — Dataset (from [Kaggle Titanic competition](https://www.kaggle.com/c/titanic)).

## Setup
Install dependencies:
```bash
pip install -r requirements.txt

## Models Tried 
- **Logistic Regression**

- **SVC**

- **Decision Trees**

- **Random Forests**

- **Boosting(XGBoost, LightGBM, CatBoost)**

- **Stacking**

- **Voting**
