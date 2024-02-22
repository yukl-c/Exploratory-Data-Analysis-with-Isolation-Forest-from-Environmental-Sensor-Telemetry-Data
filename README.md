# Kernel Density Estimation-Exploratory-Data-Analysis-from-Environmental-Sensor-Telemetry-Data
Isolation Forest Exploratory Data Analysis from Environmental Sensor Telemetry Data with temperature, humidity, carbon monoxide (CO) and liquid petroleum gas (LPG)

## Background
The data was taken with a sensor device from a physical environment with highly variable temperature and humidity from 12 to 19 July 2020. The data were taken for analysis with isolation forest.
data link: https://www.kaggle.com/datasets/garystafford/environmental-sensor-data-132k/data 

## Data Preprocessing
Device 1c:bf:ce:15:ec:4d sensing in the environment with highly variable temperature and humidity was selected for analysis. The data of timestamp, temperature, humidity, carbon monoxide (CO) and liquid petroleum gas (LPG) were selected for analysis with isolation forest. To reduce running time and cost, the data were sampled to 0.1 times to 10591 data. A new dataset was generated in csv format named place2_dataset2_10591.csv. 

## Exploratory Data Analysis
### Kernel Density Estimation
The data of timestamp, temperature, humidity, carbon monoxide (CO), and liquid petroleum gas (LPG) were found to the outliners by Kernel Density Estimation respectively. the top or button 2% of data points with the lowest probability densities can be considered outliers. 

![image](https://github.com/yukl-c/Exploratory-Data-Analysis-with-Isolation-Forest-from-Environmental-Sensor-Telemetry-Data/assets/72858964/8216ba4c-7867-4610-a08d-b788f5c65976)

The outliner of temperature mainly are below around 22°C or above around 30°C.

![image](https://github.com/yukl-c/Exploratory-Data-Analysis-with-Isolation-Forest-from-Environmental-Sensor-Telemetry-Data/assets/72858964/22352f2f-197d-475a-ae14-6b8603b63c22)

The outliner of humidity mainly are below around 50 or above around 80.

![image](https://github.com/yukl-c/Exploratory-Data-Analysis-with-Isolation-Forest-from-Environmental-Sensor-Telemetry-Data/assets/72858964/3478bb09-aebb-45f0-8271-9494ac943fef)

The outliner of CO mainly are above around 0.0048.

![image](https://github.com/yukl-c/Exploratory-Data-Analysis-with-Isolation-Forest-from-Environmental-Sensor-Telemetry-Data/assets/72858964/a2fb2f1d-6d35-44da-83bc-a66201c70de5)

The outliner of LPG mainly are above around 0.0048.

### Correlation of environmental aspects
The data of timestamp, temperature, humidity, carbon monoxide (CO), and liquid petroleum gas (LPG) were used to find the correlation. There was a strong correlation between CO and LPG (corr: 1). 
![image](https://github.com/yukl-c/Exploratory-Data-Analysis-with-Isolation-Forest-from-Environmental-Sensor-Telemetry-Data/assets/72858964/a06ddf3f-65f5-4fe1-8266-dbe28e605384)

A scatter diagram between CO and LPG showed that there is a straight line with the orientation from bottom left to top right. All the outliners shown in the graph are both outliners of CO and LPG.
![image](https://github.com/yukl-c/Exploratory-Data-Analysis-with-Isolation-Forest-from-Environmental-Sensor-Telemetry-Data/assets/72858964/57e31a63-964b-447d-92a7-c4112ffab96a)


