# house-price-prediction
1️⃣ **Problem Statement**

The objective of this project is to build a Linear Regression model to predict house prices based on features such as size (in square feet) and number of bedrooms.

2️⃣ **Dataset Description**

The dataset contains 15 manually created data samples with the following features:

Size_sqft (Input Feature)

Bedrooms (Input Feature)

Price (Target Variable)

The dataset was stored and manipulated using Pandas DataFrame.


3️⃣ **Model Used**

A Linear Regression model from Scikit-learn was used.
The dataset was split into training and testing sets using an 80-20 split.

4️⃣ **Results**

Mean Absolute Error (MAE):256095.304186907

R2 Score: 0.8719707304260014

The model explains approximately 87% of the variance in house prices.
The MAE value indicates the average prediction error in price. 
The R² score shows how well the model explains the variance in the target variable.
A higher R² and lower MAE suggest the model performs well on unseen data.


5️⃣ **Conclusion**

The Linear Regression model performed well on this small dataset. **Feature experimentation** showed that **size is a more influential feature** than the number of bedrooms. The project demonstrates basic ML workflow including data creation, exploration, visualization, training, evaluation, and overfitting analysis.
