# auto-insurance-loss-models
I clean, explore, analyze, and model claim severity from an anonymized Allstate dataset available on Kaggle [here](https://www.kaggle.com/c/allstate-claims-severity/overview/).

Given the MAE evaluation metric, I use quantile regression in all models. I find that a penalized Generalized Additive Model performs worse than Random Forest, which performs worse than lightGBM.

The inital tuning grid results for LightGBM and Random Forest, respectively, are displayed below. 

LightGBM
![LightGBM](https://github.com/ethangalebach/auto-insurance-loss-models/blob/master/lightgbm.png?raw=true)

Random Forest
![Random Forest (Ranger)](https://github.com/ethangalebach/auto-insurance-loss-models/blob/master/ranger.png?raw=true)
