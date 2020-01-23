# Product Differentiation in the Automobiles Market: An Empirical Analysis

Paper: *Product Differentiation in the Automobiles Market: An Empirical Analysis* (Rasha Ahmed and Mark Stater) <br>
Research Assistant: My Phung

This research project examined the quality vs. fuel-efficiency trade-offs between low-end and high-end car models. I first consolidated a cross-sectional dataset of 10,000+ observations (2005–2014) and 22 variables from 3 sources. I then developed a Double-Log Regression model to estimate the average miles-per-gallon of an automobile model based on its design features and real market price. For feature engineering, I conducted Pearson’s correlation test to detect and reduce multi-collinearity problem; used year-fixed effects to avoid serial correlation.

This notebook provides a replicate of my work as a research assistant at Trinity College. I'll leave out the data cleansing part which I did for a first couple of months and only focus on the EDA and modelling here. 

Summary of findings:

1. **Results:** Final R_squared: **0.7984** | Final MSE: **0.0024**
2. The signs of the coefficients allign with our research, such as follows:
 - The bigger the weight is, the less energy efficient the car would be
 - All else equal, having the label 'Lux' could imply that the car is more energy efficient than average. THis means that luxury cars are produced to overperform non-luxury ones.
3. The model can be improved by solving multicollinearity or adding more meaningful features.

<center><img src="https://github.com/Emmyphung/emmyphung.github.io/blob/master/images/Car_model_corrplot.png"/></center>
