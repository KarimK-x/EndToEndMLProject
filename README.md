# Machine Learning Project

This project was developed as part of a machine learning session to provide a structured, hands-on approach to Chapter 2 of *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow* by Aurélien Géron.

## Project Overview

The dataset used in this project is `housing.csv`, which contains real estate data. The goal is to analyze the data, clean it, and build a predictive model.

## Workflow and Content
1. **EDA**
    - Getting Familiar With The Data
    - Creating Test Set, Never Looking at It Again
    - In-Depth Visualization
    - Feature Engineering
2. **Cleaning Data**
3. **Feature Scaling and Transformation**
    - Custom Transformers
4. **Transformation Pipelines**
    - Pipeline Class
    - Recap on Full Preprocssing Pipeline
5. **Selecting and Training a Model**
    - Linear Regression
    - Decision Trees
    - Random Forests
    - Using Cross Validation
6. **Fine Tuning: Intro**
7. **Test Set Evaluation**

## Requirements

Ensure you have the following dependencies installed:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

Alternatively, if using Conda:

```bash
conda create --name ml_project python=3.10 numpy pandas matplotlib scikit-learn jupyter
conda activate ml_project
```

## Usage

Run the Jupyter Notebook using the following command:

```bash
jupyter notebook main.ipynb
```
