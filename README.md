# Electricity-Price-Forecasting
The DataFrame contains hourly electricity price data, incorporating multiple factors affecting electricity prices. It includes columns representing energy generation from various sources, energy demand, and relevant weather parameters.

Key Columns
Generation Columns: These columns represent the electricity generated from different sources, including biomass, fossil fuels, nuclear, hydro, and renewable energies. They help in understanding the impact of generation mix on pricing.
Total Load Actual: This column reflects the actual electricity demand during each hour.
Price Actual: The target variable, representing the actual electricity price.
Weather Parameters: Includes temperature, pressure, humidity, and wind speed, which are crucial for understanding how weather affects electricity prices.
Data Cleaning and Preprocessing
Missing Values: I filled missing values in key generation columns and the total load actual column with their mean values to maintain data integrity.
Data Types: Ensured all columns were in the correct data format for analysis.
Feature Engineering: Created additional features based on date and time, such as hour and day of the week, to enhance the predictive capabilities of the model.
Analysis and Modeling
Regression Models: I applied multiple regression techniques to forecast electricity prices, including linear regression and other advanced methods.
Feature Selection: Selected relevant features based on correlation with the target variable, optimizing model performance.
Visualizations
Line Plots: Created line plots to visualize the average electricity prices over different hours and days of the week.
Heatmaps: Developed heatmaps to show the relationship between electricity prices and generation sources.
Box Plots: Used box plots to identify the distribution of electricity prices across different hours and identify potential outliers.
Outcomes and Insights
Key Findings: The analysis revealed significant relationships between energy generation types and electricity prices, indicating that increased renewable generation tends to lower prices during peak demand hours.
Forecasting: The regression models showed promising results, providing a solid basis for further refinement and deployment in a forecasting framework.
