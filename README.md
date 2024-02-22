# Kernel Density Estimation-Exploratory-Data-Analysis-from-Environmental-Sensor-Telemetry-Data
Isolation Forest Exploratory Data Analysis from Environmental Sensor Telemetry Data with temperature, humidity, carbon monoxide (CO) and liquid petroleum gas (LPG)

## Background
The data was taken with a sensor device from a physical environment with highly variable temperature and humidity from 12 to 19 July 2020. The data were taken for analysis with isolation forest.
data link: https://www.kaggle.com/datasets/garystafford/environmental-sensor-data-132k/data 

## Data Preprocessing
Device 1c:bf:ce:15:ec:4d sensing in the environment with highly variable temperature and humidity was selected for analysis. The data of timestamp, temperature, humidity, carbon monoxide (CO) and liquid petroleum gas (LPG) were selected for analysis with isolation forest. To reduce running time and cost, the data were sampled to 0.1 times to 10591 data. A new dataset was generated in csv format named place2_dataset2_10591.csv. 

## Exploratory Data Analysis
### Kernel Density Estimation
The data of timestamp, temperature, humidity, carbon monoxide (CO), and liquid petroleum gas (LPG) were found to the outliners by Kernel Density Estimation respectively. the top and button 2% of data points with the lowest probability densities can be considered outliers. 

### Correlation of environmental aspects
The data of timestamp, temperature, humidity, carbon monoxide (CO), and liquid petroleum gas (LPG) were used to find the correlation. There was a strong correlation between CO and LPG (corr: 1). A scatter diagram between CO and LPG showed that there is a straight line with the orientation from bottom left to top right. All the outliners shown in the graph are both outliners of CO and LPG.


