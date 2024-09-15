# California House Pricing - Machine Learning Project

This project focuses on predicting California house prices using a linear regression model. The dataset used is the California housing dataset, which contains information on housing prices along with demographic and geographic data.

## Overview

The goal of this project is to build a machine learning model that predicts house prices in various California districts. The project demonstrates data preprocessing, exploratory data analysis (EDA), and machine learning techniques such as linear regression.

## Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA) using visualizations
- Building a linear regression model for prediction
- Model evaluation using metrics such as Mean Squared Error (MSE) and Root Mean Squared Error (RMSE)

## Dataset

The dataset used for this project is the [California Housing Dataset](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset), which includes:
- `MedInc`: Median income in block group
- `HouseAge`: Median house age in block group
- `AveRooms`: Average number of rooms per household
- `AveBedrms`: Average number of bedrooms per household
- `Population`: Block group population
- `AveOccup`: Average number of household members
- `Latitude`: Block group latitude
- `Longitude`: Block group longitude
- `MedHouseVal`: Median house value for California districts (target variable)

## Project Structure

- **data/**: Contains the dataset and any other data-related files.
- **notebooks/**: Jupyter notebooks for data analysis, model building, and evaluation.
- **src/**: Source code for data preprocessing, model training, and evaluation.
- **models/**: Saved models and performance metrics.

## Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/MohamedAbouzid1/californiaHousePricing.git
    ```

2. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the project:
    ```bash
    python src/main.py
    ```

## Usage

You can experiment with different features, try other machine learning algorithms, and tune the hyperparameters to improve the performance of the model.

## Results

The model is evaluated using Mean Squared Error (MSE) and Root Mean Squared Error (RMSE). These metrics help gauge the accuracy of the predictions.

## Future Improvements

- Implement more advanced models like Random Forest, Gradient Boosting, or Neural Networks to enhance prediction accuracy.
- Explore hyperparameter tuning for linear regression.
- Perform feature engineering to create new variables that might improve the model's performance.

## License

This project is licensed under Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

---

This README provides a clear and structured overview of your project. Let me know if you'd like to add or change anything!
