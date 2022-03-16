# TMDB Box Office Revenue Prediction

## Overview
Spending a lot of money on creating a movie does not gaurantee that they can get a lot of revenue from the movie. Even though it costed 220 million USD to create The Avengers, they made 150 million USD. The cost for making Rocky was 1 million USD, but they brought in 117.2 million USD. Then, how can we predict the movie revenue?

In this project, I built a machine learning model to predict movie revenue by analyzing [TMDB Box Office dataset](https://www.kaggle.com/c/tmdb-box-office-prediction/data). **I used lightGBM to build the model and got 1.96 RMSLE score.** 




## File Description
The files structure is arranged as below:
        
    - Building_Model_Pipeline.ipynb 
        : Workflow regarding building Gradient Boosting Model.
    - Cleaning_EDA_and_Visalization.ipynb 
        : Data cleaning, exploratory data analysis, and visualizing data.
    - FeatureEngineeringScaling.ipynb 
        : Investigations regarding feature engineering, feature scaling, and feature importance. 
    - HyperparameterTuningForGBM.ipynb 
        : Hyperparameter tuning by using Optuna to find the best parameters for GBM model. 
    - Oversampling.ipynb
        : Finding the best over-sampling methods for this project to deal with imbalanced dataset.
    - readme.md


## Dependencies
- Python 3.5+
- Machine Learning Libraries: 
    - Numpy
    - Pandas
    - Sciki-Learn
    - Feature-engine
    - Imblearn
    - Optuna
- Visualization: Matplotlib, Seaborn


## Acknowledgements
Data was provided by Kaggle