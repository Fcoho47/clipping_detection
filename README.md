# Clipping Detection

## Abstract
In this project I trained an ML model to classify clipping in energy generation curves of solar plants. For this, I was given a simulated dataset with ..... curves.

Initially, I tried different ML approaches to achieve "good" accuracy. However in this project I will focus on preprocessing, ML training and final model development.

## Description

- Dataset:  
  The dataset contains information from 101 solar plants.

- data_extractor:
  This code transforms raw data into a normalized theoretical/generated vectors from solar plants CSV files. It generates 123,498 data and label vectors.
  Using this code, the transformed data is saved into a file called "variables.plk"
  
- training:
  The choosen model is XGBoost. After many trials (which will analized and presented in other project) I found that the best model, in terms of accuracy, time and output size, is XGBoost.


