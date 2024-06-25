# Analysis-of-Comment-Toxicity-Using-Deep-Learning-Techniques

## Overview
This Jupyter Notebook contains the analysis for the final project in the DSCI 691 course at Drexel University. It includes comprehensive data preprocessing, exploration, visualization, and modeling stages used to address the project's objectives.

## Dependencies
- Python 3
- Libraries: pandas, numpy, matplotlib, seaborn, nltk, tensorflow, keras, sklearn

## Features
- **Data Cleaning and Preprocessing:** Utilizes NLTK for natural language processing tasks, including tokenization and stopword removal.
- **Exploratory Data Analysis:** Offers visualizations of data distributions and relationships using Matplotlib and Seaborn.
- **Model Development:** Implements various deep learning models including LSTM, GRU, SimpleRNN, and CNN using TensorFlow and Keras.
- **Model Evaluation:** Provides performance metrics such as ROC-AUC scores for model validation.

## Models Included
- Logistic Regression
- LSTM (Long Short-Term Memory networks)
- GRU (Gated Recurrent Units)
- SimpleRNN
- Convolutional Neural Network (CNN)

## Dataset
The dataset includes user-generated comments classified into several toxic categories like toxic, severe_toxic, obscene, threat, insult, and identity_hate. The training set contains 159,571 records and the testing set includes 153,164 records.

## Usage
To run this notebook:
1. Ensure that all dependencies listed above are installed.
2. Download the dataset as instructed in the notebook.
3. Execute the notebook cells sequentially to reproduce the analysis and results.

## Results
The models developed are capable of predicting various forms of toxicity in online comments with significant accuracy. Visualizations and metrics are provided for comprehensive assessment.

