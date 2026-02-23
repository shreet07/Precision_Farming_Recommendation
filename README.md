# YieldVision: Nutrient-to-Harvest Forecaster
YieldVision system leverages Machine Learning to optimize crop selection and water management. By integrating NPK soil analysis and climate data, it recommends ideal crops via Random Forest models, Naive Bayes and K-Means Clustering Techniques. A unique irrigation calculator converts rainfall deficits into exact liter requirements, bridging the gap between AI and field practice.

# YieldVision: Nutrient-to-Harvest Forecaster

# 🌾 Project Overview
This project leverages Machine Learning to help farmers optimize agricultural productivity. By analyzing soil characteristics and environmental factors, the system recommends the most suitable crop to grow in a specific location and calculates irrigation needs to ensure optimal growth. The goal is to reduce crop failure and maximize yield by making data-driven decisions.

## 📊 Dataset Features
The model is trained on an agricultural dataset containing:
* Nitrogen (N): Ratio of Nitrogen content in soil.
* Phosphorus (P): Ratio of Phosphorous content in soil.
* Potassium (K): Ratio of Potassium content in soil.
* Temperature: Temperature in degree Celsius.
* Humidity: Relative humidity in %.
* pH: pH value of the soil.
* Rainfall: Rainfall in mm.
Label (Target): The recommended crop (22 unique crops including Rice, Maize, Coffee, etc.).
Source: Kaggle - Crop Recommendation Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset).

## 🚀 Key Features
1.  Exploratory Data Analysis (EDA): Visualizations of nutrient distribution and environmental impacts on 22 different crop types.
2.  Predictive Modeling: Implementation of multiple ML algorithms including:
    * Random Forest
    * Decision Trees
    * K-Nearest Neighbors (KNN)
    * Logistic Regression
    * Naive Bayes
3.  Irrigation Calculator: A custom tool that calculates the water deficit based on current rainfall and the optimal needs of the selected crop, providing exact irrigation requirements in liters based on land area.

## 🛠️ Technology Stack
* Language: Python
* Libraries: Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib, Plotly
* Platform: Jupyter Notebook

## 📈 Results
The models were evaluated based on accuracy, precision, and recall. The **Random Forest** and **Naive Bayes** models typically demonstrate high performance in recommending crops accurately based on the soil-climate profile.
