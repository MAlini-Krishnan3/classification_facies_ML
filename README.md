# Facies Classification Using Machine Learning
## Project Overview

This repository contains the work completed for the PETE 419/686 course on Petroleum Data Analytics and Machine Learning at Texas A&M University, under the guidance of Associate Professor Sid Misra. The primary objective of this project is to develop various machine learning classifiers to perform facies classification on the Volve Dataset, focusing on lithology identification using well-log data.

## Project Structure

- *Train_Test.ipynb*: Notebook for training and testing classifiers on Wells 2 and 3. Features preprocessing steps such as outlier detection, scaling, and feature transformations, along with the integration of clustering techniques for enhanced feature engineering.
- *Deploy.ipynb*: Deployment of the top three performing models on Well 1, ensuring correct preprocessing sequence. Outputs include depth-wise prediction variations and an export of the mean and range of predictions to Prediction.xlsx.
- *Prediction.xlsx*: Excel file containing detailed predictions for Well 1, including depth and gamma-ray log values.
- *Distribution.ipynb*: Analysis of the stochastic behavior of the top-performing techniques through repeated experimentation without a fixed random seed, showcasing distributions of performance metrics.
