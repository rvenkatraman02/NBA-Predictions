# NBA-Predictions
***Predicting NBA Spreads, Totals, and Offensive Rebounds***

I worked in a group of five people for my STOR 538 (Sports Analytics) class project, with a goal of predicting the scores and offensive rebounds for the last six days of the NBA regular season (4/4 - 4/9).

This project required us to carefully clean the data which we acquired through the [nbastatR package provided by Alex Bresler](https://www.rdocumentation.org/packages/nbastatR/versions/0.1.10131). This package provided us with basic and advanced statistics on a game log level which allowed us to analyze the most important statistics to predict each team's points and offensive rebounds. To achieve these predictions we conducted a series of model tests such linear, Poisson, ridge, and LASSO tests and then evaluating each of their RMSEs.

In this repositiory you will find our R code for both the cleaning and modeling stages. Our predictions and their accuracy will also be included.
