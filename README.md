# Project_2
Project 2 with jason, brendan, eric and niall
We used an LSTM Model for a GDP and Inflation Predictor for the 5 largest economies in the world being, China, Unites States, Japan, Germany and India.
This was a two layer LSTM Model.
Most of our anaysis was done using 200-1000 epochs and batch size of 1-10.
We were able to produce graphs for each analysis showing the real data line and our predicted line showing how closely the predicted line followed the real data. 
We used R2 Score as our evaluation because that jst lets us know how closely our predicted lione was to the real data line. 
Due to time constraints we weere not able to: Use a randomForrestRegression Model to compare with LSTM results. ALso, we were not able to get LIME evaluations to work for our LSTM as the only info available for LIME was RandomFOrrestRegression related. 
We wanted to make out of smaple precitions for the future but were not able to due to time constraints and information availbale at the time.

Overall, the models worked great with the data getting r2 scores in the .90s with a couple outlier in the negative and and .10 range. 
