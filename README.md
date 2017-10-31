# Machine Learning Engineer Nanodegree
# Model Evaluation and Validation
## Project: Predicting Boston Housing Prices

## Project Overview
In this project, I applied basic machine learning concepts on data collected for housing prices in the Boston, Massachusetts area to predict the selling price of a new home. I first explored the data to obtain important features and descriptive statistics about the dataset. Next, I properly split the data into testing and training subsets, and determined a suitable performance metric for this problem. I then analyzed performance graphs for a learning algorithm with varying parameters and training set sizes. This enabled me to pick the optimal model that best generalizes for unseen data. Finally, I tested this optimal model on a new sample and compared the predicted selling price to your statistics.

Things I learned by completing this project:

- How to use NumPy to investigate the latent features of a dataset.
- How to analyze various learning performance plots for variance and bias.
- How to determine the best-guess model for predictions from unseen data.
- How to evaluate a model's performance on unseen data using previous data.

### Project files

This project contains three files:

- `boston_housing.ipynb`: This is the main file where I performed the work on the project.
- `housing.csv`: The project dataset. 
- `visuals.py`: This Python script provides supplementary visualizations for the project. Do not modify.


### Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes
