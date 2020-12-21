# Why it is important (and why you might be missing it)
##### The technique of regression comes in many forms — linear, nonlinear, Poisson, tree-based- but the core idea remains almost the same across the board and can be applied to a wide variety of predictive analytics problems in finance, healthcare, service industry, manufacturing, agriculture, etc.

#### Linear regression is the fundamental technique, which is rooted strongly in the time-tested theory of statistical learning and inference, and powers all the regression-based algorithms used in modern data science pipeline.

#### However, the success of a linear regression model also depends on some fundamental assumptions about the nature of the underlying data that it tries to model. It is, therefore, extremely important to check the quality of your linear regression model, by verifying Linear Regression assumnptions.

#### Often, there is plenty of discussion about regularization, bias-variance trade-off, or scalability (learning and complexity curves) plots. But, is there sufficient discussion around the following plots and lists ?

###### 1.Residuals vs. predicting variables plots
###### 2.Fitted vs. residuals plot
###### 3.Histogram of the normalized residuals
###### 4.Q-Q plot of the normalized residuals
###### 5.Shapiro-Wilk normality test on the residuals
###### 6.Cook’s distance plot of the residuals
###### 7.Variance inflation factor (VIF) of the predicting features

#### In this notebook, I have shown such a standard set of evaluations for a multivariate linear regression problem.I have used  the statsmodels library for regression modeling and statistical tests.
