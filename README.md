# Bank-Nifty-Price-Prediction-using-DNN-and-Wavelet-Decomposition
This is a Deep Learning Model created with keras and tensorflow to predict price of Bank Nifty Index.

Features used are the closing price, Wavelet decomposition of the closing series , Advance Decline Ratio and India Volatility Index.

Prices are taken from CMIE Database (Prowessiq).

LSTM Arctitecture is used for the Deep Neural Network with Adam Optimizer.

This is a Regression Based Model.

Percent Change of the predicted series is used for classification into 3 clusters. 
One with percent change greater than 1.5, one with percent change less than -1.5 and one with percentage change between -1.5 and 1.5.
