# Exoplanet Classification 🪐🔭
I wrote this code for a fun little at-home project. I used publically available data I recieved from the NASA exoplanet database API. The dataset includes data for confirmed and candidate exoplanets. My program uses gradient boosting descent to try to predict whether a candidate is a planet, or if it was a false-positive. 

# Results
Interestingly, on the test-train split, my code reaches an accuracy rating of 1.0. This made me think that there was some error in my coding, but it seems to be write and without type. I tried changing models to logistic regression and got an accuracy of .91.

So what's happening? The main explanation I can come up with for this is that maybe the planets that we know the planet-status for are just particularly easy to predict from the data, hence why we indeed have their status known. Then, the model I made would be not-so-great for predicting the unclassified planets anyway. 
 
