Walmart Sales Analysis and Prediction using Machine Learning
Project Overview

This project focuses on analyzing Walmart sales data to identify key patterns, trends, and factors influencing weekly revenue across different stores. In addition to exploratory data analysis, machine learning models are applied to predict sales and evaluate the impact of economic and environmental variables.

The objective is to combine data analysis and predictive modeling to generate meaningful insights that can support business decision-making in retail operations.

This project was developed as part of my learning journey in data science, where I also leveraged AI tools to help speed up development, improve code efficiency, and structure the analysis process more effectively.

Dataset

The dataset used in this project is publicly available on Kaggle:

https://www.kaggle.com/datasets/mikhail1681/walmart-sales

It contains historical weekly sales data from multiple Walmart stores along with external influencing factors such as temperature, fuel price, CPI, and unemployment rate.

Objectives
Analyze sales performance across different Walmart stores
Identify trends and patterns in weekly sales over time
Evaluate the impact of external factors such as holidays, temperature, fuel price, CPI, and unemployment
Build predictive models to estimate weekly sales
Compare the performance of different regression models
Academic Context

This project was completed as part of my academic journey. I am currently a 3rd-year student at EMSI (École Marocaine des Sciences de l’Ingénieur), preparing to enter my 4th year.

In parallel with my studies, I have completed 5 courses from the IBM Data Science Professional Certificate, which helped strengthen my understanding of data analysis, Python programming, and machine learning fundamentals.

Data Processing

The following preprocessing steps were applied:

Conversion of the Date column into datetime format for time series analysis
Sorting data chronologically to ensure proper time-based analysis
Checking and handling missing values
Preparing data for machine learning models
Exploratory Data Analysis

The analysis focused on understanding the dataset through:

Sales trends over time
Store-wise revenue comparison
Impact of holidays on sales
Relationship between sales and temperature
Influence of unemployment and economic indicators
Correlation analysis between numerical variables
Machine Learning Models

Two regression models were implemented:

Linear Regression

A baseline model that assumes a linear relationship between input features and weekly sales. It provides interpretability and serves as a reference for comparison.

Decision Tree Regressor

A non-linear model capable of capturing complex relationships between variables. It improves flexibility and often performs better when data relationships are not strictly linear.

Model Evaluation

Models were evaluated using:

Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)

The Decision Tree model showed better performance compared to Linear Regression, suggesting that sales patterns are influenced by non-linear relationships between variables.

Key Insights
Sales vary significantly across different stores
Certain stores consistently generate higher revenue than others
Holidays can influence sales depending on timing and store behavior
Economic indicators such as CPI and unemployment have limited direct correlation with sales
Temperature has a weak impact on weekly sales
Non-linear models are more suitable for predicting sales behavior in this dataset
Technologies Used
Python: Core programming language used for the project
Pandas: Data manipulation and analysis
NumPy: Numerical computations
Matplotlib: Data visualization
Seaborn: Statistical visualization
Scikit-learn: Machine learning model development and evaluation
Conclusion

This project demonstrates how exploratory data analysis and machine learning techniques can be applied to understand and predict retail sales behavior. The results show that non-linear models provide better predictive performance, highlighting the complexity of real-world sales data.

The insights from this analysis can help improve forecasting, inventory management, and business decision-making processes.

Author

Ryad Miftah
3rd-year Engineering Student at EMSI (École Marocaine des Sciences de l’Ingénieur)
Preparing for 4th year

Completed 5 courses of the IBM Data Science Professional Certificate
Focused on data analysis, machine learning, and real-world predictive modeling projects

Note on Project Development

This project was developed as part of my learning process in data science. I used AI-assisted tools to help structure the workflow, improve efficiency, and accelerate implementation while maintaining full understanding of the concepts and methods used.

Future Improvements
Implementation of more advanced models such as Random Forest and XGBoost
Hyperparameter tuning for improved accuracy
Time series forecasting methods for better temporal predictions
Deployment of the model as a web application