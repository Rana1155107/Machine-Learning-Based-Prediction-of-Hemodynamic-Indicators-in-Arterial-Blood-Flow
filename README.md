# Machine Learning–Based Prediction of Hemodynamic Indicators in Cardiovascular Flows

## Overview
This project develops a machine learning framework to predict key hemodynamic indicators in arterial blood flow using fluid dynamics–inspired parameters. The objective is to create fast surrogate models for cardiovascular flow analysis that can complement or reduce reliance on computationally expensive CFD simulations.

## Problem Description
Hemodynamic quantities such as wall shear stress and pressure drop play a critical role in cardiovascular health, as abnormal flow patterns are closely linked to diseases including atherosclerosis, stenosis, and aneurysm formation. While CFD provides accurate insights into blood flow behavior, patient-specific simulations are often computationally demanding. This project explores machine learning approaches to model these complex flow characteristics efficiently.

## Dataset
A synthetic CFD-inspired dataset is generated to represent steady or pulsatile blood flow through simplified arterial geometries. Input features include flow parameters (e.g., Reynolds number, Womersley number), geometric descriptors (e.g., vessel diameter, stenosis severity), and blood properties. The target variables consist of clinically relevant hemodynamic indicators such as time-averaged wall shear stress and pressure drop.

## Methodology
The project follows a structured machine learning pipeline:
- Dataset generation and preprocessing
- Exploratory data analysis with physiological interpretation
- Feature scaling and train–test splitting
- Baseline and advanced regression model training
- Model comparison using standard performance metrics
- Interpretation of results through feature importance analysis

Several regression models, including linear regression, ensemble-based methods, and neural networks, are evaluated to capture nonlinear cardiovascular flow behavior.

## Results
The results demonstrate that nonlinear machine learning models significantly outperform linear baselines in predicting hemodynamic quantities. Feature importance analysis highlights the dominant influence of geometric and flow parameters, such as stenosis severity and flow regime, on cardiovascular hemodynamics.

## Applications
Potential applications of the proposed framework include:
- Rapid assessment of arterial flow conditions
- Parametric studies of stenosis severity
- Reduced-order modeling for cardiovascular simulations
- Educational and research-oriented cardiovascular fluid dynamics analysis

## Tools and Libraries
- Python
- NumPy, Pandas
- Scikit-learn
- Matplotlib

## Notes
This project is intended for research and educational purposes and demonstrates the integration of fluid dynamics principles with machine learning techniques for cardiovascular flow analysis.
