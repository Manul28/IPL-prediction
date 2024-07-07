# IPL-prediction
IPL-prediction System using Machine Learning and Deployed on streamlit

## About This Project

The "IPL Win Predictor" leverages logistic regression to provide insights into the probability of a team winning an IPL match. This model analyzes various match features, team performance, and player statistics to offer real-time predictions.

## Project Preview
![Capture](https://github.com/rajatrawal/ipl-win-predictor/assets/72153827/071a020f-0bf5-4872-904f-5f9a0e928fd1)

## Demo
Click on the Below Link
[![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20Predictor-brightgreen)](https://ipl-match-predictor.streamlit.app/)

## Usage

To make predictions, provide the following parameters when prompted:

- **Batting Team**: The team currently at bat.
- **Bowling Team**: The team currently bowling.
- **City**: The location of the match.
- **Current runs**: The current score of batting team.
- **Overs Completed**: The number of overs completed.
- **Wickets**: The number of wickets lost.
- **Target Runs**: The total runs scored by a bowling team.

The predictor will calculate the probability of the batting team winning based on these parameters and the current match situation.


## Technologies Used

This project leverages the following technologies:

- [Python](https://www.python.org/)
- [Logistic Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
- [NumPy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [Streamlit](https://www.streamlit.io/)
