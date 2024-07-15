# IPL Win Predictor
## About This Project

The "IPL Win Predictor" leverages logistic regression to provide insights into the probability of a team winning an IPL match. This model analyzes various match features, team performance, and player statistics to offer real-time predictions.

### Features

- **Real-Time Predictions**: Get live predictions for IPL match outcomes based on the current match situation.

- **Interactive Interface**: The predictor is deployed on Streamlit, offering a user-friendly interface for exploring match scenarios.

- **Customizable Inputs**: Adjust the match parameters and teams to simulate different match scenarios.

- **Deployment**: Hosted on Streamlit Cloud for easy access and sharing.

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

## Usage

To make predictions, provide the current match situation including team performance, player statistics, and match conditions. The predictor will calculate the probability of a team winning.
