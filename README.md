# Baseball Salary Prediction

Explore the complete code and analysis for the Baseball Salary Prediction project [here](https://github.com/omotuno/baseball_salary_prediction/blob/main/Sports-Analytics-A-case-study-in-baseball-Proposal.html). This project, developed in R Studio, delves into regression modeling for predicting annual salaries of major league baseball players using the Hitters dataset from the ISLR package. The dataset includes 18 variables for players from the 1986 and 1987 MLB seasons.


# The workflow includes:

-- Fitting a full multiple linear regression model
<img width="963" alt="Screenshot 2023-12-10 at 3 58 10 PM" src="https://github.com/omotuno/baseball_salary_prediction/assets/65866718/516be606-937e-4d86-b8e7-18ec58b817ec">

-- Checking model assumptions like linearity, normality, constant variance
<img width="628" alt="Screenshot 2023-12-10 at 3 58 41 PM" src="https://github.com/omotuno/baseball_salary_prediction/assets/65866718/c6a5ffb3-6a20-497b-a0de-23d89966abfd">

<img width="643" alt="Screenshot 2023-12-10 at 3 59 16 PM" src="https://github.com/omotuno/baseball_salary_prediction/assets/65866718/b648733b-57d0-40fc-ac6c-861af390640e">

<img width="618" alt="Screenshot 2023-12-10 at 3 59 33 PM" src="https://github.com/omotuno/baseball_salary_prediction/assets/65866718/f4460842-258b-46f9-96bd-71a62ad70b19">

-- Addressing issues like multicollinearity through variable selection
<img width="637" alt="Screenshot 2023-12-10 at 3 59 51 PM" src="https://github.com/omotuno/baseball_salary_prediction/assets/65866718/92446d89-4ec3-4f5c-942c-b3dcc35dd649">
<img width="620" alt="Screenshot 2023-12-10 at 4 00 06 PM" src="https://github.com/omotuno/baseball_salary_prediction/assets/65866718/ced5c74f-986b-44e6-91d6-e062fbf03906">

-- Applying transformations to satisfy linearity assumptions
<img width="604" alt="Screenshot 2023-12-10 at 4 00 18 PM" src="https://github.com/omotuno/baseball_salary_prediction/assets/65866718/7905a41a-d2aa-4b2e-8bbc-24049ccd48a2">

-- Identifying and removing influential observations

<img width="611" alt="Screenshot 2023-12-10 at 4 00 31 PM" src="https://github.com/omotuno/baseball_salary_prediction/assets/65866718/fbb51c50-f545-4abd-999c-8db8f363773e">

-- Evaluating model fit and prediction accuracy

<img width="699" alt="Screenshot 2023-12-10 at 4 00 59 PM" src="https://github.com/omotuno/baseball_salary_prediction/assets/65866718/d120e8f0-b62a-4285-897d-af2e25d0f20e">

<img width="613" alt="Screenshot 2023-12-10 at 4 01 12 PM" src="https://github.com/omotuno/baseball_salary_prediction/assets/65866718/a124a772-fd93-4523-9b1a-5316528df11d">

-- The final model incorporates 10 predictor variables and uses a power transformation on the response Salary. It has an adjusted R-squared of 0.75, indicating excellent fit. Variables for career runs batted in (CRBI) and career walks (CWalks) have the strongest relationships with salary.

-- Predictions on test data show low error rates, demonstrating that key performance metrics like hits, walks, and runs batted in are highly predictive of player salary. This model could help teams evaluate player contracts or arbitration cases based on statistical production.
