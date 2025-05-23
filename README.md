# Healthcare Premium Prediction

## Problem Statement :
Determining the premium for health insurance involves analyzing multiple factors like age, BMI, smoking status, and number of dependents. Insurers need efficient, scalable models that can provide accurate premium predictions without manual intervention. Existing approaches may lack flexibility or fail to generalize well across diverse populations.

## Dataset :
The dataset was provided by Atliq Technologies for training purpose.

## Approach :
Applying machine learing tasks like Data Exploration, Data Cleaning, Feature Engineering, Model Building and model testing to build a solution that should able to predict the premium of the personal for health insurance.

- **Data Exploration :** Exploring the dataset using pandas, numpy, matplotlib, plotly and seaborn.
- **Exploratory Data Analysis :** Plotted different graphs to get more insights about dependent and independent variables/features.
- **Feature Engineering :** Numerical features scaled down and Categorical features encoded.
- **Model Building :** In this step, first dataset Splitting is done. After that model is trained on different Machine Learning Algorithms such as:
    1) Linear Regression
    2) Decision Tree Regressor
    3) Random Forest Regressor
    4) Gradient Boosting Regressor
    5) XGBoost Regressor
    6) KNN
- **Model Selection :** Tested all the models to check the RMSE & R-squared.
- **Pickle File** : Selected model as per best RMSE score & R-squared and created pickle file using pickle library.
- **Webpage &Deployment :** Created a web application that takes all the necessary inputs from the user & shows the output. Then deployed project on the streamlit Platform.


## Deployment Link :
https://healthcare-premium-prediction-ml.streamlit.app


## Web Interface :
![image](https://github.com/user-attachments/assets/629498b1-30a6-4232-aef8-1c300e2bb3d0)


## Libraries used :
    1) Pandas
    2) Numpy
    3) Matplotlib, Seaborn, Plotly
    4) Scikit-Learn
    5) Streamlit

## Technical Aspects :
    1) Python 
    2) Front-end : Streamlit 
    3) Back-end : Streamlit
    4) Deployment : Streamlit
