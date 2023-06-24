Note: Sometimes Jupyter Notebook files do not render on Github, paste the link in nbviewer if you cannot open the .ipynb file.
https://nbviewer.jupyter.org/

------
# Logistic-Regression-Predict-Income

What is the likelihood a person makes over 50K/year? I use a classification algorithm to create a model that predicts income, and improved its performance metrics, such as Area Under the Curve (AUC) and Receiver Operating Characteristic (ROC), using feature engineering.

I use logistic regression, a classification algorithm, to predict income (binary variable) based on age (continuous variable). Older people are more often classified above 50K, so the results of the model can be interpreted as the probability that a person makes over 50K gets closer to 1 as age increases--or as a person ages she is more likely to make over 50K.

In version 2, I used feature engineering to improve the AUC metric from .67 to .81


View analysis on my [website](https://zhaben.github.io/2019/10/15/logistic-regression.html).
