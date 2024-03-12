# PremierLeaguePredictor
This is a repo containing a Machine Learning project in which I attempt to predict the winners of Premier League matches.

PremierLeagueDataScraper is a jupyter notebook that pulls data from fbref.com, which can be saved in a csv and used to train ML models. 
Be careful to not get timed out from the site, they are very generous in the allowing of data usage, but more than 20 requests/min will get you timed out.

PremierLeaguePredictor is a jupyter notebook containing my attempts at training various ML models on Premier League match data. It includes data preprocessing and the implementation of the following models:
- Random Forest Walk
- xgBoost
- Kernel Support Vector Machine (with k-fold cross validation and grid search improvements)
- Naieve Bayes
- K-Nearest Neghbours
- Artificial Neural Network
- Recurrent Neural Network

See the notebook for details, but in summary I found the Random Forest Walk to be the best performing model with a precision of 68% on the test data.
I hope to explore this topic further, seeing how the model performs for the rest of the season, and exploring if any additional indicators improve the model , as well as testing the impact of varying the splitting of training and test data.
For any feedback, please reach out at lgayer@tcd.ie
