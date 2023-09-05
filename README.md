# Titanic Survival Prediction

![Python](https://img.shields.io/badge/Python-3.9.7-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit%20Learn-0.24.2-green)
![Pandas](https://img.shields.io/badge/Pandas-1.3.3-yellow)

## Overview

This repository contains the code and analysis for the Titanic Survival Prediction project. The project aims to predict the survival outcome of passengers aboard the RMS Titanic using machine learning techniques. We explore the dataset, preprocess the data, engineer relevant features, and train several machine learning models for prediction.

## Getting Started

To run this project on your local machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/gabriel-nds/Titanic_ML_from_Disaster.git

2. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate    # On Windows, use "venv\Scripts\activate"

3. Install dependencies:

   ```bash
   pip install -r requirements.txt

4. Run the Jupyter Notebook:

   ```bash
   jupyter notebook Titanic_Survival_Prediction.ipynb

5. Explore the project:

Open the Jupyter Notebook and follow the step-by-step analysis, preprocessing, modeling, and evaluation process.

## Model Performance on Kaggle Competition

Before we dive into the notebook's structure, let's celebrate our accomplishments. In the Digit Recognizer Kaggle competition, our model has demonstrated exceptional performance, ranking in the top 5% of participants: 


![7778B558-876B-43C2-A686-7C6CE5CD4C26](https://github.com/gabriel-nds/Titanic_ML_from_Disaster/assets/118403829/e55bd301-cc05-4b2b-82ed-446abfad8c95)

On Kaggle we got a score of **79.66%**!

![FE56FE37-E971-4FAF-A6BF-286D43218472_1_201_a](https://github.com/gabriel-nds/Titanic_ML_from_Disaster/assets/118403829/f649d771-4035-43cb-ad37-2a60a7b4e35d)


This is a testament to the effectiveness of the techniques and strategies we'll explore in this notebook!

## Project Structure

The project is structured into the following sections:

- **Import Necessary Libraries**: Importing Python libraries and modules for data manipulation, visualization, and modeling.

- **Loading the Training Dataset**: Loading the Titanic training dataset.

- **Exploring Feature-Target Correlation**: Exploring the correlation between features and the target variable (survival).

- **Splitting the Dataset**: Splitting the dataset into training and testing subsets.

- **Preprocessing the Train Data**: Handling missing values, dropping unnecessary columns, and feature engineering.

- **Encoding and Standardization**: Encoding categorical features and standardizing numerical features.

- **Training the Data**: Training various machine learning models and evaluating their performance.

- **Preprocessing the Test Data**: Preprocessing the test dataset for predictions.

- **Making Predictions**: Using the trained model to make survival predictions.

- **Creating File to Submit on Kaggle**: Formatting predictions for submission to Kaggle.

- **Model Evaluation**: Evaluating the model's performance with metrics such as accuracy, precision, recall, and F1-score.

## Kaggle Submission

Our model's performance has been evaluated and submitted to the Titanic: Machine Learning from Disaster Kaggle competition. It achieved impressive results with [mention your Kaggle rank and score here, if applicable].

## Acknowledgments

We would like to thank the Kaggle community and Titanic dataset providers for making this project possible.

Feel free to explore the project, experiment with different models, and contribute to its improvement.

Happy coding!

