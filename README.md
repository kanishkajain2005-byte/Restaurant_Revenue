1F4CB Restaurant Revenue Prediction: A Data Science Approach
This project is a great example of a complete data science workflow, turning raw business data into actionable insights using machine learning. Our objective was to predict monthly restaurant revenue by building a robust and reliable predictive model.

Key Project Steps
Data Preparation and Feature Engineering
We started by getting the data ready for the model. First, we used a technique called one-hot encoding to convert the categorical Cuisine_Type data (like 'Japanese' or 'Italian') into a format the model could understand. We also applied Z-score normalization to scale numerical features, such as Menu_Price and Marketing_Spend, so they'd have a similar impact on the model. To make the model smarter, we engineered a new feature by calculating Revenue_per_Review, which provides a clearer picture of a restaurant's financial performance relative to its customer feedback.

Feature Selection
To ensure our model was efficient and didn't overfit, we used Recursive Feature Elimination (RFE). This method helped us identify the most important features for predicting revenue. The top predictors turned out to be Number_of_Customers, Menu_Price, Marketing_Spend, our newly created Revenue_per_Review, and the Cuisine_Type_Mexican indicator.

Model Training and Evaluation
Using these key features, we trained a Linear Regression model. The model's performance was evaluated using standard regression metrics. It achieved an R-squared (R 
2
 ) score of 0.68, meaning the features in our model can explain about 68% of the variability in monthly revenue. Our Mean Absolute Error (MAE) of 47.05 tells us that on average, our predictions were off by about $47. This is a solid result for a business prediction model.

This project is a successful demonstration of how a structured approach to data analysis can provide a powerful tool for strategic business planning.
