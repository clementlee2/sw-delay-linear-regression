![image](https://github.com/user-attachments/assets/1b26f976-9d94-402d-a897-9af01dec95b7)


This repository contains a predictive analysis of Southwest Airlines flight delays, conducted as part of a class project.
The project integrates exploratory data analysis (EDA), linear regression techniques (including Box-Cox transformations), and a custom-built cost-savings function to evaluate the financial impact of delays and inform operational decisions.

📊 Project Overview
* Flight delays pose major financial and reputational risks for airlines. Our objective was to:

* Identify key factors driving departure delays

* Develop predictive models to estimate delays using flight and weather data

* Quantify potential cost savings through operational improvements

📁 Data Source
* The dataset was sourced from Kaggle’s “Flight Delay and Cancellation Dataset (2019–2023)”. We filtered and cleaned the data to focus specifically on Southwest Airlines (WN)

🧠 Methodology
* Exploratory Data Analysis (EDA): Identified outliers, seasonal patterns, and delay distributions

* Linear Regression Modeling: Applied both simple linear regression and Box-Cox transformations to improve model fit

* Custom Cost-Savings Function: Created to translate predicted delay times into monetary impact based on internal operational metrics

🔧 Tools & Technologies
* Language: R

* Libraries: ggplot2, dplyr, caret, MASS, lmtest

* Techniques:

* Box-Cox Transformation

* Simple Linear Regression

* RMSE for model evaluation

* Residual diagnostics and model validation

📈 Key Outcomes
* Achieved improved prediction accuracy using transformed models

* Highlighted the most predictive variables (e.g., weather delays, prior leg performance)

* Estimated cost savings under various delay mitigation scenarios

