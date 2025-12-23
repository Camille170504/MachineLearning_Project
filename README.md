# MachineLearning_Project

# Fraud Detection

## Project Description

The aim of this project is to detect fraudulent financial transactions using machine learning. Detecting fraud in financial transactions is a major challenge for financial institutions and consumers. With the rise of electronic transactions and the increasing sophistication of fraudsters, it is becoming increasingly difficult to effectively identify fraudulent activity. 

The goal of the project is to develop a machine learning model capable of detecting fraudulent transactions with high accuracy, while limiting false positives in order to preserve the user experience.

## Business Case 
Financial fraud causes significant economic losses and affects user confidence in online payment systems. An effective detection model can reduce these losses while avoiding the unnecessary blocking of legitimate transactions.

## Dataset
The dataset used contains more than 568,000 transactions, each described by 30 numerical variables.
- Explanatory variables: V1 to V28 (anonymised variables), transaction amount and elapsed time
- Target variable: Class
  -> 0: legitimate transaction
  -> 1: fraudulent transaction

Our dataset is clean, with no missing values, and balanced between fraudulent and non-fraudulent transactions.

## Our methodology: 
We divided our project into four stages:
- Analysis of our dataset
- Training and evaluation of different models
- Selection of our model

## Our models: 
We tested the following models: 
- Logistic regression
- KNN
- Decision tree
- XGBoost
- LightGBM

## File organisation: 
- dataset: https://drive.google.com/drive/folders/1jWy0TTkHDhrWvijZ_e9NbIOnjDIRdNKP?usp=sharing
- "descriptive_analysis.ipynb": analysis of our dataset
- "Models_Preprocessing.ipynb": training and evaluation of models
