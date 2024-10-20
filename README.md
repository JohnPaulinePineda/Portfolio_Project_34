# [Supervised Learning : Exploring Penalized Models for Handling High-Dimensional Survival Data](https://johnpaulinepineda.github.io/Portfolio_Project_34/)

[![](https://img.shields.io/badge/R-black?logo=R)](#) [![](https://img.shields.io/badge/RStudio-black?logo=RStudio)](#)

This [project](https://johnpaulinepineda.github.io/Portfolio_Project_34/) explores different regularization methods for minimizing model complexity by promoting coefficient sparsity in high-dimensional survival data. Using a Cox Proportional Hazards Regression model structure, penalty functions applied during the coefficient estimation process included the Least Absolute Shrinkage and Selection Operator, Elastic Net, Minimax Concave Penalty, Smoothly Clipped Absolute Deviation and Fused Least Absolute Shrinkage and Selection Operator. The predictive performance for each algorithm was evaluated using the time-dependent area under the receiver operating characteristics curve (AUROC) metric through both internal bootstrap and external validation methods. Model calibration was similarly assessed by plotting the predicted probabilities from the model versus the actual survival probabilities. The differences in survival time for different risk groups determined from the calibration analyses were additionally examined using the  Kaplan-Meier survival curves.

<img src="images/Project34_Summary.png?raw=true"/>
