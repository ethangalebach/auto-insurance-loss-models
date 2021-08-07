# auto-insurance-loss-models
I clean, explore, analyze, and model claim severity from an anonymized Allstate dataset available on Kaggle [here](https://www.kaggle.com/c/allstate-claims-severity/overview/).

For the given MAE evaluation metric, I find that a penalized Generalized Additive Model (with quantile regression) performs worse than XGBoost, which performs worse than lightGBM.

![LightGBM](https://github.com/ethangalebach/auto-insurance-loss-models/blob/images/lightGBM.png?raw=true)