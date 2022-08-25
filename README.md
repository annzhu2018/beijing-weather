# beijing-weather

Air pollution is one of the great killers of our time. It occurs when the surrounding air contains gases, dust, fumes or odors in high enough quantities to be harmful to the health of humans and animals or enough to cause damage to plants and materials. With the fast development of the economy and industrial construction, air pollution has always been a major problem in China, especially in cities like Beijing. The objective of this project using big data analytic techniques to predict the hourly concentration of air pollutant level over a period of 48 hours in Beijing. We are provided two types of historical datasets: meteorological data including variables such as humidity, wind direction and speed, temperature, and atmospheric pressure; air pollutants data, including pollutants such as PM2.5, PM10, O3, NO2, CO and SO2. I will use meteorological data as the training data and the pollutants data at the labels. When predicting air quality, there are many variables to take into account, some of which are quite unpredictable. Predicting air quality, therefore, involves many difficulties, which requires extra attention to the details. Throughout this project, I will be performing the overall steps of exploring the data, preparing the data, selecting the models for predictions, comparing and testing the models, and finally coming up with the best result.


Tool: Jupyternotebook

Description of the uploaded files
1. Final output.ipynb: 
      Combine the grid weather and observed weather.csv for the first two day of May in 2018 and match them with the air quality station.
2. Model.ipynb:
      XGboost model, which outputs the final submission. csv
3. LSTM_aotizhongxin(scaled)-201804all_finalLast.ipynb: 
      LSTM model training
4. april-june.ipynb.ipynb: 
      Split the data from April to June in 2017 from the whole dataset.
5. gridob04-06.ipynb: 
      Data preprocessing for both gridweather and observed weather from April to June
6. air1704_1706.ipynb: 
      Data preprocessing for air quality station data from April to June
7. 5002Preprocess_grid.ipynb: 
      Calculate the distance between the stations and pair up the closest weather station and air quality station.
8. repot.pdf
    
