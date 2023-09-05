# IPL Match Win Predictor
Based on the first innings perfomance of a team, this app takes in current data of second innings and tries to predict the win probability of either of the teams. 

## The flow of the app is as follows:
1. Load the dataset into pandas dataframe
2. Perform EDA on the dataset and extract new features
3. Fit a Machine Learning Pipelind on the data extracted
4. Integrate the pipleline with the UI which is created using streamlit
5. Deploy the app on Heroku