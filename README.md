Machine Learning Models for House Price Prediction
A Comparative Study of Regression Models

 Author: Akimuddin Aslam Shaikh
 Institution: National College of Ireland, School of Computing


 **Project Overview**
This project explores various machine learning regression models to predict house prices based on real estate data from King County, NYC, and California. The study aims to compare the performance of different regression models and determine the most suitable approach for real estate price forecasting.

 **Key Highlights**
✅ Implemented Decision Tree, Lasso, Linear, Random Forest, Ridge, and Support Vector Machine (SVM) Regression
✅ Applied Pipeline module & PCA (Principal Component Analysis) for dimensionality reduction
✅ Evaluated models using R-squared score, Mean Squared Error (MSE), and Root Mean Squared Error (RMSE)
✅ Used StatsModel for regression analysis
✅ Found that Random Forest Regression with PCA performed best for King County & California datasets, while NYC dataset yielded poor results across models


**Technologies & Libraries Used**
Python 
Scikit-Learn (Regression models & PCA)
StatsModels (Regression analysis)
Matplotlib & Seaborn (Data visualization)
Pandas & NumPy (Data preprocessing)

**Regression Models & Performance**
Model	R² Score	MSE	RMSE	Dataset
Random Forest + PCA	Best	Low	Low	King County, California
Decision Tree Regression	Moderate	Medium	Medium	King County, California
Linear Regression	Moderate	High	High	NYC
SVM Regression	Poor	High	High	NYC
 **Key Finding:** The Random Forest Regression model with PCA performed best for King County & California datasets.
 **NYC Dataset:** None of the models achieved a positive R-squared score, highlighting dataset limitations.
