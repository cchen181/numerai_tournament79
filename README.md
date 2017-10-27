# numerai_tournament79

This repo contains relevant data and scripts while participating in Numer.ai, Tournament 79.
Numer.ai is a hedge fund built upon crowd-sourced prediction models. These models are used to select favorable stocks with
financial rewards returned to successful modelers in the form of Numeraire.

Tournaments are reset weekly. Data is released every Tuesday 9 AM PST. Data includes training data (~230 MB) and tournament 
data (~150 MB). Further details can be found on Numer.ai and in data_details.ipynb.

Through this tournament, I aim to strengthen intuition and gain a deeper understanding of predictive modeling. I look forward
to exploring the strengths and weaknesses of the models I use in an empirical manner. 

-------------------------
Numer.ai releases several files to its users:
example_model.py [contained in  repo] - A sample script creating and executing model prediction.
example_model.r [not in  repo] - A sript similar to above written in R.
example_predictions.csv [contained in  repo] - Corresponding sample output of model prediction.
numerai_tournament_data.csv [not in repo due to size limits] - Data. Data sample available in data_details.ipynb.
numerai_training_data.csv [not in repo due to size limits] - Data. Data sample available in data_details.ipynb.

-------------------------
Scripts in this repo:
data_details.ipynb - Script enabling others to see samples of both numerai*data.csv
-------------------------
The training data is used to create, produce, and validate my model. Following validation, the model is run on the tournament data. Details in ______.ipynb
