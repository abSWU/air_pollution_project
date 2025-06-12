# Air Quality Trends in the US (2000-2023)
The purpose of this project was to analyze air quality data in the US from 2000-2023, as well as to see if air quality has increased or decreased over time.

##**DISCLAIMER**
This project used an averaged AQI (Air Quality Index) of different pollutants to show trends in the data. 
This is **NOT** an accurate measurement for air quality, as different pollutants have differing AQI formulas, scales, and health impacts.
That being said, this project was mainly made for **personal educational and practice purposes only**, as this was my first time making a project with pandas and real world data.

**##Project Summary**

  Used tools such as Python, pandas, matplotlib, and JupyterNotebook
  
  Data Used: https://www.kaggle.com/datasets/guslovesmath/us-pollution-data-200-to-2022/data
  
  Cleaned and filtered the dataset
  
  Took an average of AQIs from the four pollutants: SO2, CO, O3, and NO2
  
  Compared AQI Trends over 4 separate time periods (2000-2005, 2006-2011, 2012-2017, 2018-2023)
  
  Visualized monthly and yearly trends over the 23 year time interval with matplotlib

**##Data Cleaning**

  Dropped irrelevant columns such as address and hourly max data
  
  Dropped rows with missing information

**##Findings**

  The average AQI seemed to decreased from 2000-2023, suggesting that there may have been improvements in air quality as time went on
  
  Average AQI was highest in 2000-2005 (~22.96 ), and lowest in 2018-2023 (~15.21)
  
  While 2018-2023 had the lowest mean AQI, there was an increase near 2020 and forward, which may indicate signs of increasing air pollution in recent years.
