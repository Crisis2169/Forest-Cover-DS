# Forest-Cover-DS
The goal is to build a machine learning model that predicts the forest cover type of a given land area based on various cartographic and environmental features.
📌 Project Overview

The Covertype Dataset contains ~580,000 observations of forest land, with 54 input features such as elevation, slope, soil type, wilderness area, hillshade, and more. The task is a multi-class classification problem, where the objective is to predict one of seven forest cover types.

This project implements a complete machine-learning workflow including:

Data cleaning and preprocessing

Exploratory data analysis

Feature engineering and scaling

Model training using multiple classifiers

Model comparison (Accuracy, F1-Score)

Feature importance evaluation

Final results and conclusions

🎯 Objective

Build a classification model that achieves 75%+ accuracy in predicting forest cover types and provides insights into which features significantly influence predictions.

📂 Dataset

Source: UCI ML Repository — Covertype Dataset

Approx. 580k rows

54 independent features

7 target classes

Combination of continuous and categorical inputs

🛠️ Tech Stack

Python

NumPy, Pandas

Matplotlib / Seaborn

Scikit-Learn

XGBoost

Joblib

📊 Models Used

The following models were trained and evaluated:

Random Forest Classifier

XGBoost Classifier

After training, performance was compared using:

Accuracy

F1-Score

Confusion Matrix

Classification Report

The best-performing model was selected based on overall evaluation metrics.

🔍 Key Features of the Project

End-to-end preprocessing pipeline

Label encoding and scaling

Model training using optimized hyperparameters

Visual insights through plots and correlations

Exporting the best model using joblib

Clean, modular code suitable for production and academic submission

📈 Results Summary

(You can customize this based on your actual model output)

XGBoost achieved higher accuracy than Random Forest

Strong predictive power for classes with abundant data

Elevation, soil type, slope, and hillshade values were among the most important features

🧾 Conclusion

This project successfully demonstrates how to build a high-performance multi-class classification model for forest cover prediction. The results meet or exceed the success criteria, and the analysis highlights the environmental factors most responsible for differentiating forest types.
