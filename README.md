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
`/Data_Files/`: Folder containing csv files used in our Rmd files <br>
`Playoffs_2-Data_Cleaning.Rmd`: R notebook file used to import and clean the data. <br>
`Playoffs_2-Pts_Modeling.Rmd`: R notebook file used to model and predict points scored by team. <br>
`Playoffs_2-Oreb_Modeling.Rmd`: R notebook file used to model and predict offensive rebounds by team. <br>
`Predictions_FINAL.csv`: CSV file containing our final predictions. <br>
`2023_NBA_Predictions_Report.pdf`: Final report with our methodologies for the whole project. <br>

### RMSE of NBA Predictions

|              | Spread | Total Points | Offensive Rebounds |
|--------------|-------:|-------------:|-------------------:|
| **April 4**  |   13.504    |      19.046        |       6.824           |
| **April 5**  |    8.161   |        26.015      |          6.247           |
| **April 6**  |   17.415    |       18.012       |          4.506           |
| **April 7**  |   13.844    |       20.644       |          5.440           |
| **April 8**  |   6.440    |       38.440       |            1.130         |
| **April 9**  |    21.699   |        23.063      |           4.668          |
| **Cumulative**  |    15.903   |       22.904       |          5.519           |

_* Please note that our model did not account for players resting for the final regular season games, resulting in unexpected results. Additionally we were asked to predict all 6 days of games on April 3rd, so we could not adjust accordingly each day._
