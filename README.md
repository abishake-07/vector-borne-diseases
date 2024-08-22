# Vector Borne Diseases (VBD)

## Overview

This repository contains the code and resources for a project aimed at predicting and understanding the spread of Vector Borne Diseases (VBD) using machine learning models. The project focuses on leveraging climate-based and symptom-based data to build a robust model for early detection and prevention of VBD.

## Table of Contents

- [Introduction](#introduction)
- [Objective](#objective)
- [Data Sources](#data-sources)
- [Methodology](#methodology)
- [Installation](#installation)


## Introduction

Vector Borne Diseases are illnesses transmitted by vectors such as mosquitoes, ticks, and fleas. The prevalence and spread of these diseases are closely linked to various environmental factors, including climate conditions. This project aims to employ machine learning techniques to analyze climate-based data along with symptom-based information to create a predictive model for the occurrence and spread of VBD.

This research aims to develop and understand machine learning models for predicting vector-borne disease
prognosis based on patient symptoms. To achieve this, we will leverage a combination of machine learning
algorithms, data preprocessing techniques, interpretability tools, and adversarial robustness evaluation.
Our approach is guided by a strong emphasis on transparency, reproducibility, and practical application in
healthcare settings.

## Objective

The primary objectives of this project include:

1. **Early Detection:** Develop a machine learning model to predict the likelihood of VBD outbreaks based on climate data.
2. **Symptom Analysis:** Incorporate symptom-based data to enhance the accuracy of the prediction model.
3. **Unveiling Model Vulnerability to Adversarial Attacks:**To investigate the susceptibility of the selected machine learning models to adversarial
attacks and assess their generalization ability under such conditions, a growing concern in deep
learning applications.
4. **Illuminating Model Insights through Interpretability**: To interpret the decision-making process of the selected machine learning models and
identify the most influential symptoms for disease predictions, addressing the need for transparency
and explainability in healthcare AI.


## Data Sources

The project utilizes diverse datasets, including:

- **Symptom-based Data:** Patient records and symptom data to identify patterns related to VBD. The link to the data is here: https://www.kaggle.com/datasets/richardbernat/vector-borne-disease-prediction?resource=download

## Methodology

The project follows these key steps:

1. **Data Collection:** Gather relevant climate and symptom-based data from reliable sources.
2. **Data Preprocessing:** Clean and preprocess the data to handle missing values and ensure consistency.
3. **Feature Engineering:** Extract meaningful features from the data to improve model performance.
4. **Machine Learning Model Development:** Employ machine learning algorithms to build a predictive model for VBD.
5. **Model Evaluation and Comparison:** Validate the model using historical data and assess its performance.

6. **Model Interpretability with SHAP and LIME**: understand the relationship between symptoms and disease predictions.

7. **Adversarial Robustness Evaluation**: We will choose the best performing models from previous steps and subject them to adversarial attacks to
assess their robustness.



## Installation

To set up the project locally, follow these steps:

```bash
git clone https://github.com/your-username/vbd-project.git
cd vector-borne-diseases
pip install -r requirements.txt
```



