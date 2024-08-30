# Linear-Regression-Using-SPSS
# About Dataset
![image](https://github.com/user-attachments/assets/46d8d7d2-733a-4de2-822c-7c12a4db24e6)
The dataset includes 20 rows and 3 columns which are Age, Experience, and Income.
# Distribution of the Experience
![image](https://github.com/user-attachments/assets/bddc2ee3-a862-4061-bb96-60221ca9a68a)
# Distribution of the Age
![image](https://github.com/user-attachments/assets/7453bbf1-a73b-4d56-936b-59da66387eb7)
# Descriptive Statistics
![image](https://github.com/user-attachments/assets/4cc77306-e564-4a18-91cb-d8be7765aa17)
Income: The mean income is $40,735.50 with a standard deviation of $8,439.798.
Experience: The mean years of experience is 6.20 with a standard deviation of 4.124.
Age: The mean age is 39.65 years with a standard deviation of 10.028.

# Correlations
![image](https://github.com/user-attachments/assets/12a099be-052d-4bbf-9114-9958d8888e9e)
Income and Experience: The Pearson correlation coefficient is 0.984, indicating a very strong positive correlation between income and experience. The p-value (Sig.) is <0.001, suggesting that this correlation is statistically significant.
Income and Age: The Pearson correlation coefficient is 0.532, indicating a moderate positive correlation between income and age. The p-value is 0.008, indicating that this correlation is also statistically significant, but it is weaker compared to the correlation between income and experience.
Experience and Age: The correlation between experience and age is 0.615, showing a moderate positive correlation, and the p-value is 0.002, which is statistically significant.

## Since experience has the highest correlation with income (0.984), it is the most related independent variable for predicting income. Therefore, experience should be used as the independent variable in the simple linear regression equation.

# Model Summary
![image](https://github.com/user-attachments/assets/3b40639c-531f-4927-9ac7-1bfffdcff422)
R: The correlation coefficient for the model is 0.984, indicating a very strong positive relationship between the predictor (experience) and the dependent variable (income).
R Square (R²): The R² value is 0.977, which means that approximately 97.7% of the variance in income is explained by the predictors (experience and age).
Adjusted R Square: The adjusted R² value is 0.969, which accounts for the predictor in the model, providing a slightly more accurate measure of the model's explanatory power.
Std. Error of the Estimate: The standard error of the estimate is 1534.018, representing the average distance that the observed values fall from the regression line.

# ANOVA Table
![image](https://github.com/user-attachments/assets/037a601e-8ea2-4888-a834-2dc939e5ce2c)
F-value: The F-value is 577.118 with a significance level (Sig.) of <0.001, indicating that the overall model is statistically significant, and the experince has a significant impact on income.

# Coefficients Table
![image](https://github.com/user-attachments/assets/1f23c484-5c5d-49a2-8dfe-d310d447867a)
This table provides the coefficients necessary to construct the regression equation.
Constant (Intercept): 28,248.447 is the intercept, meaning that when experience is zero, the predicted income is $28248.447.
Experience (Slope): 2,014.041 is the slope for experience, meaning that for each additional year of experience, the income increases by $2014.041.

# Simple Linear Regression Equation
![image](https://github.com/user-attachments/assets/f453447b-5219-4ce1-be28-fa57da94c8e2)
Since experience has the highest correlation with income, the simple linear regression equation using experience as the sole predictor is:
Income = 2,014.041 + 28,248.447 × Experience
This equation indicates that income increases by $2,162.404 for each additional year of experience.
