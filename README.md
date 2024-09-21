# Diamond Price Prediction

This repository contains a predictive analytics project that aims to predict diamond prices using machine learning models.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Preparation](#data-preparation)
- [Modeling](#modeling)
- [Evaluation](#evaluation)

## Introduction
This project focuses on predicting the price of diamonds based on various features such as carat, table, dimension, cut, color, and clarity. The goal is to build a model that accurately predicts the price.

## Dataset
The dataset used in this project is from [Kaggle](https://www.kaggle.com/datasets/shivam2503/diamonds), containing the following features:
- **price**: price in US dollars (\$326--\$18,823)
- **carat**: weight of the diamond (0.2--5.01)
- **cut**: quality of the cut (Fair, Good, Very Good, Premium, Ideal)
- **color**: diamond colour, from J (worst) to D (best)
- **clarity**: a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
- **x**: length in mm (0--10.74)
- **y**: width in mm (0--58.9)
- **z**: depth in mm (0--31.8)
- **depth**: total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
- **table**: width of top of diamond relative to widest point (43--95)

## Exploratory Data Analysis
Exploratory Data Analysis (EDA) is conducted to gain insights into the dataset. During this phase:
- Handling missing data
- Outliers are detected and removed
- Relationships between features and target variables are analyzed

## Data Preparation
Data preparation steps include:
- Encoding categorical features
- Dimensionality reduction

## Modeling
In this section, different machine learning models are applied to predict diamond prices:
1. K-Nearest Neighbors
2. Random Forest
3. AdaBoost

## Evaluation
Model evaluation metrics:
- Mean Squared Error (MSE)