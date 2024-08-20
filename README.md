# Crop-Yield-Prediction-and-Analysis
## Project Overview
This project aims to predict the type of crop best suited for cultivation based on soil metrics such as Nitrogen (N), Phosphorus (P), Potassium (K), and pH levels. The project uses Logistic Regression, a popular machine learning algorithm, to evaluate the predictive power of these soil metrics in determining the optimal crop.

## Dataset
The dataset includes the following features:

N: Nitrogen content in the soil
P: Phosphorus content in the soil
K: Potassium content in the soil
pH: Acidity or alkalinity of the soil
Crop: The type of crop cultivated
## Methodology
Data Preprocessing: The data was cleaned and split into training and testing sets.
Logistic Regression Modeling: Logistic Regression was applied to each soil metric individually to assess its predictive power.
F1-scores were calculated to measure the model's performance for each feature.
Potassium (K) was found to be the most predictive feature.
## Visualization:
Pair Plot to visualize relationships between soil metrics and crops.
Box Plots to show the distribution of each soil metric across different crops.
Correlation Heatmap to analyze the correlation between soil metrics.
Confusion Matrix to evaluate the model's predictions.
## Key Results
F1-Score: Potassium (K) had the highest F1-score, making it the best predictor for crop type in this dataset.
Confusion Matrix: The confusion matrix provided insight into the model's performance, showing which crops were predicted accurately and where the model struggled.
## Conclusion
This project demonstrates the effectiveness of using Logistic Regression for crop prediction based on soil metrics. The analysis highlights Potassium as a key soil metric in determining the appropriate crop type, making it a valuable tool for farmers and agronomists.
## How to Run
Clone the repository.
Install required dependencies using pip install -r requirements.txt.
Run the Jupyter Notebook or Python script to reproduce the analysis and visualizations.
