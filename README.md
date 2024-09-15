# DVD Rental Duration Prediction

## Project Overview
This project aims to help a DVD rental company predict the number of days a customer will rent a DVD, based on historical data. The company provided a dataset containing various features like the rental date, return date, rental rate, and amount paid. The goal is to build a regression model that predicts the rental duration (in days) with a Mean Squared Error (MSE) of 3 or less.

The model will assist the company in better inventory planning, ensuring that DVDs are available to customers when needed.

## Dataset
The dataset, `rental_info.csv`, includes the following features:

- **rental_date**: The date (and time) when the customer rents the DVD.
- **return_date**: The date (and time) when the customer returns the DVD.
- **amount**: The amount paid by the customer for renting the DVD.
- **amount_2**: The square of `amount`.
- **rental_rate**: The rate at which the DVD is rented.
- **rental_rate_2**: The square of `rental_rate`.
- **release_year**: The year the DVD was released.

## Key Steps
1. **Data Cleaning and Preprocessing**:
   - Handling missing values, if any.
   - Feature engineering to extract relevant information from the rental and return dates.
   
2. **Modeling**:
   - Trying out different regression models (e.g., Linear Regression, Decision Trees, Random Forest, etc.).
   - Evaluating the models based on Mean Squared Error (MSE).

3. **Evaluation**:
   - Selecting the model with the lowest MSE (target: MSE ≤ 3).

## Future Improvements
- Experiment with more advanced regression models like Gradient Boosting and Neural Networks.
- Perform hyperparameter tuning to further reduce the MSE.
