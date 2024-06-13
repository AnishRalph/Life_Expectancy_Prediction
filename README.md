# Life Expectancy Prediction

This project uses machine learning to predict the life expectancy of countries based on various health, economic, and social factors. The dataset is obtained from Kaggle and includes data from multiple countries over several years.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Overview](#project-overview)
- [Results](#results)

## Introduction
The goal of this project is to predict the life expectancy of different countries using various features such as adult mortality, infant deaths, alcohol consumption, GDP, schooling, etc. The project involves data preprocessing, handling missing values, model training, and future predictions using machine learning models.

## Dataset
The dataset used in this project is from Kaggle and can be found [here](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who). It contains the following columns:

- Country
- Year
- Status (Developed/Developing)
- Life expectancy
- Adult Mortality
- Infant deaths
- Alcohol
- Percentage expenditure
- Hepatitis B
- Measles
- BMI
- Under-five deaths
- Polio
- Total expenditure
- Diphtheria
- HIV/AIDS
- GDP
- Population
- Thinness 1-19 years
- Thinness 5-9 years
- Income composition of resources
- Schooling

## Project Overview
1. **Data Preprocessing:** Handling missing values.
2. **Imputation:** Imputing missing values using KNN and Random Forest algorithms.
3. **Model Training:** Training a TensorFlow neural network to predict life expectancy.
4. **Future Predictions:** Predicting life expectancy for the next year for each country.
5. **Visualization:** Plotting actual vs. predicted life expectancy over the years.

## Results
The project evaluates the model using Root Mean Squared Error (RMSE) and plots the actual vs. predicted life expectancy. It also predicts life expectancy for the next year and saves the results to a CSV file (predicted_life_expectancy.csv).

## Acknowledgements

The dataset used in this project is provided by Kaggle and can be found [here](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who).
Thanks to the contributors of the libraries used in this project.
