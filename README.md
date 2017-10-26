# numerai_tournament79

This repo contains relevant data and scripts while participating in Numer.ai, Tournament 79.
Numer.ai is a hedge fund built upon crowd-sourced prediction models. These models are used to select favorable stocks with
financial rewards returned to successful modelers in the form of Numeraire.

Tournaments are reset weekly. Data is released every Tuesday 9 AM PST. Data includes training data (~230 MB) and tournament 
data (~150 MB). Further details can be found on Numer.ai.

Through this tournament, I aim to strengthen intuition and gain a deeper understanding of predictive modeling. I look forward
to exploring the strengths and weaknesses of the models I use in an empirical manner. 

The entire dataset is numerical and all identifiers within tournament data are scrubbed. One advantage of this is that users
do not need any domain knowledge within finance. The released dataset is clean; this enables modelers to focus on modeling techniques.


Numer.ai releases several files to its users:
example_model.py [contained in this repo] - A sample script creating and executing model prediction.
example_model.r [not in this repo] - Script similar to above written in R.
example_predictions.csv [contained in this repo] - Corresponding sample output of model prediction.
numerai_tournament_data.csv [not in this repo] -  Data to test models.
numerai_training_data.csv [not in this repo] - Data to create models.
Both numerai*data.csv files exceed file limits of GitHub. Instead, samples of these datasets are available in ____.ipynb . 
