# Diamond Sales Prediction
## Overview
This notebook aims to predict the sales prices of diamonds based on various features such as carat weight, cut quality, color, clarity, and more. The dataset used for this analysis is sourced from diamonds.csv.

### Data Preprocessing
1. Checked for and handled null values.
2. Removed duplicate rows.
3. Encoded categorical values using Label Encoder.
4. Detected and addressed outliers in feature variables.
### Exploratory Data Analysis (EDA)
1. Explored the distribution of diamonds based on cut, color, and clarity using count plots.
2. Analyzed the relationship between sales prices and numerical features.
3. Conducted quantitative analysis on feature correlation using a heatmap.
4. Visualized the distribution of numerical features using scatter plots.
### Feature Selection
1. Selected relevant features for prediction.
2. Utilized SelectKBest and f_regression for feature scoring.
3. Normalized input features using MinMaxScaler.
### Model Training
1. Constructed a neural network model using Keras Sequential API.
2. Applied early stopping and learning rate scheduling to optimize training.
3. Achieved a R-squared value of approximately 80% on the test set.
### Top Features Impacting Sales Price
Explored the top features influencing sales prices, including carat weight, cut quality, polish, and more.


### Dependencies
1. Python 3.x
2. pandas
3. numpy
4. matplotlib
5. seaborn
6. scikit-learn
7. keras
### How to Run
Install the required dependencies using

    pip install -r requirements.txt.

Run the Jupyter notebook diamond_sales_prediction.ipynb for a step-by-step analysis.
