# Multivariate Time Series Models in Keras

# Introduction
This repository contains a throughout explanation on how to create different deep learning models in Keras for multivariate (tabular) time-series prediction. The data being used in this repository is from the [KB-74 Opschaler](https://github.com/deKeijzer/KB-74-OPSCHALER) project. The goal of this project is to do gas consumption prediction of houses on an hourly resolution, for the minor Applied Data Science at The Hague University of Applied Sciences.

# Data used
The data has a samplerate of one hour.  
Features: 
- Electrical power consumption (ePower)
- Wind speed (FF)
- Rain intensity (RG)
- Temperature (T)
- Timestamp YYYY:MM:DD HH:MM:SS (datetime)

Target:
- Gas consumption (gasPower)

# Models used
- Deep neural network (DNN)
- Recurrent neural networks: LSTM & GRU (RNN)
- Convolutional neural network (CNN)
- Timedistributed(CNN) -> RNN -> DNN
...