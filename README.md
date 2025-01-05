**Flight Price Prediction**

**Overview**

This project focuses on predicting flight ticket prices using machine learning. 
The dataset includes information such as airline, journey date, source, destination, total stops, and duration, among other features. By preprocessing the data and training models, this project aims to predict flight prices accurately.

**Table of Contents**

1. Project Workflow
2. Dataset Description
3. Key Features
4. Technologies Used
5. Installation
6. How to Use
7. Results and Insights
8. Future Scope
9. License
    
**Project Workflow**

The project follows these key steps:

**1.Data Preprocessing:**

- Handled missing values by dropping rows.

- Extracted useful features from columns like Date_of_Journey, Dep_Time, and Duration.

- Encoded categorical features using OneHotEncoding and ordinal mapping.
- 
**2.Exploratory Data Analysis (EDA):**
  
- Analyzed correlations between features using heatmaps.
- Studied trends between flight prices and various factors like stops, duration, and airlines.
  
**3.Feature Engineering:**
- Selected the most important features using statistical methods and feature importance scores.
  
**4.Model Building:**
Trained machine learning models on the preprocessed dataset to predict flight prices.

**Dataset Description**

The dataset contains the following key columns:

**Airline**: Name of the airline.

**Date_of_Journey**: The journey date.

**Source**: Starting point of the journey.

**Destination**: Endpoint of the journey.

**Route**: Route taken by the flight.

**Dep_Time**: Departure time of the flight.

**Arrival_Time**: Arrival time of the flight.

**Duration**: Total time taken by the flight.

**Total_Stop**s: Number of stops between source and destination.

**Price**: Ticket price (target variable).

**Key Features**

- Comprehensive data preprocessing pipeline for cleaning and feature engineering.
- Consistent handling of training and test datasets.
- Feature selection for identifying important predictors.
- Visualizations to understand correlations and trends in the data.
**Technologies Used**
- Programming Language: Python
-Libraries:
  - Pandas and NumPy: Data manipulation
  - Matplotlib and Seaborn: Visualizations
  - scikit-learn: Preprocessing, modeling, and feature selection
  - Jupyter Notebook: Code development and execution


**Results and Insights**

- The project highlights the impact of features like Airline, Total_Stops, and Duration on ticket prices.
- Feature selection improved model performance by focusing on the most relevant predictors.
  
**Future Scope**

- Include additional features like seasonality and demand to enhance predictions.
- Experiment with advanced machine learning models and hyperparameter tuning.
- Deploy the trained model using Flask or Streamlit for a web-based prediction tool.



