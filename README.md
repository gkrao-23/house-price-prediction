# house-price-prediction
1️⃣ **Problem Statement**

Example:

The objective of this project is to build a Linear Regression model to predict house prices based on features such as size (in square feet) and number of bedrooms.

2️⃣ **Dataset Description**

Example:

The dataset contains 15 manually created data samples with the following features:

Size_sqft (Input Feature)

Bedrooms (Input Feature)

Price (Target Variable)

The dataset was stored and manipulated using Pandas DataFrame.
Size_sqft  Bedrooms     Price
0        1000         2   5000000
1        1200         3   6000000
2         800         2   4000000
3        1500         4   8000000
4        2000         5  10000000
5        1700         4   8500000
6        1100         3   5500000
7         900         2   4500000
8        1300         3   6500000
9        1600         4   7500000
10       1800         4   9000000
11       1400         3   7000000
12       1250         3   6200000
13        950         2   4800000
14       2100         5  11000000


3️⃣ **Model Used**

Example:

A Linear Regression model from Scikit-learn was used.
The dataset was split into training and testing sets using an 80-20 split.

4️⃣ **Results**

Example:

**Mean Absolute Error (MAE):256095.304186907
R2 Score: 0.8719707304260014**

The model explains approximately 87% of the variance in house prices.
The MAE value indicates the average prediction error in price. 
The R² score shows how well the model explains the variance in the target variable.
A higher R² and lower MAE suggest the model performs well on unseen data.


5️⃣ Conclusion

Example:

The Linear Regression model performed well on this small dataset. **Feature experimentation** showed that **size is a more influential feature** than the number of bedrooms. The project demonstrates basic ML workflow including data creation, exploration, visualization, training, evaluation, and overfitting analysis.
