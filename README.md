
# FIFA21 Data Analysis Project





## Overview

Welcome to the FIFA21 data analysis project! This project entails intensive data cleaning and transformation of the raw, messy FIFA21 data set I obtained from Kaggle. It involves a comprehensive exploration of various aspects of the data set, aiming to provide valuable insights into player performance, team dynamics, and statistical trends within the world of football.
### Tools
- R

### Libraries Used
- Tidyverse
- Skimr
- janitor
- ggrepel
- PerformanceAnalytics
- kableExtra

### Objectives

The objective of this project is to perform data cleaning and transformation on the raw, messy fifa21 data set, and then to analyze the data to derive insights such as who are the most valuable players, which players have stayed at a club for the longest time, and to relationships between age, weight, and height of players.

#### Data Cleaning Tasks
- Drop columns that won’t be used in the analysis
- Fix the column names
- Remove the unnecessary newline characters from all columns that have them
- Convert the height and weight columns to numeric
- Convert the value, Wage, and release clause columns into numeric, multiply the columns by there respective value, e.g “M” should be multiplied by 1000000
- Remove star characters in the W/F, SM, and IR columns
- Split the contract column into three separate columns: the year the contract starts, ends, and the type of contract


#### Data Analysis Tasks
- Check which players have been playing at a club for more than 10 years.
- Highlight players who are highly valuable but still underpaid (using a scatterplot).
- Identify the most valuable players.
- Built a Multiple Regression Model to check if there is a significant relationship between weight, height, and age of a player. (Does the height and age of a player have a significant impact on the weight?)
- Check the distribution of players across different clubs and identify clubs with the highest average overall rating among its players?
- Investigate whether a player's contract length relates to their market value.
## Insights

- Based on the analysis, approximately 759 players have been playing at a club for more than 10  years, with H. Sogahata of Kashima Antlers in Japan being the oldest player at a single club, played for more than 26 years at the same club.
- As per the FIFA21 data set, Erling Haaland and G.Donnarumma were some of the highly rated players but still got underpaid. Where as K.Mbappe, Neymar Jr and  K. De Bruyne were the top 3 most valuable players in the world.
- From the regression model, 62.04% of the change in a player's weight can be explained by the height and age of the player. An increase in one unit of the height leads to 0.778 increase in the player's weight.
- The analysis also shows that Central Forward (CF), Right Wingers (RW), and Left Wingers (LW) are the most highly rated players while Goal Keepers have the least ratings.
- On distribution of players, 22.28% of the clubs have 28 players each, 17.45% have 30 players, while surprisingly, there are clubs with less than 22 players. Approximately 15 clubs have 22 players and below.
- FC Bayern Munchen, Real Madrid, Inter, and Napoli are the teams with the most highly rated players, while Finn Harps and Waerford FC have the lowest rated players.
- There also appears to be a  weak positive relationship between a player’s contract length and their market value. A correlation coefficient of 0.213385 indicates that as the contract length increases, the market value is also expected to increase.

