# Olympics

# Olympic Medal Prediction using Linear Regression

## Overview

This project predicts the number of medals won by different countries in the Olympics based on the number of athletes they send and their previous medal count. The model utilizes Linear Regression to make these predictions.

## Dataset

The dataset includes:

-   **Country Code:** The three-letter country code (e.g., USA, IND, CHN).
-   **Year:** The Olympic year.
-   **Athletes:** The number of athletes sent by the country.
-   **Previous Medals:** The number of medals won by the country in the previous Olympic event.
-   **Medals:** The actual number of medals won in the event (used as the target variable for training).

## Model

The model used in this project is Linear Regression, which establishes a relationship between the number of athletes, previous medals, and the predicted medal count.

## Requirements

To run this project, you need the following dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage

1.  **Prepare the Data:** Ensure the dataset is cleaned and formatted correctly.
2.  **Train the Model:** Run the script to train the linear regression model.
3.  **Evaluate Performance:** The model's accuracy is measured using Mean Absolute Error (MAE).
4.  **Make Predictions:** The model predicts the number of medals for a given country based on input features.

## Results

- The model's Mean Absolute Error (MAE) is approximately 3.3, meaning predictions are off by about 3 medals on average.
- Predictions are adjusted to ensure no negative medal counts.
- Some outliers exist where the model overestimates or underestimates medals significantly.
