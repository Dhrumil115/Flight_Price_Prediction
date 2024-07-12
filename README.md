# Flight_Price_Prediction
Flight Price Prediction is a machine learning project that aims to predict flight prices based on various factors such as route duration, source, destination, arrival, and departure times. Using a dataset of over 300,000 flight records, we employ different machine learning algorithms including Decision Tree, Logistic Regression, and Random Forest to forecast flight prices. Our model achieved an impressive 96% accuracy with the Decision Tree algorithm.

## Abstract
Frequent flyers often seek the best deals and optimal times to purchase tickets, but airline prices can vary significantly based on numerous factors, making it challenging for customers to predict the best times to buy. This project addresses this issue by developing a machine learning framework that assists customers in determining the best time to purchase plane tickets. We collected data on various flight attributes and used machine learning techniques to predict ticket prices. The Decision Tree model demonstrated the highest accuracy in predicting flight prices.

## Problem Statemet
Accurately estimating flight prices is challenging for both passengers and airlines due to the dynamic nature of ticket pricing. This project explores the application of supervised machine learning algorithms to predict flight costs, aiding consumers in making informed decisions and helping airlines optimize their pricing strategies.

## Approach
1. Data Collection and Preprocessing:
   * Dataset: 300,153 rows and 10 columns, each representing different flight attributes.
   * Libraries used: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
   * Techniques: Target Encoding, MinMax Scaling.
2. Exploratory Data Analysis:
   * Visualized data distributions using pie charts, bar graphs, scatter plots, and box plots.
   * Identified attributes with the strongest correlation to flight prices using Pearson correlation.
3. Modeling:
   * Machine Learning Algorithms: Decision Tree, Random Forest, Logistic Regression.
   * Evaluation Metrics: Accuracy, Precision, Recall, F1 Score, Confusion Matrices, Classification Reports.
4. Results:
   * Decision Tree achieved the highest accuracy (97%), followed by Random Forest (94%) and Logistic Regression (90%).

## Conclusion
This project demonstrates the potential of machine learning models in predicting flight prices based on historical fare data. The models developed, particularly the Decision Tree, provide reliable predictions that can help customers find the best times to purchase tickets, ultimately making air travel more cost-effective.
