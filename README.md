# Baseball Salary Prediction

This project develops a regression model to predict the annual salary of major league baseball players based on performance statistics. The analysis uses the Hitters dataset containing observations on 18 variables for players from the 1986 and 1987 MLB seasons.


# The workflow includes:

-- Fitting a full multiple linear regression model

-- Checking model assumptions like linearity, normality, constant variance

-- Addressing issues like multicollinearity through variable selection

-- Applying transformations to satisfy linearity assumptions

-- Identifying and removing influential observations

-- Evaluating model fit and prediction accuracy

-- The final model incorporates 10 predictor variables and uses a power transformation on the response Salary. It has an adjusted R-squared of 0.75, indicating excellent fit. Variables for career runs batted in (CRBI) and career walks (CWalks) have the strongest relationships with salary.

-- Predictions on test data show low error rates, demonstrating that key performance metrics like hits, walks, and runs batted in are highly predictive of player salary. This model could help teams evaluate player contracts or arbitration cases based on statistical production.
