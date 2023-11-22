# Sleep Analysis Project

## Overview

This project involves the analysis of sleep-related data, exploring relationships between various factors and stress levels. It includes data wrangling, visualization, demographic analysis, and model training using Linear Regression and GRU models.

## Dependencies

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `plotly`
- `scikit-learn`
- `tensorflow`

## Data Wrangling

The dataset (`Sleep.csv`) is loaded using pandas, and basic information about the dataset is displayed using methods such as `head()`, `info()`, and `describe()`.

## Data Visualization

Various visualizations are created to explore relationships and patterns in the data. Notable visualizations include:

- Correlation matrix heatmap
- Scatter plots examining the relation between variables and stress level
- Demographic analysis using pie charts and histograms
- Bar charts exploring the relationship between occupation, sleep disorder, BMI category, and blood pressure

## Pair Plot

A pair plot is generated using seaborn to visualize relationships between numerical variables.

## Model Training

Two models are trained:

1. **Linear Regression:**
   - Data is preprocessed using label encoding and standard scaling.
   - The model is built and evaluated using mean squared error, mean absolute error, and R-squared.

2. **GRU (Gated Recurrent Unit) Model:**
   - Data is reshaped and converted to a TensorFlow Dataset for training efficiency.
   - A GRU model is created, trained, and evaluated.

## Model Evaluation

The performance of both models is evaluated using metrics such as mean squared error, mean absolute error, and R-squared. Results are visualized using a bar chart.

## File Structure

