#  Electricity Bill Consumption Prediction using Machine Learning

##  Project Overview

This project predicts household electricity consumption using Machine Learning techniques. It analyzes household characteristics such as the number of rooms, number of people, house area, appliance usage, and other features to estimate electricity consumption in units.

The project compares multiple Machine Learning algorithms to identify the model that provides the best prediction accuracy.



##  Objective

- Predict household electricity consumption.
- Compare the performance of different Machine Learning algorithms.
- Help users estimate electricity usage in advance.
- Improve energy management through predictive analytics.



##  Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn



##  Dataset

The dataset contains household electricity consumption information with features such as:

- Number of Rooms
- Number of People
- House Area
- Air Conditioner Usage
- Television Usage
- Flat or Independent House
- Number of Children
- Urban or Rural Area

**Target Variable:**
- Electricity Consumption (Units)


##  Machine Learning Algorithms

The following Machine Learning algorithms were implemented and compared:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- K-Nearest Neighbors (KNN)

The models were evaluated using **Mean Absolute Error (MAE)** to determine the best-performing algorithm.



##  Project Workflow

1. Load the dataset
2. Data preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature selection
5. Train-test split
6. Train Machine Learning models
7. Evaluate model performance
8. Predict electricity consumption



## 📊 Results

Among the implemented algorithms, the **Random Forest Regressor** provided the best prediction performance for this dataset.

The project demonstrates that Machine Learning can effectively estimate household electricity consumption and assist users in understanding their future energy usage.



##  Project Structure

```
Electricity-Bill-Consumption-Prediction/
│
├── Electricity_Bill_Consumption_Prediction.ipynb
├── Household energy unit data.csv
└── README.md
```



##  Features

- Predicts household electricity consumption.
- Compares multiple Machine Learning algorithms.
- Performs data preprocessing and visualization.
- Evaluates model performance using Mean Absolute Error (MAE).
- Simple and easy-to-understand implementation.





