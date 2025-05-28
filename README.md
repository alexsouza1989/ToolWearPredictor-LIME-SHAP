# ToolWearPredictor-LIME-SHAP

A Python project for predicting tool wear in dry machining of Ti6Al4V using machine learning models with LIME and SHAP explainability.

---

## Table of Contents

- [Overview](#overview)  
- [Data Source](#data-source)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Results & Explainability](#results--explainability)  
- [License](#license)  

---

## Overview

This repository provides code to load experimental cutting data, train classification models (Random Forest, SVM, Logistic Regression, LightGBM), and interpret their predictions using:

- **LIME** (Local Interpretable Model-agnostic Explanations)  
- **SHAP** (SHapley Additive exPlanations)  

Its goal is to give both high predictive accuracy and transparent, actionable insights for process engineers.

---

## Data Source

All experimental data were originally published by Klippel *et al.* in:

> Klippel, H., Süssmaier, S., Zhang, N., Kuffa, M., Wegener, K. (2024).  
> Large-scale investigation of dry orthogonal cutting experiments Ti6Al4V and CK45.  
> *The International Journal of Advanced Manufacturing Technology*, 135, 2871–2908.  
> https://doi.org/10.1007/s00170-024-14597-2

The raw Excel dataset (`data/raw/ti6al4v_cutting.xlsx`) in this repo was extracted from their published supplementary data.

---


