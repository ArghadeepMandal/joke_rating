# joke_rating

## Libraries Used:

matplotlib, pandas, numpy, seaborn for data manipulation and visualization.
LabelEncoder from sklearn.preprocessing for encoding categorical features.
train_test_split from sklearn.model_selection for splitting the dataset.
LinearRegression from sklearn.linear_model for building a linear regression model.
Other libraries: warnings, math for handling warnings and mathematical operations.
## Data Loading and Merging:

Loading datasets: train.csv, jokes.csv, test.csv.
Merging joke text into the training and test datasets based on joke_id.
## Data Exploration:

Checking for missing values in each dataset.
Visualizing boxplots for user and joke IDs.
Visualizing bar plots for the distribution of ratings.
## Data Preprocessing:

Label encoding applied to categorical features.
## Model Building:

Splitting the dataset into features (X) and target variable (y).
Training a Linear Regression model on 40% of the data.
Visualizing coefficients using a barplot.
## Model Evaluation:

Computing Root Mean Squared Error (RMSE) and printing the result.
## Submission:

Making predictions on the test set and saving the results to a CSV file for submission.
