# Letter Classification with Support Vector Machine (SVM)
This project implements letter classification using Support Vector Machine (SVM) in R. It utilizes two kernel methods: vanilladot (linear) and rbfdot (RBF) to predict letters from the letterdata.csv dataset. The code includes data preprocessing, model training, and evaluation of classification accuracy for each kernel.

## Dataset
The dataset used for this project is `letterdata.csv`, containing labeled letter data for training and testing.

## Steps
- Load and preprocess data
- Split data into training and testing sets
- Train SVM models with different kernels
- Evaluate and compare performance of models

## Requirements
- R
- `kernlab` package in R

## How to Run
1. Make sure you have installed the `kernlab` package in R.
2. Set the correct path to the `letterdata.csv` file.
3. Run the code to see the accuracy of both linear and RBF kernels.
