# Solar-Cells-Output-Prediction

PROBLEM STATEMENT

Solar Power forecasting for a Solar Power System is a very active research field, as reliable information about the future power generation allow for a safe operation of the power grid and helps to minimize the operational costs. Deep Learning algorithms have shown to be very powerful in forecasting tasks, such as economic time series or speech recognition. Up to now, Deep Learning algorithms have only been applied sparsely for forecasting renewable energy power plants. By using different Deep Learning Algorithms, such as RNN,LSTM with different Feature extraction method like PCA,1D CNN , Auto encoders , My motive is to show the forecast strength of these algorithms compared to a standard MLP and traditional machine learning model in forecasting the energy output of 21 solar power plants.

POSSIBLE SOLUTION

Applying different deep learning techniques like MLP,Simple RNN,LSTM,GRU on solar power system to predict a hour/day ahead solar power generation based on Certain weather condition of the location of solar power system.
![alt text](https://github.com/Soumyapro/Solar-Cells-Output-Prediction/blob/main/download.png?raw=true)

DATA DESCRIPTION

The GermanSolarFarm data set contains 21 photovoltaic facilities in Germany. Their installed nominal power ranges between 100kW and 8500kW. The PV facilities range from PV panels installed on rooftops to fully fledged solar farms. They are distributed throughout Germany as shown in the attached image. For each facility historical NWP data and the produced power in a three-hour resolution for 990 days are available. All-time series in the data set, except the measured power output, are normalized between 0 and 1 using the min max normalization. The target variable, the measured power output, is normalized using the nominal output capacity of the corresponding PV facility. Therefore, allow the comparison of the forecasting performance without taking the size of the PV facilities into account.


