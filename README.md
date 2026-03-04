Project Overview

This project analyzes medical datasets using machine learning and statistical modeling techniques in R. The objective was to explore how predictive models can assist in healthcare decision-making by identifying patterns in patient data.

The analysis includes:
	•	Decision tree modeling
	•	Ensemble learning methods (Bagging, Boosting, Random Forest)
	•	Regression modeling for medical prediction
	•	Model comparison using train and test datasets

Datasets Used

1. Pima Indians Diabetes Dataset

The dataset contains medical diagnostic information for 768 female Pima Indian patients.

The goal of the analysis is to predict diabetes test outcomes based on predictors such as:
	•	Glucose
	•	Blood pressure
	•	BMI
	•	Age
	•	Insulin level
	•	Skin thickness
	•	Number of pregnancies

  2. Prostate Cancer Dataset

This dataset contains clinical information from 97 men with advanced prostate cancer.

The objective is to predict PSA (Prostate Specific Antigen) levels using medical variables such as:
	•	Cancer volume
	•	Prostate weight
	•	Age
	•	Benign prostatic hyperplasia
	•	Seminal vesicle invasion
	•	Capsular penetration
	•	Gleason score



Methods Used

**Decision Trees**

Used to create interpretable classification models that split the data based on entropy and information gain.

**Bagging**

Bootstrap aggregation improves prediction stability by averaging results from multiple trees.

**Boosting**

Sequentially builds models that focus on correcting previous errors.

**Random Forest
**
Ensemble learning technique combining multiple decision trees to improve predictive accuracy.

**Lasso Regression**

Used for feature selection and regularization in regression modeling.


Model Evaluation

Models were evaluated using a train/test split approach to measure prediction performance.

Key evaluation aspects included:
	•	Predictive accuracy
	•	Model interpretability
	•	Comparison between statistical and tree-based methods

Key Insights
	•	Ensemble methods such as Random Forest and Boosting improved predictive performance compared to single tree models.
	•	Lasso regression helped identify important predictors affecting PSA levels.
	•	Machine learning models can assist clinicians by identifying important patterns in complex medical datasets.
