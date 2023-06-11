### Referee_Analysis

This analysis seeks to explore the differences in the tendencies of football referees to give fouls, yellow cards and red cards across UK and European football leagues. It analyses the range of differences between the individual referees and how the tendency for referees to give above or below the average of these features for any particular season is continued from one season to the next.

The dataset used was taken from soccer-data.co.uk and consists of English and Scottish league football and top division Italy, Spain and Germany from 2003 to 2022, with data filtering used to isolate games where referee information was provided. The final processed dataset consists of 45148 rows. A subset of data for the top 50 referees was then obtained which was organised comparing alternate years for each of the three features. The final dataframe consists of 319 rows each providing an individual referees year to year ratio comparison.

The data shows that there is a positive correlation for referees who give an above average number of fouls and yellows on a per match basis in any given season to then continue this above average tendency for the following season. Similarly, below average numbers will continue into the following season. The data for red cards show a negligible correlation.

Regression analysis was finally carried out to provide a formula which can be applied to quantify the expected referee influence on the outcome of total fouls and yellows in any future match.
