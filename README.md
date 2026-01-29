# House Price Prediction using Linear Regression

Project Overview
This project focuses on building a **machine learning regression model** to predict house prices based on various features such as area, number of bedrooms, bathrooms, parking, and other amenities.

The project demonstrates a complete **end-to-end regression workflow**, including data preprocessing, feature encoding, model training, evaluation, and visualization, making it suitable for an internship-level data science project.

---

 Objectives
- Predict house prices using Linear Regression
- Understand the fundamentals of regression modeling
- Perform data preprocessing and feature encoding
- Evaluate model performance using regression metrics
- Visualize actual vs predicted prices

---
 
 Technologies & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
 
#Project Workflow

 Data Exploration & Cleaning
- Loaded and inspected the dataset
- Verified data types and structure
- Confirmed absence of missing values
- Identified numerical and categorical features

Feature Engineering
- Converted binary categorical variables (Yes/No) into numerical values (1/0)
- Applied one-hot encoding to the `furnishingstatus` column

 Model Training
- Defined features (`X`) and target (`y`)
- Split data into training (80%) and testing (20%)
- Trained a **Linear Regression model** using Scikit-learn

 Model Evaluation
- Evaluated model performance using:
  - **Mean Squared Error (MSE)**
  - **R² Score**

Visualization
- Created a scatter plot comparing **Actual vs Predicted House Prices**
- Added a reference line to indicate perfect prediction

---

#Results & Insights
- The model explains a significant portion of the variance in house prices
- Predictions are generally close to actual values
- Some outliers indicate scope for improvement using advanced models

---

#Conclusion
This project successfully demonstrates how **Linear Regression** can be applied to predict house prices. It provides a strong foundation in regression modeling, evaluation, and interpretation.
