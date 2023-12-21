# House Price Prediction Model

## Overview

This repository contains the implementation of a house price prediction model using various regression techniques. The models employed include:

- Linear Regression
- Random Forest Regressor
- XGB Regressor
- Ridge Regression
- Gradient Boost Regressor
- LGBM Regressor
- CatBoost Regressor
- Voting Regressor
- StackReg Regression (yielding the best results)

## Data Cleaning

A crucial step in the process involved data cleansing. I addressed missing values by imputing appropriate values where data was unavailable. This ensured a more comprehensive dataset for model training and evaluation.

## Visualization

The project incorporates Matplotlib for data visualization, aiding in the exploration and understanding of the dataset. Visualizations, such as correlation matrices, were utilized to gain insights into the relationships between different features.

## Usage

To replicate and explore the results, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/officialshivansh26/Kaggle_House_Price_Prediction.git
   cd house-price-prediction
2. Install the required dependencies:
     ```bash
   pip install -r requirements.txt
3.Run the Jupyter notebook or Python script to train and evaluate the models.

Feel free to experiment with different parameters, models, or extend the dataset for further analysis.

##Results
The StackReg Regression model exhibited superior performance, providing the most accurate house price predictions among the implemented techniques.

##Acknowledgments
Special thanks to the Kaggle community and the contributors of the libraries used in this project.

If you find this project helpful or have suggestions for improvement, feel free to open an issue or submit a pull request.

Happy coding!
