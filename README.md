E-commerce Customer Spending Analysis

This project analyzes a dataset of an e-commerce company to understand customer behavior and its impact on yearly spending. The primary goal is to determine whether the company should focus its efforts on improving its mobile app experience or its website. A linear regression model is built to predict the "Yearly Amount Spent" based on different customer attributes.

Dataset
The analysis is performed on the Ecommerce Customers dataset, which contains the following customer information:
Email: The email address of the customer.
Address: The mailing address of the customer.
Avatar: The customer's chosen avatar color.
Avg. Session Length: The average duration of a customer's in-store style advice sessions.
Time on App: The average time in minutes the customer spends on the mobile app.
Time on Website: The average time in minutes the customer spends on the website.
Length of Membership: The number of years the customer has been a member.
Yearly Amount Spent: The total amount spent by the customer in a year (this is the target variable).

Exploratory Data Analysis (EDA)
Initial analysis was conducted to explore the relationships between different variables in the dataset.
A pairplot was used to visualize the pairwise relationships, which revealed a strong linear correlation between Length of Membership and Yearly Amount Spent.
A heatmap of the correlation matrix confirmed that Length of Membership is the most correlated feature with Yearly Amount Spent.

Linear Regression Model
A linear regression model was trained to predict the Yearly Amount Spent.
Features (X): Avg. Session Length, Time on App, Time on Website, Length of Membership.
Target Variable (y): Yearly Amount Spent.
The data was split into training (70%) and testing (30%) sets to evaluate the model's performance.

Results and Findings
The model performed well on the test data, and the analysis of its coefficients provided the following insights:
Holding all other features constant, a 1-year increase in Length of Membership is associated with an increase of $61.28 in yearly spending.
Holding all other features constant, a 1-minute increase in Time on App is associated with an increase of $38.59 in yearly spending.
Holding all other features constant, a 1-minute increase in Time on Website is associated with an increase of only $0.19 in yearly spending.

Conclusion:
The analysis clearly indicates that both the Length of Membership and the time spent on the mobile app are significant drivers of customer spending. The website, on the other hand, has a negligible impact on the amount spent.
So the company should:
Focus on the Mobile App - Invest in developing and improving the mobile app, as it has a much stronger correlation with customer revenue.
Enhance the Website - The website is underperforming compared to the app. The company could either invest in a major overhaul to improve its engagement and sales potential or reallocate the resources to the more profitable mobile app.
