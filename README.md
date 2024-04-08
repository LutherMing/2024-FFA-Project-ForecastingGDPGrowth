

#### Research Framework Summary:
- Introduction
- Methodology (data collection, variable selection)
- Data Analysis (exploratory data analysis, regression analysis, model evaluations)
- Discussion (interpretation, sensitivity analysis, limitations)
- Conclusion

#### Functions Included:
1. `trimify`: Trims data based on specified quantile values.
2. `datify`: Converts characters to dates with a specified format.
3. `html_df`: Displays small tables in HTML format.
4. `calculate_missing_percentage`: Calculates missing percentage in columns and displays in HTML.
5. `min_max_scaling`: Performs Min-Max scaling on data.
6. `z_score_normalization`: Performs Z-score normalization on data.
7. `cal_rmse`: Calculates Root Mean Squared Error.

#### Loading and Saving Data:
- Loads training and testing GDP data.
- Loads independent variables data.
- Loads GDP forecasts data.

#### Data Files:
1. "Data/GDP_Forecast_train.csv"
2. "Data/GDP_Forecast_test.csv"
3. "Data/merged_quarterly.csv"
4. "Data/gdp_forecast_indv.xlsx"
5. "Data/gdp_forecast_mean.xlsx"
6. "Data/Federal_Reserve_GDP_Test_Sample.csv"

#### Project Specific Requirement:
- Forecast quarterly nominal GDP growth rate in the United States based on BEA's final GDP estimate for each quarter.
- Investigate the usefulness of accounting information for GDP forecast.
- Utilize any external data sources to enhance the model.

For more details, refer to the code and functions provided in the file.
