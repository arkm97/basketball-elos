# basketball-elos

### Goal
The goal is to predict the winner of any game in the 2017 NBA season. The file $\texttt{NBA-DATAMINING.csv}$ contains stats for NBA games from 2011 to 2018.  I use the data to create a set of features and train a classifier to predict the outcome of any given game. I use a logistic model because I'm interested in predicting a binary dependent variable.

To make things interesting, I implement an Elo rating system for all the teams, as well as a few other engineered featuers.

### Results
Trained on data from the 2009 - 2016 seasons, I can predict the outcome of the 2017 season with >65% accuracy. For fun, I also trained and scored a Random Forest classifier.

### Packages 
```
pandas
sklearn
numpy
matplotlib
```

### Acknowledgements
FiveThirtyEight's [Elo rating system](https://fivethirtyeight.com/features/how-we-calculate-nba-elo-ratings/)
