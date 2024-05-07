# Facies Classification Using Machine Learning
## Project Overview

This repository contains the work completed for the PETE 419/686 course on Petroleum Data Analytics and Machine Learning at Texas A&M University, under the guidance of Associate Professor Sid Misra. The primary objective of this project is to develop various machine learning classifiers to perform facies classification on the Volve Dataset, focusing on lithology identification using well-log data.

## Project Structure

- *Train_Test.ipynb*: Notebook for training and testing classifiers on Wells 2 and 3. Features preprocessing steps such as outlier detection, scaling, and feature transformations, along with the integration of clustering techniques for enhanced feature engineering.
- *Deploy.ipynb*: Deployment of the top three performing models on Well 1, ensuring correct preprocessing sequence. Outputs include depth-wise prediction variations and an export of the mean and range of predictions to Prediction.xlsx.
- *Prediction.xlsx*: Excel file containing detailed predictions for Well 1, including depth and gamma-ray log values.
- *Distribution.ipynb*: Analysis of the stochastic behavior of the top-performing techniques through repeated experimentation without a fixed random seed, showcasing distributions of performance metrics.

## Techniques Used

Logistic Regression, K-Nearest Neighbors, Gaussian Naive Bayes, Support Vector Machines (both linear and RBF kernels), AdaBoost, Random Forest, Gradient Boosting, and Neural Networks. This variety ensures a robust analysis of the dataset with different algorithmic approaches.

## Key Results

- Detailed evaluation using metrics like F1 Score, AUC, and Matthews Correlation Coefficient, with a special focus on addressing class imbalance.
- Insight into the predictability of different facies types through confusion matrices and performance metrics.

## Libraries and Tools

Python with essential libraries like Scikit-learn for machine learning algorithms, Pandas for data manipulation, and Matplotlib and Seaborn for data visualization.

## Usage

Clone this repository and follow the notebooks to replicate the analysis. Ensure all dependencies are installed as per the requirements listed in the repository.

## Acknowledgments

Thanks to Texas A&M University and Professor Sid Misra for the guidance and resources provided for this project.
