# IPL_Cricket_Score_Predictor
# Cricket Score Predictor using Linear Regression

This repository contains a cricket score predictor program that utilizes linear regression to predict the first inning score of a match played between two teams in an IPL match. The program takes into account various factors from ball-to-ball coverage of past IPL matches to make predictions about the total runs scored by the batting team in the first innings.

## Dataset

The dataset used for training and testing the predictor is located at `data/ipl.csv`. It consists of ball-to-ball coverage data from 617 IPL matches. Each match in the dataset is represented by the following columns:

- `mid`: Unique match number
- `date`: Date of the match
- `venue`: Stadium where the match was played
- `bat_team`: Batting team's name
- `bowl_team`: Bowling team's name
- `batsman`: Batsman facing the ball
- `bowler`: Bowler bowling the ball
- `runs`: Total runs scored by the batting team at that instance
- `wickets`: Total wickets fallen for the batting team at that instance
- `overs`: Total overs bowled at that instance
- `runs_last_5`: Total runs scored in the last 5 overs
- `wickets_last_5`: Total wickets that fell in the last 5 overs
- `striker`: Maximum runs scored by the striker and non-striker
- `non-striker`: Minimum runs scored by the striker and non-striker
- `total`: Total runs scored by the batting team after the first innings

## Libraries Used

The program utilizes several Python libraries for data manipulation, visualization, machine learning, and plotting:

- **Pandas**: Used for data loading, manipulation, and analysis.
- **NumPy**: Provides support for mathematical operations on arrays and matrices.
- **TensorFlow**: Used for implementing machine learning models, including linear regression in this case.
- **Matplotlib**: Used for creating various types of plots and visualizations.
- **Seaborn**: Built on top of Matplotlib, Seaborn enhances the visual appeal of plots.

## About Linear Regression

Linear regression is a machine learning algorithm used to model the relationship between a dependent variable (in this case, the total runs scored) and one or more independent variables (features such as runs, wickets, overs, etc.). The algorithm fits a linear equation to the data by finding the best-fitting line that minimizes the difference between predicted and actual values.

The linear regression model in this program is trained on the provided dataset, learning from the historical match data to predict the likely first inning score of a given match based on its features.

For any questions or issues, feel free to contact us.

Happy predicting! 🏏
