# Calorie Burn Prediction

**Machine Learning & Data Analysis Project**

Developed by Yair Man | High School Final Project (2025–2026)

## Overview

This project explores the relationship between workout characteristics, physical measurements, and the number of calories burned during exercise.

Using Python and machine learning techniques, the project analyzes a fitness dataset, visualizes patterns, processes the data, and experiments with two classification algorithms: **K-Nearest Neighbors (KNN)** and an **Artificial Neural Network (ANN)**.

## Research Question

Can the amount of calories burned during a workout be classified based on a person's characteristics and exercise data?

## Dataset

The project uses the [Gym Members Exercise Dataset](https://www.kaggle.com/datasets/valakhorasani/gym-members-exercise-dataset) from Kaggle.

The original dataset contains **973 records and 15 features**, including age, gender, weight, height, heart rate, workout type, workout duration, and calories burned.

## Technologies Used

- **Python** – Programming language
- **Pandas & NumPy** – Data processing and analysis
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – KNN classification and preprocessing
- **TensorFlow / Keras** – Artificial neural network
- **Google Colab / Jupyter Notebook** – Development environment

## Project Workflow

1. **Exploratory Data Analysis:** Examine the dataset and visualize relationships between variables.
2. **Data Preprocessing:** Handle features, transform categorical data, and investigate outliers.
3. **Feature Engineering:** Prepare the data for machine learning.
4. **KNN Classification:** Train and evaluate K-Nearest Neighbors models.
5. **Model Improvement:** Experiment with preprocessing and model parameters.
6. **Neural Network:** Build and train an ANN using Keras.
7. **Evaluation:** Examine accuracy, confusion matrices, classification reports, and training graphs.

## Machine Learning Models

### K-Nearest Neighbors (KNN)

The KNN model classifies workout records based on similar examples in the training data. The project experiments with different values of K and evaluates classification performance.

### Artificial Neural Network (ANN)

The ANN model uses multiple dense layers and nonlinear activation functions to learn patterns in workout data. The notebook includes model training, evaluation, and visualizations of the learning process.

## Project Structure

```text
calorie-burn-prediction/
├── data/
│   ├── README.md
│   └── gym_members_exercise_tracking.csv
├── notebooks/
│   ├── README.md
│   └── calorie_burn_analysis.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

## How to Run

1. Download or clone this repository.
2. Install the dependencies:

   `pip install -r requirements.txt`

3. Open `notebooks/calorie_burn_analysis.ipynb` in Jupyter Notebook or a compatible notebook environment.
4. Run the notebook with the repository root as the working directory so that the relative path to `data/gym_members_exercise_tracking.csv` is accessible.

## Project Conclusions

The project investigates how workout duration, heart rate, workout type, and other physical characteristics relate to calorie expenditure.

It also demonstrates the use of data preprocessing, visualization, and two machine learning approaches to explore calorie-burn classification.

## Author

**Yair Man**

Developed as a high school final project in Data Science and Machine Learning.
