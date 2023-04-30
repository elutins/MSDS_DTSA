## DTSA 5510 Final Project


### Project Background & Data Explanation

This project required gathering and preprocessing data from an external source online, and then performing clustering analysis on the dataset. I have gathered data spanning several NHL seasons with the aim of trying to cluster individual NHL players into their respective positions, given game-by-game statistics for each player. There are four possible positions a player can assume; **Right Wing (RW)**, **Left Wing (LW)**, **Centerman (C)**, or **Defenseman (D)**. For the sake of this analysis I am excluding goalies, as it would be fairly trivial to predict which player's are goalies based on their game statistics. 

Data statistics included but are not limited to the time player spent on the ice per game, shots taken per game, faceoffs taken per game, and the player's height. I will build two different clustering models with `k=4` clusters, and evaluate model performance based on the homogeneity of each model cluster.

I have gathered data from [Kagggle](https://www.kaggle.com/datasets/martinellis/nhl-game-data?datasetId=56652&sortBy=dateRun&tab=profile&select=game_skater_stats.csv) for this analysis. I will leverage two datasets durign this ananlysis; one dataset containing game-by-game statistics for each player and another containing the player's primary position. I will use the player's actual primary position from the second dataset in order to evaluate my models. 


### Modeling Methods Performed
1. KMeans Clustering
2. Hierarchical Clustering
3. Random Forest Classifier


### Notebook

Jupyter Notebook containing EDA, data preprocessing, modeling, model results, and conclusions can be found within the `5510/` subfolder
