# Forecasting-prophetAuckland Cycling Count Prediction Project

### Overview

This project aims to predict cycling counts in Auckland, New Zealand, using historical data and Prophet forecasting model. In this exercise, we explore the effects of incorporating holidays into the forecasting model and analyze its impact on prediction accuracy.

### Installation
Before running the notebook, make sure you have the required libraries installed. You can install them using pip:
pip install holidays
pip install prophet

### Usage
1. Data Preparation: Ensure you have the necessary data files in your working directory. The dataset includes cycling counts by day (cycling_counts_by_day(1).csv) and weather data (Auckland_weather_combined(1).csv).
   
2. Run the Notebook: Open the Jupyter notebook (Auckland_Cycling_Prediction.ipynb) in your preferred environment.
   
3. Follow Along: Execute each cell in the notebook sequentially to load data, preprocess it, train the Prophet model, and make predictions.

4. Analyzing Results: Examine the visualizations and interpret the results. Pay special attention to the comparison between models with and without holidays.

5. Additional Analysis: Modify the notebook as needed to further investigate the effects of holidays or improve model performance.
   
### Files Included
ForcastExerciseWithHolidays_NjinjuZilefacFogap(1).ipynb : Jupyter notebook containing the code and analysis.
cycling_counts_by_day.csv: Dataset containing historical cycling counts in Auckland.
Auckland_weather_combined.csv: Dataset containing historical weather data for Auckland.
README.md: This file, providing an overview of the project.

### Results
A) Decrease in RMSE with Holidays
RMSE with Holidays: 193.67911455920358
RMSE without Holidays: 195.4605947338803

B) Interpretation of Fit
The addition of holidays may have improved the prediction accuracy, especially during significant events like Waitangi Day. The forecast during the week of Waitangi Day can be analyzed to determine if the model captured the effects of the holiday.


### Contributors
Njinju Zilefac Fogap


