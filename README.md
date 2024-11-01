# Probabilistic-Graphical-Models

**Model 1: Stock Data Analysis**   

Numerous large-scale projects and prominent financial institutions focus
 on predicting financial markets using advanced Artificial Intelligence (AI) and
 Machine Learning (ML) approach, leading to publicly available stock indices data
 sets. In this report, we will model, integrate the financial market movements using
 probabilistic graphical model approach and will incorporate economic indicators
 using external factors.
 
 This probabilistic approach incorporating a wide range of external factors that
 influence market behavior, such as macroeconomic trends, economic indicators,
 geopolitical events, technical indicators, regional and sector-specific develop
ments.
 
![Major_Indices_CP](https://github.com/user-attachments/assets/1dfb68c2-cf5e-481a-85f6-8d7b3b6ae279)


**Data Sources and Collection: ** 
Data used in this project were collected mainly from yahoo finance and government open source platforms. 

Major 7 indices  were considered in this study in three different regions such  as US, Europe and Asia. We use python API which will pull  historical data from yahoo finance (Indices data) and world  bank (wbdata for economic indicators) and store it in google  cloud for model development.

 Some of major indices were considers such as:
 
 • SP 500 (Standard and Poor’s 500)– USA: Represents 500  of the largest publicly traded companies in the United States.
 
 • DowJones Industrial Average (DJIA)– USA: Includes 30  major, large-cap companies across various industries.
 
 • NASDAQComposite– USA: Encompasses around 3,000  companies listed on the NASDAQ Stock Market.
 
 • FTSE 100 (Financial Times Stock Exchange 100 Index) UK: Tracks the 100 largest companies listed on the London  Stock Exchange.
 
 • Nikkei 225– Japan: Consists of 225 blue-chip companies listed on the Tokyo Stock Exchange.
 
 • DAX(Deutscher Aktienindex)– Germany: It tracks 40 of the largest and most liquid companies on the Frankfurt Stock  Exchange.
 
 • Sensex (Sensitive Index)– India: Sensex tracks 30 well established and financially sound companies listed on the  Bombay Stock Exchange.


** Model Approach:**
1. Data Collection, (Yahoo finance for educational and exploratory purpose)
2. Data Preprocessing,
3. Feature Engineering, (Functions to create 15 different technical indicators to evaluate the stocks)
4. Model Selection (Time series models like ARIMA, RNN and LSTM will be leveraged)
5. Evaluation Metrics (Mean Square Error (MSE), Mean Absolute Error (MAE))
6. Results Interpretation And Visualization
7. Optionally, business analytics to understand different varities of sectors and revenue models.

![image](https://github.com/user-attachments/assets/c51eb893-0558-47f0-b4a7-98261db5507e)


**Model 2: Weather Data Analysis:**

City List: Created a list of 20 major cities with their latitude and longitude coordinates.

Loop through Cities: The For loop goes through each city and calls get_weather_open_meteo, passing the latitude, longitude, and city name. 

Prediction: Time series foundational models would be utilized.

** Model Approach:**
1. Data Collection, (Open Source Weather Platforms),
2. Data Preprocessing,
3. Feature Engineering, (Functions to create different variables like humitity, wind speed etc.,)
4. Model Selection (Time series models like ARIMA, RNN and LSTM will be leveraged),
5. Evaluation Metrics (Mean Square Error, etc),
6. Results Interpretation, and
7. Optionally, flat maps will be implemented for better visualization.

 



