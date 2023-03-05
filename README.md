### Final Project for DTSA-5509: Intro to Machine Learning: Supervised Learning

#### Project Background

For this final project I gathered data from [Kaggle](https://www.kaggle.com/) containing game-by-game statistics across every NHL season from 2002-2019, however for the sake of my analysis I limited the data to only games played between 2010-2019 (data prior to 2010 was unreliable). I attemped to predict a team's efficiency throughout the entirety of a season using aggregated game statistics throughout the year. A few of the statistics I aggregated and used as input features include goals per game, saves per game, face-off winning percentage per game, etc. The response variable was a bound (0, 1) of the teams total points earned throughout the year as a fraction of the total possible points to be earned in a single year.  

#### Notebook

The notebook contained within this repo contains all the data gathering, data preporcessing, EDA, and model analysis done for this project. The final model with the lowest test MSE was a Ridge Regression model. 


#### Data Resources

- [link to data on Kaggle](https://www.kaggle.com/datasets/martinellis/nhl-game-data)
