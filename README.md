# Hackathon
Spencer Kline and I wrote this code for the 2020 BDBI Datathon using Kaggle datasets but couldnt get the provided HDF4-EOS data to work in the model 

WildFire hackathon

In the fight to reduce the impact of wildfires we must find the cause of these fires. 
This code creates a deep learning neural network to determine whether a wildifre was caused by nature of human-based sources. The data used to train the model was gathered from three different sources.

Training and hyperparameter tuning of the neural network gives ~87.63% accuracy for prediction of natural/human causes on the test of fires between 2011 and 2014. Therefore, the model can be helpful in assigning the causes of US wildfires, improving the understanding of wildfire creation.

The data that is used for training should be in a data folder.
US wildfire data downloaded here <https://www.kaggle.com/rtatman/188-million-us-wildfires>.
Climate data downloaded here <https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data#GlobalLandTemperaturesByCity.csv>. (GlobalLandTemperaturesByCity.csv)
Historical stock data downloaded here <https://www.kaggle.com/ehallmar/daily-historical-stock-prices-1970-2018> historical_stock_prices.csv
<https://www.kaggle.com/sobhanmoosavi/us-weather-events> US_WeatherEvents_2016-2019.csv


pip3 install -r requirements.txt

python3 main.py
