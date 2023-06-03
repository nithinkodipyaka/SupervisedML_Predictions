# Prediction using Supervised ML
This project aims to predict the percentage score of a student based on the number of hours studied using Supervised Machine Learning. The dataset used for this analysis can be found at the following link: http://bit.ly/w-data.

## Author
Nithin Kodipyaka

## Organization
GRIP: The Sparks Foundation

## Libraries Used
Pandas

NumPy

Matplotlib

scikit-learn

## Steps Involved
Data Import: The dataset is imported from the provided link using the pandas library.

Data Exploration: The first 10 rows of the dataset are displayed to get an overview of the data.

Data Visualization: The distribution of scores is visualized using a scatter plot.

Data Preparation: The dataset is divided into input features (X) and target variable (y).

Data Split: The data is split into training and testing sets using the train_test_split function from scikit-learn.

Model Training: A linear regression model is created and trained using the training data.

Regression Line Plot: The regression line is plotted based on the trained model.

Prediction: The model is used to predict the scores for the test data.

Evaluation: The predicted scores are compared with the actual scores and evaluation metrics are calculated, including Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared score (R2).

## Conclusion
Based on the trained linear regression model, the predicted score for a student studying for 9.25 hours per day is displayed. Additionally, the evaluation metrics are calculated to assess the performance of the model.

