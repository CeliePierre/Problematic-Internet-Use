# Kaggle Competition: Child Mind Institute — Problematic Internet Use

![Competition Badge](https://img.shields.io/badge/Kaggle-Competition-orange)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-gray.svg?logo=jupyter)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=fff)](#)
[![NumPy](https://img.shields.io/badge/NumPy-4DABCF?logo=numpy&logoColor=fff)](#)
[![Matplotlib](https://custom-icon-badges.demolab.com/badge/Matplotlib-71D291?logo=matplotlib&logoColor=fff)](#)
[![Seaborn](https://img.shields.io/badge/Seaborn-30B5B5?logo=seaborn&logoColor=fff)](#)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikit-learn&logoColor=fff)](#)


## Overview

This repository contains the code and documentation for our participation in [Child Mind Institute — Problematic Internet Use](https://www.kaggle.com/competitions/child-mind-institute-problematic-internet-use):

> <i>"The goal of this competition is to develop a predictive model that analyzes children's physical activity and fitness data to identify early signs of problematic internet use. Identifying these patterns can help trigger interventions to encourage healthier digital habits."</i> - Kaggle

## Introduction

This project aims to develop a predictive model to identify problematic internet use among children and adolescents by analyzing their physical activity and fitness data. The dataset includes various metrics related to physical activity, fitness levels, and internet use scores. By leveraging these indicators, we hope to identify early signs of unhealthy internet habits, enabling timely interventions to promote healthier digital behaviors and support children's mental health.

## Data Loading

The data is loaded from CSV and Parquet files, which include training and testing datasets. The project processes these files to extract relevant features and prepare the data for analysis.

## Data Visualization

Data visualization techniques are employed to understand the distribution of the target variable (Severity Impairment Index, SII) and to identify missing values in the dataset. Visualizations help in assessing the overall data quality and understanding the relationships between different features.

## Data Preprocessing

The preprocessing steps include dropping unnecessary columns, applying one-hot encoding to categorical variables, and aligning the training and testing datasets. Missing values are handled appropriately to ensure the integrity of the data before model training.

## Model Development

Two models are developed in this project: a Random Forest model and a Logistic Regression model. The Random Forest model is used to predict the SII based on the processed data, and it is evaluated for accuracy and performance. The Logistic Regression model is implemented for comparison, allowing for an assessment of different modeling approaches.

## Results

The performance of both models is evaluated using metrics such as accuracy, classification reports, and confusion matrices. The results provide insights into the effectiveness of the models in predicting problematic internet use.

## Conclusion

This project demonstrates the potential of using physical activity and fitness data as proxies for predicting problematic internet use among children and adolescents. The findings can inform interventions aimed at promoting healthier digital habits and supporting mental health in young individuals.

### Final Kaggle Competition Results

![Final Results](images/fig7.png)
![Kaggle Competitor](images/kaggle-competitor.svg)

## Contributors

- Anusha Ghimire: [![GitHub Profile](https://img.shields.io/badge/GitHub-anu--sha19-181717?logo=github&logoColor=white)](https://github.com/anu-sha19)
- Célie Pierre: [![GitHub Profile](https://img.shields.io/badge/GitHub-CeliePierre-181717?logo=github&logoColor=white)](https://github.com/CeliePierre)

## Citation

Adam Santorelli, Arianna Zuanazzi, Michael Leyden, Logan Lawler, Maggie Devkin, Yuki Kotani, and Gregory Kiar. Child Mind Institute — Problematic Internet Use. https://kaggle.com/competitions/child-mind-institute-problematic-internet-use, 2024. Kaggle.

## Figures

![Figure 1](images/fig1.png)

*Figure 1: Distribution of SII*

![Figure 2](images/fig2.png)

*Figure 2: Classification report*

![Figure 3](images/fig3.png)

*Figure 3: Random Forest with adjusted parameters*

![Figure 4](images/fig4.png)

*Figure 4: Feature importance*

![Figure 5](images/fig5.png)

*Figure 5: ROC curve*

![Figure 6](images/fig6.png)

*Figure 6: Confusion matrix*
