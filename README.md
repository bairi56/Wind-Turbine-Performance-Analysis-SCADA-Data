# Wind-Turbine-Performance-Analysis-SCADA-Data

This project analyzes **wind turbine performance** using **SCADA data**. The goal is to explore the relationship between wind speed, blade pitch angle, and power production, and to identify trends and patterns in the data.

## Key Highlights
- **Objective:** Analyze wind turbine performance and model the relationship between wind speed and power production.
- **Dataset:** SCADA data with columns such as `Timestamp`, `WindSpeed`, `PitchAngle`, and `PowerProduced`.
- **Preprocessing:**
  - Data wrangling: Loading, renaming columns, and handling missing/invalid values.
  - Data cleaning: Stripping whitespace, converting data types, and filling missing values.
- **Visualization:**
  - Histograms for `WindSpeed`, `PitchAngle`, and `PowerProduced`.
  - Scatter plot to visualize the relationship between `WindSpeed` and `PowerProduced`.
  - Line plots for monthly averages of wind speed and power production.
- **Analysis:**
  - Grouped data by month to calculate average wind speed and power production.
  - Identified the top 10 days with the highest average wind speed in 2022.
  - Performed curve fitting to model the relationship between wind speed and power production using a quadratic equation.
- **Tools Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scipy.

## Key Findings
- **Wind Speed vs. Power Production:** A quadratic relationship was observed, with power production increasing with wind speed up to a certain point.
- **Monthly Trends:** Seasonal variations in wind speed and power production were identified.
- **Top Wind Speed Days:** The top 10 days with the highest average wind speed in 2022 were identified.

## Future Improvements
- Incorporate more complex models (e.g., machine learning) for predictive analysis.
- Analyze additional factors such as temperature and turbine maintenance data.
- Optimize the curve-fitting model for better accuracy.

## References
- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Scipy Documentation](https://scipy.org/)
