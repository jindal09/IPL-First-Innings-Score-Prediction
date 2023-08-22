# IPL-First-Innings-Score-Prediction
This Python notebook uses machine learning to predict first-innings scores in IPL cricket matches. It cleans and preprocesses data, trains models including Linear Regression and AdaBoost, and predicts scores for given match details. A concise demonstration of data analysis, modelling, and prediction for cricket enthusiasts.


This code is a Python notebook that performs first innings score prediction for IPL cricket matches. It uses machine learning models to predict the total runs a team is likely to score in the first innings based on various factors. Here's a concise summary of the code:

1. **Importing Libraries:** The code starts by importing necessary libraries, including pandas, numpy, and various machine learning algorithms from scikit-learn.

2. **Loading and Exploring Data:** The IPL dataset is loaded using pandas, and basic exploratory data analysis (EDA) is performed to understand the dataset's structure and content.

3. **Data Cleaning:** Unwanted columns are removed, consistent teams are selected, and data from the first 5 overs of each match is discarded. The 'date' column is converted from a string to a datetime object.

4. **Data Preprocessing:** Categorical features are converted using one-hot encoding. The dataset is split into training and test sets based on the year. Columns are rearranged for modeling.

5. **Model Building:** The code trains and evaluates four models: Linear Regression, Decision Tree Regression, Random Forest Regression, and AdaBoost using Linear Regression as a base learner.

6. **Predictions:** Using the trained Linear Regression model, the code provides functions to predict the score of the first innings for specific matches.

7. **Predictions Examples:** The code showcases predictions for multiple matches by inputting various match details and estimating the potential first innings score.

This code essentially demonstrates how machine learning techniques can be applied to predict the scores of the first innings in IPL cricket matches. It showcases the process of data cleaning, preprocessing, model training, and predictions. This summary is a brief overview of the code's functionality and purpose, suitable for a concise description in a GitHub repository.
