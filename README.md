# ML Assignment 1

## Overview

This repository contains solutions and implementations for the first machine learning assignment, including linear regression experiments, analysis, and visualizations. Below is a summary of the tasks and findings.

## Questions and Solutions

### 1. **Linear Regression Implementation**
   - **Objective:** Fit a straight line using linear regression with a learning rate of 0.5.
   - **Results:**  
     - Batch Gradient Descent: `1.1948e-06`  
     - Stochastic Gradient Descent: `1.3741e-06`  
     - Mini-Batch Gradient Descent: `1.1998e-06`  
   - **Convergence Criteria:**  
     - Number of iterations: `1000`  
     - Learning rate: `0.5`  

### 2. **Cost Function Analysis**
   - **Advantage of Averaging Cost:**  
     - Better numerical stability.  
     - Scaled cost values for large datasets.  
     - Easier learning rate tuning.

### 3. **Cost Function vs. Iteration Plot**
   - The graph demonstrates:  
     - Rapid initial cost reduction.  
     - Gradual plateauing as convergence nears.

### 4. **Data Visualization and Fitted Line**
   - Scatter plot of the dataset with the fitted regression line.  
   - **Observation:** The regression line closely matches the trend of data points, indicating a good fit.

### 5. **Learning Rate Experimentation**
   - Learning rates tested: `0.005`, `0.5`, `5`.  
   - **Observations:**  
     - `lr = 0.005`: Slow convergence.  
     - `lr = 0.5`: Optimal, stable convergence.  
     - `lr = 5`: Failed to converge due to oscillations.  

### 6. **Gradient Descent Comparisons**
   - Implemented Batch, Stochastic, and Mini-Batch Gradient Descent.  
   - **Observations:**  
     - **Batch Gradient Descent (BGD):** Smooth and steady cost reduction.  
     - **Stochastic Gradient Descent (SGD):** Faster convergence with noisy updates.  
     - **Mini-Batch Gradient Descent (MBGD):** Balanced approach with smoother curves and faster convergence.

## Visualizations
- Cost function vs. iteration graphs.  
- Scatter plots with fitted regression lines for data analysis.