# regression-analysis
Project III: Regression Analysis on Seoul Bike Sharing Demand DataSet

Introduction:
The "Seoul Bike Sharing Demand DataSet" is sourced from the official website of the South Korean government and contains data related to bicycle sharing rentals. The original dataset comprises 13 independent variables along with one dependent variable. However, due to multicollinearity and the inclusion of a date variable, three variables have been excluded, leaving us with 10 independent variables, including two dummy variables, and one dependent variable. Modifications were made to enhance the data's statistical properties, such as removing entries with zeros and performing a logarithmic transformation on the dependent variable. The resulting dataset, "Bikedata.csv," contains the natural logarithm of the count of bike rentals, log.Rented.Bike.Count, as the dependent variable, and several explanatory variables.

Tasks:

1. Descriptive Analysis:
We will start by describing the relationships in the data using descriptive analysis, such as scatter plots or correlation plots. This will help us understand the relationships between the dependent variable, log.Rented.Bike.Count, and the independent variables: Hour, Temperature, Humidity, Windspeed, Visibility, Solar radiation, Rainfall, Snowfall, Seasons, and Holiday.

2. Linear Regression Model:
Next, we will determine a linear regression model for log.Rented.Bike.Count based on all the given variables. We will estimate the model parameters, assess their statistical significance (p-values), and calculate confidence intervals. Additionally, we will evaluate the goodness-of-fit measure of the model to determine how well it fits the data.

3. Model Selection:
In this task, we will select a suitable subset of explanatory variables for log.Rented.Bike.Count. We can use model selection techniques like forward selection, backward selection, or best subset selection. Criteria such as AIC, BIC, adjusted R^2, or Mallows' Cp values can guide our selection process. We will provide a reasonable explanation for our final model selection.

4. Residual Analysis:
Using the selected model from Task 3, we will create residual plots for model evaluation. These plots will help us check for patterns of linearity, heteroskedasticity, and normality in the residuals. We will also assess multicollinearity using the variance inflation factor (VIF). Finally, we will discuss any potential problems or limitations of our final model.

Literature Recommendations:
For further insights into regression models, methods, and applications, the following literature is recommended:
- Fahrmeir, L., Kneib, T., Lang, S., & Marx, B. D. (2022). Regression: Models, Methods, and Applications.
- Hastie, T., Tibshirani, R., Friedman, J. H., & Friedman, J. H. (2009). The Elements of Statistical Learning: Data Mining, Inference, and Prediction (Vol. 2).
- James, G., Witten, D., Hastie, T., & Tibshirani, R. (2013). An Introduction to Statistical Learning.

Conclusion:
Through this regression analysis project, we aim to understand the relationship between Seoul bike sharing demand and various factors that influence it. By selecting a suitable model and evaluating its performance, we will gain valuable insights into the key determinants of bike rentals in Seoul, South Korea.
