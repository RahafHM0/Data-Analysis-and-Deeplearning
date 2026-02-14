# Infant Cry Classification using Deep Learning

## Project Overview

This project focuses on the end-to-end pipeline of Audio Data Analysis and classification. The primary goal is to identify and classify the reasons behind infant cries into 5 distinct categories using Deep Learning techniques. By analyzing audio patterns, this model helps in understanding infant needs with high precision.
Classification Categories
The model successfully classifies audio signals into the following categories:
* Belly Pain
* Burping
* Discomfort
* Hungry
* Tired

## Technical Implementation

* Data Preprocessing: Performed extensive cleaning and feature extraction from raw audio files (captured in donateacrycorpus_features.csv).
* Feature Engineering: Managed categorical data conversion using to_categorical for model compatibility.
* Model Training: Developed a Neural Network using TensorFlow/Keras.
* Validation Strategy: Utilized train_test_split to ensure the model generalizes well to unseen data.
* Performance: Achieved a remarkable accuracy of 94%.
  
## Tech Stack
* Language: Python.
* Libraries: Pandas, NumPy, Scikit-learn, TensorFlow, Keras , matplotlib.pyplot.
* Environment: Jupyter Notebook.
