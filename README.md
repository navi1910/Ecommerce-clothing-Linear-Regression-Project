# Ecommerce-clothing-Linear-Regression-Project

<img src='https://github.com/navi1910/Ecommerce-clothing-Linear-Regression-Project/blob/master/img.png' height=50% width=50%>

An Ecommerce company based in New York City that sells clothing online but they also have in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want.
The company is trying to decide whether to focus their efforts on their mobile app experience or their website.

## Project Objective
- Linear Regression Project to find out which variable has the greatest effect on the yearly amount spent by customers of an ecommerce retailer.
- To create a model which can predict the 'Yearly Amount Spent' by using the values of other columns for the data.

## Methods
* Exploratory Data Analysis

<img src='https://github.com/navi1910/Ecommerce-clothing-Linear-Regression-Project/blob/master/len%20vs%20app.png' height=50% width=50%>

* Data Visualization
* Linear Regression Model using scikit-learn
* Model evaluation using scikit-learn

## Technologies used
* Python
 * Pandas
 * seaborn
 * Scikit-learn
 * Matplotlib

## Procedure
+ The required packages were imported.
+ The data was loaded.
+ The data was checked for null values.

<img src='https://github.com/navi1910/Ecommerce-clothing-Linear-Regression-Project/blob/master/heatmap.png' height=50% width=50%>

+ Exploratory data analysis was done using visualizations in order to figure which variable had the greatest effect on the Target Variable.

<img src='https://github.com/navi1910/Ecommerce-clothing-Linear-Regression-Project/blob/master/amt_spt%20vs%20len_mem.png' height=50% width=50%>

+ Linear Regression Model was built.

## Model Building
+ The data was split into Train and Test sets.
+ LinearRegression was intialized as 'lm'.
+ Model 'lm' was fit to the Train set.
+ The model intercept and coefficients were calaculated.

<img src='https://github.com/navi1910/Ecommerce-clothing-Linear-Regression-Project/blob/master/coefficients.png' height=50% width=50%>

+ The Target Variables for the test set was predicted.
+ We checked the distribution of the predicted values.
+ The predicted values were evaluated.

## Results
+ We conclude that an unit change in **'Length of Membership'** causes the greatest effect on the **'Yearly Amount Spent'**.

<img src='https://github.com/navi1910/Ecommerce-clothing-Linear-Regression-Project/blob/master/amt_spt%20vs%20len_mem.png' height=50% width=50%>

  + An unit change in 'Length of Membership' causes change of 61.78 dollars spent per year.
  + An unit change in 'Time on App' causes change of 38.87 dollars spent per year.

+ **R-squared value: 0.9861924261981547**

+ **MSE: 92.89010304498504**

+ **RMSE: 9.637951185028125**

+ **MAE: 7.645674798915268**





