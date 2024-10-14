# Predictive Modeling for Agriculture

This project focuses on developing a predictive model for agricultural purposes, specifically to determine the most suitable crop based on soil conditions.

## Dataset

The dataset used in this project is `soil_measures.csv`, which contains the following features:
- N: Nitrogen content in the soil
- P: Phosphorus content in the soil
- K: Potassium content in the soil
- ph: pH level of the soil
- crop: The type of crop suitable for the given soil conditions

## Project Structure

The main analysis and modeling are conducted in the `notebook.ipynb` file. This Jupyter notebook contains the following key steps:

1. Data Loading and Exploration
2. Data Preprocessing
3. Feature Engineering (if applicable)
4. Model Selection and Training
5. Model Evaluation
6. Predictions and Insights

## Requirements

To run this project, you'll need:
- Python 3.x
- Jupyter Notebook
- Required libraries (list to be updated based on the specific libraries used in the notebook)

## How to Use

1. Clone this repository
2. Install the required dependencies
3. Open and run the `notebook.ipynb` file in Jupyter Notebook

## Results

Our analysis revealed that the most predictive feature for determining suitable crops based on soil conditions is:

- Best predictive feature: K
- Best score: 0.3227


This feature demonstrated that the Potassium content in the soil has the highest individual predictive power among all soil measures in the dataset. This insight can be valuable for farmers and agricultural experts in making quick assessments of crop suitability based on a single soil measurement.
