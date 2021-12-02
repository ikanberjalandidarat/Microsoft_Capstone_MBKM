# Microsoft Capstone KMMI
This repository will be used for Microsoft's capstone project in regards to its Data and Artificial Intelligence program from Kampus Merdeka. 
Made by Zhafira E. Fawnia, Computer Science, Universitas Gadjah Mada
18/423121/PA/18204

[1] Project using MariBelajar.org score-card (fiscal year 2020/2021) dataset 
This project's purpose is ML-Ops Suitability Check: A Business Intelligence Approach, where it will be done with using **three** different Python Notebooks:
- Preprocessing and loading data (Involves one hot encoding) (Run this first)
- Using cleaned and encoded data through feature selection to be inputted to Random Forest & Linear Models (Run this second)
- Using cleaned and encoded data **without** feature selection (using all features to seperate independent and dependent variables) for a Linear Regression model (Run this third)

Using Power BI: 
- Creating a dashboard for both Fiscal 2020 and 2021 (Mobile version friendly) 

[2] Project using MariBelajar.org's Business dataset of property sales
This project's purpose is within the scope of Machine Learning Property Prices Prediction Based on Combinatory Features Selection
and various algorithms, this project will be done using one Python notebook that consists of:
- Preprocessing and cleaning the data 
- Outlier detection in variable 'price'
- Exploratory data analysis 
- Using feature engineering with numerous algorithms to then combine the best suited to choose, (from 19 features to 10), using Pearson,	Chi-2m,	RFE, and	Random Forest
- Applying machine learning algorithms to predict 'price' of the property sold based on its features.
- Approaches used are: Standardized Linear Regression, (Hyperparameter Tuned) Random Forest Regression, Robust Regression (Using RANSAC), Stochastic Gradient Descent, Elastic Net Regression, Artificial Neural Network (Sequential model using RelU activation function) 
- Then the results will be evaluated by creating a dataframe that shows predicted vs actual values, alongside that Mean Squared Erorr (MSE), Mean Absolute Error (MAE), Root Mean Square Error (RMSE), and R squared value (To see how the model fits the data, the higher the R squared value, the better). -> The results of all the algorithms used will be evaluated with these four metrics and then applied to one dataframe and exported to excel.

Using Power BI:
- Creating a report for the property sales 