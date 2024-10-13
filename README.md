# Airbnb Price Analyzer

This project analyzes Airbnb listings to categorize them into price categories based on various features. The analysis includes data exploration, visualization, and a machine learning model to predict the price category.

## Features
- Visualization of the data.
- Categorization of listings into price categories: low, medium, and high.

## Data
The dataset used in this project includes:
- **price**: The price of the Airbnb listing.
- **bedrooms**: The number of bedrooms in the listing.
- **number_of_reviews**: The total number of reviews the listing has received.
- **reviews_per_month**: The average number of reviews the listing receives per month.
- **price_category**: The category of the listing price (low, medium, high).

## Installation
To run this project, you need to have Python and the following libraries installed:
- `pandas`
- `scikit-learn`
- `joblib`

You can install the necessary libraries using pip:
```bash
pip install pandas scikit-learn joblib
Usage

To use the model:

Load the trained model using joblib.
Prepare your input data in the same format as the training data.
Use the model to predict the price category.
