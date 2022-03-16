# TMDB Box Office Revenue Prediction

## Overview
Spending a lot of money on creating a movie does not gaurantee that they can get a lot of revenue from the movie. Even though it costed 220 million USD to create The Avengers, they made 150 million USD. The cost for making Rocky was 1 million USD, but they brought in 117.2 million USD. Then, how can we predict the movie revenue?

In this project, I built a machine learning model to predict movie revenue by analyzing [TMDB Box Office dataset](https://www.kaggle.com/c/tmdb-box-office-prediction/data). **I used lightGBM to build the model and got 1.96 RMSLE score.** 



## File Description
Each jupyter notebook shows workflow:
        
    - Cleaning_FeatureEngineering.ipynb 
        : Shows workflow regarding data clearning, and feature engineering. 
    - FeatureEngineeringScaling.ipynb 
        : Exploratory data analysis, and investigations rearding feature engineering and feature scaling.
    - HyperparameterTuning.ipynb 
        : Used Optuna to tune hyperparameters to find the best paramters for lightGBM model. 
    - PipelineToBuildModel.ipynb 
        : Built model pipeline and evaluate the model. 


## Dependencies
- Python 3.5+
- Machine Learning Libraries: 
    - Numpy
    - Pandas
    - Sciki-Learn
    - Feature-engine
    - lightGBM
    - Optuna
- Visualization: Matplotlib, Seaborn


## Acknowledgements
Data was provided by Kaggle