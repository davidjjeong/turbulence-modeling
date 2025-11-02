# Turbulence Data Modeling for Particle Clustering Distribution Analysis

This case study investigates the effect of fluid turbulence, gravitational acceleration, and particle inertia, quantified by Reynolds, Froude, and Stokes numbers, on the summary statistics (mean, standard deviation, skewness, kurtosis) of particle clustering distribution in an idealized turbulence.

We present two models, one for inference and the other for prediction:

- A multiple linear regression model with box-cox transformation of the response variables and appropriate variable transformation of predictors, with significant interaction effects chosen by a shrinkage method (lasso)
- A predictive random forest model with optimal number of decision trees chosen systematically by 5-fold cross validation

Refer to the Rmd file for more details.
