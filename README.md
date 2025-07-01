  **Metro Traffic – Big Data Visualization & Predictive Analytics**

This project analyzes historical traffic data from the I-94 Interstate highway in the Minneapolis–St. Paul metro area using PySpark, Kafka, and visualization tools. It demonstrates the use of Big Data techniques to process, visualize, and forecast traffic volume patterns based on time, weather, and holiday variables.

**Project Highlights**


  **Data Cleaning and Transformation**


   1.Data Loading: Loaded the Metro_Interstate_Traffic_Volume.csv dataset using Apache Spark for efficient large-scale processing.
  
  2.Dataset URL: UCI Repository – Metro Interstate Traffic Volume
  
  3.Missing Values Handling: Identified and treated missing values to improve data completeness and ensure model reliability.
  
  4.Categorical Transformation: Converted categorical columns (holiday, weather_main, weather_description) into numerical indices using StringIndexer to support modeling and correlation analysis.
  
  5.Duplicate Removal: Detected and removed duplicate records to ensure data accuracy and consistency.
  
  6.Data Sorting: Sorted the dataset by date_time to prepare for chronological analysis and visual exploration.
  

  **Data Visualization**


  1.Historical Traffic Volume: Plotted historical traffic volume to observe daily and seasonal trends using Matplotlib and Seaborn.
  
  2.Scatter Plot: Created scatter plots comparing traffic volume with variables like temperature and cloud cover to uncover hidden relationships.
  
  3.Time Series Decomposition: Performed decomposition to separate trend, seasonality, and residual components, revealing weekly traffic cycles.
  
  4.Forecasting: Visualized traffic volume forecasts using ARIMA, showing both historical and future values with clear interpretability.
  

  **Predictive Analytics**


  1.Summary Statistics: Computed key metrics such as mean, standard deviation, skewness, and kurtosis for all numeric features including traffic volume, temperature, and precipitation.
  
  2.Correlation Analysis: Used PySpark to calculate Pearson correlation between traffic volume and weather variables, identifying key influencing factors.
  
  3.Modeling: Applied ARIMA time-series modeling for short-term traffic volume forecasting and evaluated trends with visual overlays.

  
![Picture1](https://github.com/user-attachments/assets/70faebd9-30f4-4b2e-b24c-89492ad6b8b3)

![Picture2](https://github.com/user-attachments/assets/ed59b937-7c23-41e2-b85e-e0417ab14eee)

![Picture3](https://github.com/user-attachments/assets/8a3840fe-ec3f-4228-a771-b8c0c8649e5b)


  **Kafka Integration**


  1.Kafka Producer: Implemented a real-time Kafka producer that streamed data from a public API into a Kafka topic.

  2.Kafka Consumer: Developed a Kafka consumer to subscribe to the topic and receive messages in real-time.

  3.Extended Kafka Consumer: Enhanced the consumer to process messages with PySpark, compute descriptive statistics, and export results for analysis.

  **Key Findings**


  1.Weather Impact: Discovered that weather conditions (e.g., heavy rain, snow, cloud cover) significantly influence traffic volume.

  2.Holiday Effect: Observed reduced or highly variable traffic volume on national and regional holidays.

  3.Trends and Seasonality: Identified clear weekly traffic patterns through time series decomposition.

  4.Forecast Accuracy: Achieved reasonably accurate traffic volume predictions using ARIMA time-series modeling.






