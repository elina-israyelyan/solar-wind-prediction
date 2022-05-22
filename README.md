# Solar Wind Prediction

The repository contains the experiments done for the time series course project at American University of Armenia. \
In this repository you will find ARIMA and VAR implementations for proton speed prediction using magnetic field vector. \
Also we have implemented Neural Network to understand the relationship between the magnetic field vector and proton speed to have better and more accurate prediction.

## Our methods

So to predict the proton speed we have developed the current steps. \
First we train a VAR model and forecast the magnetic field vector for future timestamps.\
Next we predict the proton speed based on the forecasted magnetic field vector. Here we are using the pretrained neural network. \
The codes for both steps can be found in the `notebooks` directory. 
