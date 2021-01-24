# The-Polar-Bears

This github contains all the notebooks that were developed for the sea-ice challenge during the Hackathon 2021.
- Feature_Engineering_and_analysis.ipynb : explore parameter space (correlation, time-dependence)
- Linear_regression.ipynb : performs a series of linear regression models on the data
- boosting.ipynb : training and predictions from a XGBoost model
- classification.ipynb : apply classification algorithm on velocity magnitude. If two steps models are used, where in the first step valocities are classified into categories based on their intensity and then predicted and in the second step some other algorithms (i.e XGBoost, random forst etc.) are apllied where category is taken as an extra feature, this classification can be the first step.
- NeuralNetwork : application and prediction for a series of Neural Network models
