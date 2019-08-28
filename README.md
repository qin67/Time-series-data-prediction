# Time-series-data-prediction
 <br>
Compare several methods including LSTM, GRU, TCN <br><br>
For more information about TCN, check https://github.com/philipperemy/keras-tcn<br>https://github.com/locuslab/TCN<br>
HQQ.csv is the data measured each 30 min automatically in one location by online water quality monitor system<br>
Water Quality Record.csv is the data measured daily in one location by lab<br><br>
What we find:<br>
1. When dataset is big enough, for the single variable time series prediction, TCN is obviously not as good as LSTM & GRU
2. LSTM/GRU get the best result when we set the batch size as 1, but when handling large dataset, that would need a long time to train. 
