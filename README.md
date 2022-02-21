# NLP_LitReadibility
Data exploration and final algorithm code to assess ease of read of a text excerpt, created for the [Common Literature Readability Prize 2021](https://www.kaggle.com/c/commonlitreadabilityprize) hosted by [Kaggle](https://kaggle.com). The original notebook (with version history and connection to the relevant data sources) is availabile [on Kaggle Notebooks](https://www.kaggle.com/ppjanka/2021-commonlitreadability).

Branches:
 - main: the final model (best-performing version selected)
 - exploration: full data exploration notebook
    - data cleaning & exploration
    - feature engineering
    - model exploration & tuning

**Contents (exploration branch):**
 - (tabular) data cleaning and pre-processing:
 - feature engineering:
   - manual, based on data exploration and domain knowledge / expectations,
   - PCA,
 - regression models:
   - classical:
     - SGDR (base),
     - linear regression,
     - LGBM,
     - XGB
     - CatBoost,
     - KernelRidge,
     - ElasticNet,
     - BayesianRidge,
     - GradientBoosting,
     - SVM,
   - neural networks: 
     - CNN,
     - LSTM,
 - natural language processing:
   - word embedding (pre-trained),
 - hyperparameter tuning:
   - keras_tuner.Hyberband for the neural networks,
   - optimization over scalers for the classical models.
