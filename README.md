# CFB_Drive_Predictors
Using data from BCfToys.com, analyzing drive data to predict wins, success, and ball movement

# College Football Drive Efficiency Modeling

This project analyzes team performance using drive-level metrics from FBS college football games to estimate Net Points Per Drive (NPD). Using cleaned data sourced from bcftoys.com, the goal is to understand how field position and offensive and defensive efficiency contribute to scoring margins.

## Project Objective

The objective is to build a predictive model for Net Points Per Drive using the following variables:

- Points per offensive drive (OPD)
- Points allowed per defensive drive (DPD)
- Points per drive based on starting field position
  - Long drives (OLD for offense, DLD for defense)
  - Medium drives (OMD for offense, DMD for defense)
  - Short drives (OSD for offense, DSD for defense)

By modeling these variables, we identify which aspects of drive performance best explain a team's net scoring efficiency.

## Approach

Data was cleaned and structured for modeling, including the removal of incomplete rows and non-informative columns. Models were developed using scikit-learn, including both decision tree and random forest regressors. The random forest model was selected for its stronger performance and generalization. Feature importances were computed and visualized to support interpretation.

## Features

- Cleaned and structured drive-level data
- Exploratory analysis and variable evaluation
- Predictive modeling using decision tree and random forest regressors
- Model interpretation through feature importance and tree visualization
