# statistical_study_indoor_air_quality
The script shows a range of different visualization techniques for multivariate data, such as, grouped bar chart and pairplots, and performs statistical inference using an OLS regression

The script is specifically designed to analyze a dataset of environmental measurements in different rooms of a building. The data is read in from an Excel file and is first prepared by cleaning and transforming it to create a DataFrame of the overall rooms dataset. The script then performs various data visualizations to explore the relationships between different environmental measurements and time-related variables such as time of day, day of the week, and working/non-working days.

The script uses various Python packages to perform the data analysis and visualization. These include pandas for data manipulation, seaborn and matplotlib for data visualization, and calendar for working with dates and times. 

In terms of data cleaning and transformation, the script first selects specific columns from the original data, groups the data by room and measurement type, and then computes the mean for each measurement type per timestamp. The script then adds columns for day, week, month, hour, day of the week, and a binary column for whether the day is a working day or not. The script drops any rows where all the selected measurement columns are empty.

The data visualizations in the script include line plots, scatter plots, and bar plots. These visualizations help to explore the relationships between different environmental measurements and time-related variables. For example, the script creates line plots to show how the different environmental measurements vary over time, scatter plots to show the relationships between different measurements, and bar plots to compare the mean measurements between working and non-working days.

Overall, the script provides a comprehensive analysis of the environmental measurements dataset and is useful for anyone interested in analyzing similar data.
