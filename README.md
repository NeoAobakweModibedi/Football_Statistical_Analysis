# Football_Statistical_Analysis

This project aims to predict the score of football matches based on historical match data. The prediction model uses machine learning techniques to forecast the number of goals scored by both the home and away teams. This can be useful for applications like match forecasting or betting systems.

## Table of Contents
1. [Project Description](#project-description)
2. [Installing Packages](#packages)
3. [Data](#data)
4. [Features](#features)
5. [Model Training](#model-training)
6. [Model Evaluation](#model-evaluation)
7. [Predictions](#predictions)
8. [Conclusion](#conclusion)
9. [License](#license)

## Project Description

This project uses historical football match data, including team names, match date, and full-time goals scored by both home and away teams. The main objective is to predict the number of goals scored by the home and away teams in future matches using a machine learning model.

### Approach:
- Data is preprocessed and encoded (categorical variables such as team names are transformed into numeric values).
- The model is trained using a Random Forest Regressor to predict the goals scored by the home and away teams.
- The model can be used to predict the result of a specific match given the teams and the match date.

## Getting Started

To get started with this project, clone the repository and install the required dependencies.

### Prerequisites

- Python 3.x
- Libraries:
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn

You can install the required libraries using:

```bash
pip install -r requirements.txt
