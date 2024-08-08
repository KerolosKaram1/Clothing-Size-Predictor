# Clothing Size Prediction

This repository contains a machine learning project for predicting clothing sizes based on physical attributes such as weight, height, and age. The project utilizes data analysis and various machine learning models, including Linear Regression and Voting Regressor, to provide accurate size recommendations.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Data Description](#data-description)
3. [Features](#features)
4. [Setup and Installation](#setup-and-installation)
5. [Usage](#usage)
6. [Results](#results)
7. [Model Evaluation](#model-evaluation)


## Project Overview

This project aims to predict the clothing size of individuals based on their physical characteristics. The dataset used in this project includes features like weight, height, and age, and the target variable is the clothing size.

## Data Description

The dataset `final_test.csv` includes the following columns:

- `weight`: Weight of the individual in kilograms
- `height`: Height of the individual in centimeters
- `age`: Age of the individual in years
- `size`: Clothing size (target variable)

## Features

The following features were engineered for model training:

- `bmi`: Body Mass Index
- `neck_circumference`: Estimated neck circumference
- `waist_circumference`: Estimated waist circumference
- `hip_circumference`: Estimated hip circumference
- `whr`: Waist-to-Hip Ratio
- `shoulder_circumference`: Estimated shoulder circumference
- `shoulder_to_waist_ratio`: Shoulder-to-Waist Ratio
- `torso_length`: Estimated torso length
- `leg_length`: Estimated leg length

## Setup and Installation

To get started with this project, clone this repository and install the necessary dependencies:

```bash
git clone https://github.com/your-username/clothing-size-prediction.git
cd clothing-size-prediction
pip install -r requirements.txt
```

## Usage

1. **Data Preprocessing**: Clean and preprocess the data, including handling missing values, outliers, and feature engineering.
2. **Model Training**: Train Linear Regression and Voting Regressor models on the preprocessed data.
3. **Prediction**: Use the trained model to predict clothing sizes based on new input data.

To run the analysis and model training, use:

```bash
python main.py
```

You can also use the functions in `predict_size.py` to predict clothing size based on user inputs.

## Results

The project includes results of model performance evaluations, including Mean Squared Error (MSE) and R² scores. The models were evaluated using cross-validation and performance metrics to ensure reliability.

## Model Evaluation

The project employs the following evaluation metrics:

- **Mean Squared Error (MSE)**
- **R² Score**

Additionally, the Voting Regressor model was fine-tuned using Grid Search for optimal performance.

