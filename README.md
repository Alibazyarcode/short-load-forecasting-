# short-load-forecasting-


# Tools Required


Python 3.7 is used during development and following libraries are required to run the code provided in the notebook:

- Tensorflow

- Numpy

- Matplotlib

- Pandas

- keras

# Dataset
Three different datasets were used to evaluate the proposed model. We selected these datasets based on the following criteria: 1) data volume because deep learning models are highly dependent on data, 2) different intervals, having different intervals of hourly, daily, weekly and monthly collection 3) availability for simplicity in reconstructing research results. These datasets have different properties, each of which is described below:


# Household Electric Power Consumption

This dataset measures electricity consumption in a household with a one-minute sampling rate for approximately four years. This archive contains 2075,259 records between December 2006 and November 2010 (47 months), which includes the following nine features: Date, Time, Universal active power, Universal reactive power, Voltage, Global intensity, Submetering1, Submetering2, and Submetering3.
    This data set can be downloaded through the link\footnote{\url{https://www.kaggle.com/datasets/uciml/electric-power-consumption-data-set}}.
  

# PJM Hourly Energy Consumption Data

This dataset is the hourly energy consumption data of PJM Interconnection LLC, a regional transmission organization (RTO) in the United States. It is part of the Eastern Connection Network, which operates an electrical transmission system to all  or parts of Delaware, Illinois, Indiana, Kentucky, Maryland, Michigan, New Jersey, North Carolina, Ohio, Pennsylvania, Tennessee, Virginia, West Virginia, and the District of Columbia. Hourly power consumption data comes from the PJM website and is in megawatts (MW). This data set is hourly from 2004-10-01 to 2018-08-03 have been collected. This data set only contains the date and  MW field per time zone, that can be downloaded through the link https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption.

# short term electricity load forecasting Panama

This database contains 48049 records related to the city of Panama and includes 16 feature columns. Information includes consumption, calendar information including school openings, and climate variables including temperature, relative humidity, rainfall, and speed. Data are collected in hourly records from January 2015 to June 2020. The data composition is as follows:
      
  -  Electric charge, in daily reports, is available from the network operator (CND).
      
  - Calendar information for school courses from the Panamanian Ministry of Education.
      
  -  Holiday calendar information from the "When on Earth https://whenonearth.net Website.
      
  - Climate variables such as temperature, relative humidity, precipitation and wind speed, for the three main cities of Panama, from Earthdata.

      
One of the important reasons for using this data is the abundance of features including environmental and climate factors that are included in it. Vacation and school data are sparse, in addition to web site information and PDF files. This data set can be downloaded through the link https://www.kaggle.com/ernestojaguilar/shortterm-electricity-load-forecasting-panama.

# Example of read data:

![image](https://github.com/Alibazyarcode/short-load-forecasting-/assets/166903490/ef80064a-5ba9-405c-8578-7ac03be649a7)

# panama dataset
![image](https://github.com/Alibazyarcode/short-load-forecasting-/assets/166903490/72b3c87a-6d83-4df6-9ab1-d8c90739598a)


# For time interval change this field:

- H for Hour
  
- D for Day
  
- 7D for Week
  

![image](https://github.com/Alibazyarcode/short-load-forecasting-/assets/166903490/fa2c482d-db63-4bda-badf-c676b98ed4ee)







