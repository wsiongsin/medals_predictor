# Medals Predictor

## Project Overview

Welcome to the Olympic Medal Prediction project! This beginner project employs Machine Learning (ML) to predict the number of medals a country might win in the Olympic Games. Leveraging historical data, the model takes into account previous medal counts, the number of athletes, and their age to make its predictions. The primary ML approach utilized here is Linear Regression, facilitated by the powerful Python libraries: Pandas for data manipulation, Seaborn for data visualization, and Scikit-learn (sklearn) for implementing the Linear Regression model.

## Key Features

**Data Exploration:** Understand the underlying patterns and correlations within the Olympic data using explorative data analysis.

**Data Visualization:** Employ Seaborn to visualize data distributions, correlations, and patterns that will inform model development.

**Predictive Modeling:** Using Sklearn, develop a Linear Regression model to predict the future medal counts based on input variables: previous medal counts, number of athletes, and average age of athletes.

**Model Evaluation:** Utilize various model evaluation metrics to understand the model's performance and predictive accuracy.

## Getting Started

#### Prerequisite

Python (>= 3.6)
Pandas
Seaborn
Scikit-learn
Matplotlib (optional, for additional plotting capabilities)
You can install the prerequisites using pip:

```shell
pip install pandas seaborn scikit-learn matplotlib
```

## Dataset

Ensure that your dataset is structured in a manner that facilitates effective ML modeling, with features like previous medal count, number of athletes, and their ages cleanly organized into columns. This project assumes a CSV file format, but you can adjust the data loading functions for different formats.

## Files Structure

data_processing.ipynb: Entry point for the project. Contains code to train and evaluate the model and functions for creating various visualizations of the data.
teams.csv: Contains all data from previous Olympics

## Usage

Data Preparation: Place your dataset in the correct directory.
Visualization: Use data_processing.ipynb to generate and explore various visualizations of the data

## Acknowledgements

Special thanks to the Olympic Data repositories for providing publicly accessible datasets.
Everyone who contributes to the development of the utilized libraries: Pandas, Seaborn, and Scikit-learn.
