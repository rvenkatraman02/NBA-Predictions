# NBA-Predictions
***Predicting NBA Spreads, Totals, and Offensive Rebounds***

I worked in a group of five people for my STOR 538 (Sports Analytics) class project, with a goal of predicting the scores and offensive rebounds for the last six days of the 2023 NBA regular season (April 4th - April 9th).

_Here are the formulas for the metrics we were predicting:_
$$\text{Spread} = \text{Home Points} - \text{Away Points}$$
$$\text{Total Points} = \text{Home Points} + \text{Away Points}$$
$$\text{Offensive Rebounds} = \text{Home Offensive Rebounds} + \text{Away Offensive Rebounds}$$

This project was a comprehensive data analysis effort that required meticulous data cleaning, modeling, and evaluation. We obtained the necessary data from the [nbastatR package provided by Alex Bresler](https://www.rdocumentation.org/packages/nbastatR/versions/0.1.10131), which allowed us to access and analyze both basic and advanced statistics on a game log level.

To predict each team's points and offensive rebounds, we conducted a series of rigorous model tests including linear, Poisson, ridge, and LASSO tests. After evaluating the RMSEs of each model, we arrived at a final set of predictions.

In this repositiory you will find our Rmd notebook files for both the cleaning and modeling stages, a spreadsheet of our predictions and actual results, and a comprehensive final report detailing our entire methodology. This project showcases our ability to utilize a diverse range of analytical tools and techniques to deliver actionable insights and predictions.

### Files in this Repository


### RMSE of NBA Predictions

|              | Spread | Total Points | Offensive Rebounds |
|--------------|-------:|-------------:|-------------------:|
| **April 4**  |       |              |                     |
| **April 5**  |       |              |                     |
| **April 6**  |       |              |                     |
| **April 7**  |       |              |                     |
| **April 8**  |       |              |                     |
| **April 9**  |       |              |                     |
