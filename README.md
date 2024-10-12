# Heart Disease Prediction

## Project Overview

This project aims to predict the likelihood of heart disease in patients using a machine learning approach. It utilizes a dataset that contains various health-related features to determine if an individual is at risk for heart disease.

## Dataset

The dataset used in this project is the Heart Disease dataset, which contains various features that are indicative of heart health. Key features in the dataset include:

- Age
- Sex
- Chest pain type
- Fasting blood sugar
- Resting electrocardiographic results
- Maximum heart rate achieved
- Exercise angina
- Oldpeak
- Number of major vessels colored by fluoroscopy
- Thalassemia
- Target variable (presence or absence of heart disease)

## Data Analysis

Data analysis involves several steps:

1. **Exploratory Data Analysis (EDA)**: 
   - Visualizations were created to understand the distribution of features and their correlations.
   - A heatmap was generated to illustrate the correlation between different features in the dataset.
   - Histograms were plotted to visualize the distribution of each feature.

2. **Data Visualization**: 
   - Count plots were created to show the distribution of the target variable (presence or absence of heart disease).

## Data Preprocessing

The preprocessing steps taken in the project include:

- Converting categorical variables into dummy variables for better representation in the machine learning model.
- Scaling continuous features using StandardScaler to normalize the data.

## Model Training

The K-Nearest Neighbors (KNN) algorithm was chosen for this project due to its simplicity and effectiveness for classification tasks. 

- A range of K values (from 1 to 20) was evaluated to find the optimal number of neighbors for the KNN classifier.
- Cross-validation was utilized to ensure the model's robustness and avoid overfitting.

## Results

The model's performance was evaluated based on the accuracy scores obtained for different K values. The optimal K value was identified, providing insights into the predictive capabilities of the model.

## Conclusion

This project demonstrates the application of machine learning techniques in predicting heart disease based on various health parameters. The findings can potentially aid healthcare professionals in making informed decisions regarding patient health and interventions.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
