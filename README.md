Project Name: polymer-production-rate
Develop a  estimates the polymer production rate based on several input parameters.
1.Input Parameters:
Temperature: The reaction temperature (°C ).
Catalyst concentration: The concentration of the catalyst (%).
Reaction time: The duration of the reaction (hours or minutes).
Output:
The output should be the estimated polymer production rate
The program should:

Import Data: Load the CSV file containing relevant data, such as temperature, catalyst concentration, and reaction time.
Handle Missing Values: Identify and handle missing values in the dataset by either filling or removing them.
Data Cleaning: Clean the data by removing invalid entries or outliers to ensure the dataset is suitable for analysis.

Steps:
Import CSV Data: Use appropriate libraries (e.g., pandas) to read the CSV file containing data about polymer production, which may include columns such as temperature, catalyst concentration, reaction time, and production rate.

Handle Missing Values: Check for any missing values in the dataset and handle them. This could include filling missing values with a default value, mean, median, or dropping rows with missing data depending on the context.

Remove Invalid Entries: Identify and remove rows with invalid or unrealistic data points (e.g., negative temperature, catalyst concentration, or reaction time) that do not make sense for polymer production.
Outlier Detection and Removal: Identify and remove any outliers (values that fall significantly outside the expected range for each variable) using statistical methods.

Input:
A CSV file containing polymer production data, with columns such as temperature, catalyst concentration, reaction time, and production rate.
Output:
A cleaned dataset free of missing values, invalid entries, and outliers, ready for further analysis or modeling.
2. Simple Production Rate Calculation:
The polymer production rate should be calculated using the following simplified linear model:
Production Rate = 𝑎
⋅
Temperature=𝑏
⋅
Catalyst_Conc = 𝑐
⋅
Reaction_Time
Production Rate=a⋅Temperature=b⋅Catalyst_Conc=c⋅Reaction_Time.
Input Data: The program should take in the temperature, catalyst concentration, and reaction time for each data entry.
Calculation: Apply the above formula to calculate the polymer production rate for each data point.
3. Visualization:
Create visualizations to better understand the relationships between the variables:

Relationship between Temperature and Production Rate:

Plot a graph (e.g., scatter plot or line graph) showing how the production rate changes with temperature.
Bar Chart of Production Rates for Different Catalyst Concentrations

Table of content :
Data Import and Cleaning
Simple Production Rate Calculation
Visualization
