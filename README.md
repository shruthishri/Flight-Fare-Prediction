# Flight-Fare-Prediction

## Dataset
https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh/

## Description
- The dataset taken from Kaggle is a combination of both categorical and numerical values which required data cleaning.
- The numerical values like date and month are extracted by using to_datetime function in pandas.
- The categorical values are handled using One Hot Encoder.
- The data is split into Train and Test set and fitted by Random Forest Algorithm.
- Hyperparameter Tuning was done by Randomized Search CV.
- The performance is checked by RMSE score.
