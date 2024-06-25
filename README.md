# Rainfall Prediction Using Machine Learning Algorithms

This project is part of an honors project where we explore different machine learning algorithms to predict rainfall in Australia. The dataset used is sourced from the Australian Government's Bureau of Meteorology.

## Project Overview

In this project, we aim to build a classifier to predict whether there will be rain the following day based on historical weather data. We explore and compare the performance of several machine learning algorithms:

1. Linear Regression
2. K-Nearest Neighbors (KNN)
3. Decision Trees
4. Logistic Regression
5. Support Vector Machines (SVM)

For each algorithm, we evaluate its performance using the following metrics:
- Accuracy Score
- Jaccard Index
- F1-Score
- LogLoss (where applicable)
- Mean Absolute Error
- Mean Squared Error
- R2-Score

## Dataset

The dataset used in this project is provided by the Australian Government's Bureau of Meteorology. It includes various meteorological features such as temperature, humidity, wind speed, and pressure, among others.

## Files Included

- **`data.csv`**: The raw dataset obtained from the Bureau of Meteorology.
- **`Rainfall_Prediction.ipynb`**: Jupyter notebook containing the Python code for data cleaning, preprocessing, model building, and evaluation.
- **`README.md`**: This file, providing an overview of the project and instructions.

## How to Use

To replicate this project on your local machine:

1. Clone this repository:
   ```
   git clone https://github.com/your_username/rainfall-prediction.git
   ```
2. Navigate to the project directory:
   ```
   cd rainfall-prediction
   ```
3. Install the required Python libraries:
   ```
   pip install -r requirements.txt
   ```
4. Open and run the `Rainfall_Prediction.ipynb` notebook using Jupyter or any compatible environment.

## Results

Each algorithm's performance metrics are detailed in the notebook:
- Accuracy scores vary from X% to Y% across different algorithms.
- Decision Trees achieved the highest F1-Score of Z.

## Conclusion

In conclusion, this project demonstrates the application of various machine learning algorithms to predict rainfall based on historical weather data. It highlights the importance of algorithm selection and evaluation metrics in predictive modeling.

---
