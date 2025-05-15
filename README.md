Overview
This project focuses on improving predictive modeling for housing prices by performing feature engineering on a real estate dataset. I first cleaned and preprocessed the data, created new features, selected important ones, trained several regression models, and then evaluated their performance.

Dataset
The dataset contains various property-related features such as price, area, number of bedrooms, bathrooms, stories, availability of main road, guestroom, basement, air conditioning, parking, preferred area, and furnishing status. The goal is to predict the house price based on these features.

Steps
First, I handled data cleaning by converting categorical variables into numeric form using encoding methods and scaling numerical features. I created new features like bedrooms-to-bathrooms ratio, area per room, and interaction terms to enrich the dataset.

Next, I used Recursive Feature Elimination (RFE) to select the most important features. I split the data into training and testing sets and trained different models including Linear Regression, Ridge Regression, Lasso Regression, and Random Forest Regressor.

Finally, I evaluated the models using metrics like R² score and Root Mean Squared Error (RMSE) to compare their predictive performance. I also visualized feature importance and coefficients to understand the impact of the engineered features on the model.
