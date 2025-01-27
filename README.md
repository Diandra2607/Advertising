# Background
In the modern business world, especially in the marketing industry, sales data analysis plays a crucial role. The success of a company does not only depend on the size of the advertising budget but also on how well it understands and leverages the relationship between marketing strategies across various media and their impact on sales. To help companies stay competitive, advertising data analysis becomes key to understanding spending patterns on platforms such as TV, radio, and newspapers, as well as their effects on sales outcomes. By utilizing these insights, businesses can optimize their marketing strategies to maximize revenue.

# Table of Contents
TV: The amount spent on TV advertising (in some unit of currency).
Radio: The amount spent on radio advertising.
Newspaper: The amount spent on newspaper advertising.
Sales: The resulting sales (in units or revenue).
The dataset contains 200 rows, and all columns have complete data (no missing values). It seems to focus on understanding the relationship between advertising spend across different media channels and the resulting sales. 

# Data Preprocessing
For this data, it will be used multiple linear regression for predicting the sales within the tv, radio, and newspaper. After import the panda, numpy, pyplot, seaborn, statsmodel, and sklearn. The first one is import the data and check it if it has missing value. After checking it, there are no missing data. After that, create the scatter plot. Based on the scatter plot, there are relationship between the TV, radio, newspaper, and the sales.

# Correlation
The next step is to make a correlation using .corr function. Based on the .corr function, the correlation between the advertising on TV and the sales has the biggest correlation, which is 0.901208. Followed by the correlation between the advertising on radio and the sales which is 0.349631 and the correlation between the advertising on newspaper and sales which is 0.15796.

# Regression
After making a correlation, divide the data into training and testing data. The next step is create a multiple linear regression model with the advertising on TV, radio, and newspaper become independent variables, and sales becomes dependent variable. The regression model is Y = 4.714 + 0.055X1 + 0.1X2 + 0.0043X3. After create a regression model, do the simultaneous and partial test. The result for the simultaneous test are advertising on TV, radio, and newspaper influence the sales simultaneously. However, based on the results on the regression partial test, the advertising on TV has more influences in sales than the radio and newspaper. 

# Suggestion
Based on the results on the regression partial test, the advertising on TV has more influences in sales than the radio and newspaper. So, the company should make more advertising on TV, so the sales will be more increased.

