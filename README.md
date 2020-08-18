# Influenza-Viral-Strain-Prediction

The influenza viruses in the seasonal flu vaccine are selected each year based on surveillance data indicating which viruses are circulating and forecasts about which viruses are the most likely to circulate during the coming season. The degree of similarity between available vaccineviruses and circulating viruses is also an important factor to consider. Vaccine viruses must be similar to the influenza viruses predicted to circulate most commonly during the upcoming
season. 

In this project, we are trying to keep track of the mutations in the Influenza A strain using time-series based machine learning methods. The model trains on the dataset of the past influenza viral strains and prediction of the future viral sequences is done using Time Series Forecasting. Deep Learning prediction methods like dense Neural Networks, ARIMA and LSTM(RNNs) are used for forecasting. In order to enhance our forecasting model, positions which were SNP’s were found using Multiple Sequence Alignment and only the SNP sites were replaced by the sequences predicted from the Time Series forecasting model.
