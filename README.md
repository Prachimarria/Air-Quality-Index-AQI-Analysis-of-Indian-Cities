# Air-Quality-Index-AQI-Analysis-of-Indian-Cities
## Steps Performed
1. Data Cleaning
Removed unnecessary columns (note, unit)
Checked and handled missing values
Converted date column into datetime format
Extracted month and year
Ensured AQI values are within valid range (0–500)


2. Exploratory Data Analysis (EDA)
Analyzed statistical summary (mean, median, skewness)
Visualized AQI distribution using histogram
Counted frequency of AQI categories
Observed monthly AQI trends using line plots
Identified outliers using boxplots
Used heatmaps and pairplots to understand relationships



3. Feature Engineering
Created new features like month, year, and day type (weekday/weekend)
Extracted primary pollutant from pollutant column



4. Model Building
🔹 Linear Regression
Used features like month and monitoring stations
Predicted AQI values
🔹 (Optional Extension) Classification
Can classify air quality status (Good, Moderate, Poor, etc.)




5. Model Evaluation
Evaluated using:
R² Score
Mean Squared Error (MSE)

## Observations:

R² Score was very low → model has weak predictive power
Indicates AQI depends on more complex factors

6. Statistical Analysis
Performed hypothesis testing (T-test)
Compared AQI between weekdays and weekends
Decision based on p-value (< 0.05 significance level)



7. Outlier Analysis
Used IQR method to detect outliers
Outliers were not removed as they represent real pollution events



## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

# Conclusion
AQI data shows right-skewed distribution with extreme pollution events
Seasonal trends are observed across months
Some states contribute more to pollution
Basic regression model was not sufficient for accurate prediction
Further improvements can be made using advanced models and additional features

