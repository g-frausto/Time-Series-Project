# Forcecasting Power Consumption for Electric Buses using different Recurrent Neural Network

In this project we are interested in forecasting the power consumption for electric busses commuting on their regular routes. We used three different Reccurent Neural Networks, vanilla RNN, gated recurrent unit (GRU), and Long-short term memory (lstm). We were also interested in testing in the models ability to forecast multiple time-steps forward. 

## Dataset
The following is the power consumption versus distance traveled for an electric bus.
![Forecasting_Distance](/plots/data_example_2.png)

## Summary of Results 
The following graphs are examples of various models forecasting one, two, three, and four time steps ahead. 

### RNN Results

![RNN_Prediction](/plots/presentation%20plots/spread%20graphs/RNN_all_prediction_test_set.png)

### GRU Results

![GRU_Prediction](/plots/presentation%20plots/spread%20graphs/GRU_all_prediction_test_set.png)

### LSTM Resutls

![LSTM_Prediction](/plots/presentation%20plots/spread%20graphs/LSTM_all_prediction_test_set.png)