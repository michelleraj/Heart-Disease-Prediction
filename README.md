# Heart-Disease-Prediction
## Introduction

This project aims to predict heart disease using patient health records from the Kaggle Heart Disease dataset. By applying various machine learning algorithms, we aim to identify key risk factors and develop an accurate predictive model to aid in early diagnosis and intervention.
## Data Processing
The dataset was first inspected for missing values, duplicates, and inconsistencies. Categorical variables were encoded using one-hot encoding, and numerical features were standardized to ensure uniformity. These steps helped prepare the data for effective modeling.
## Prevalence Analysis
Exploratory Data Analysis (EDA) revealed a heart disease prevalence of 25% in females and 65% in males. These insights guided the feature selection and model-tuning processes, highlighting the importance of gender-specific risk factors.
## Feature Engineering
Feature engineering included imputing missing values, encoding categorical variables, and normalizing numerical features. These steps enhanced the dataset's quality and the model's predictive accuracy, leading to an accuracy of 82%.
## Model Training and Evaluation
Several machine learning algorithms were tested, including Logistic Regression, Random Forest, and Support Vector Machine (SVM). Model performance was evaluated using accuracy, precision, recall, and F1-score, with the Random Forest model achieving the highest accuracy of 82%.
## Results
The best-performing model, Random Forest, achieved an accuracy of 82% in detecting heart disease. Confusion matrix and ROC curve analyses further validated the model's performance, confirming its suitability for predictive tasks in a clinical setting.

## Plots from Exploratory Data Analysis (EDA) 
### For Detailed Analysis [Click Here](Heart_Failure_Prediction.ipynb.ipynb.ipynb)


## 1. Correlation Matrix - the relationship between variables in the data set

<img width="622" alt="Screen Shot 2023-05-20 at 5 21 32 PM" src="https://github.com/michelleraj/Heart-Disease-Prediction-/assets/57809798/00ce54f6-b631-4f06-8a72-7d14bca35711">

## 2. Exploratory Data Analysis Heart Disease vs Gender
Heart Disease is most commonly found in Males relative to females
Females that have heart disease are less than the ones who don't have heart disease

<img width="1306" alt="Screen Shot 2023-05-20 at 5 34 01 PM" src="https://github.com/michelleraj/Heart-Disease-Prediction-/assets/57809798/b77b82de-fe47-48ee-8014-3fe211d8e95f">

## 3. Exploratory Data Analysis for different ECGs compared to heart failure


<img width="1292" alt="Screen Shot 2023-05-20 at 5 34 11 PM" src="https://github.com/michelleraj/Heart-Disease-Prediction-/assets/57809798/078f4341-e5b7-47a3-94ba-da64301813b3">


# BOX Plots

Box plots visually show the distribution of numerical data and skewness by displaying the data quartiles (or percentiles) and averages

box plot consists of a rectangular box that represents the interquartile range (IQR), spanning from the first quartile to the third quartile. Inside the box, a line marks the median, while extending from the box are "whiskers" that indicate the positions of the minimum and maximum values.

Box plots are a useful way to visualize differences among different samples or groups. They manage to provide a lot of statistical information, including — medians, ranges, and outliers

Compare the respective medians of each box plot. If the median line of a box plot lies outside of the box of a comparison box plot, then there is likely to be a difference between the two groups.

Compare the interquartile ranges (that is, the box lengths), to examine how the data is dispersed between each sample. The longer the box the more dispersed the data. The smaller the less dispersed the data.


## Box plot of HeartDisease vs Cholesterol
<img width="1300" alt="Screen Shot 2023-05-20 at 5 34 31 PM" src="https://github.com/michelleraj/Heart-Disease-Prediction-/assets/57809798/11ea84ea-ddb3-4dcb-b1b7-f871242be35f">

## Box plot of HeartDisease vs MAXHR

<img width="1300" alt="Screen Shot 2023-05-20 at 5 34 42 PM" src="https://github.com/michelleraj/Heart-Disease-Prediction-/assets/57809798/e148121d-365e-41ef-abf0-bae2fa56582c">

## Box plot of HeartDisease vs RestingBP

<img width="972" alt="Screen Shot 2023-07-21 at 4 13 34 PM" src="https://github.com/michelleraj/Heart-Disease-Prediction-/assets/57809798/df76ff49-0c1a-43f7-b403-b4950055bf17">



