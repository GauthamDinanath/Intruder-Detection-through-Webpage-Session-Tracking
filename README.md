# Intruder-Detection-through-Webpage-Session-Tracking
Anomaly detection

## Dataset
Data from Blaise Pascal University proxy servers uploaded to Kaggle.

## Requirements
`Python`

## Results & Discussion
Site data was normalized and feature engineering was done on time data.
Since the data was unbalanced, stratified cross validation was used. LightGBM showed the best accuracy at detecting anamoly in web sessions.

![1](https://user-images.githubusercontent.com/64839751/93212468-ed669480-f762-11ea-91dd-5244cb1eb31b.png)
