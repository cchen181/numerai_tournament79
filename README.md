# numerai_tournament79

This repo contains relevant data and scripts while participating in Numer.ai, Tournament 79.
Numer.ai is a hedge fund built upon crowd-sourced prediction models. These models are used to select favorable stocks with
financial rewards returned to successful modelers in the form of Numeraire.

Data includes training data (~230 MB) and tournament data (~150 MB). Further details can be found on Numer.ai and in data_details.ipynb. 

The training data is used to create different predictive models and model performance among said models is compared to determine the best predictive model. The best model is then run on the tournament data. Prior to modeling, the data is analyzed and prepared for modeling. Samples of original datasets are available in the data_details.ipynb.

-------------------------
Scripts in this repo:
  * data_details.ipynb - Script enabling others to see data samples of both numerai*data.csv
  * model_v2.ipynb

-------------------------
From exploring the training data and preparing the dataset for model prediction, I have learned:
  * there is a target, whose discrete values of 0 and 1, suggest a supervised learning modeling approach, specifically in classification. For these reasons, one of the modeling approaches I will use is logistic regression.
  * there are 135 features at my disposal for predictive modeling. There are 50 features in the original training dataset and converting one of the categorical variables, era, into several indicator variables results in a total of 135 features. 
  * the distributions of the 50 features are fairly similar. This is supported by a table of statistical summaries and density plots revealing fairly symmetrical bell-shaped curves around similar mean values.
  * With values ranging from -0.035647 to 0.032404, all 135 features appear weakly correlated to the target. Within all available features, those features labeled feature## are more strongly correlated with the targets than those labeled era##.

Details available in model_v2.ipynb.
