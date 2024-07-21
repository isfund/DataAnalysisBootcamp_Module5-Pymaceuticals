# DataAnalysisBootcamp_Module5-Pymaceuticals

In this project I am analyzing a dataset containing information on various treatments given to mice and the resulting tumor volumes recorded over a study period. The goal is to get meaningful insights using statistical analysis and visualization.

Dataset
The dataset includes two CSV files:
1.	Mouse_metadata.csv
2.	Study_results.csv

1. Data Preparation
Merging DataFrames: I combined the Mouse_metadata and Study_results DataFrames into one DataFrame.
Data Cleaning: I identified and removed duplicate entries based on mouse ID and time point to ensure data accuracy.
Unique Mouse Count: I counted the number of unique mice IDs before and after cleaning the data to verify the process.

2. Summary Statistics
I created a summary statistics DataFrame for tumor volumes, grouped by drug regimen that included:
-	Mean
-	Median
-	Variance
-	Standard Deviation
-	Standard Error of Mean (SEM)

3. Bar Charts and Pie Charts
Bar Charts: I made two bar charts showing the total number of time points for each drug regimen. One chart was created using Pandas, and the other using Matplotlib.
Pie Charts: I created two pie charts showing the distribution of female versus male mice in the study, again using both Pandas and Matplotlib for comparison.

4. Quartiles, Outliers, and Box Plot
Final Tumor Volume Calculation: I calculated the final tumor volume for each mouse under four promising treatments: Capomulin, Ramicane, Infubinol, and Ceftamin.
Outlier Detection: I calculated quartiles and interquartile ranges to identify potential outliers.
Box Plot: I created a box plot to show the distribution of final tumor volumes for each treatment group, highlighting any outliers.

5. Line Plot and Scatter Plot
Line Plot: I generated a line plot for a single mouse treated with Capomulin, showing the tumor volume over time.
Scatter Plot: I made a scatter plot to show the relationship between mouse weight and average tumor volume for mice treated with Capomulin.

6. Correlation and Regression
Correlation Coefficient: I calculated the correlation coefficient between mouse weight and average tumor volume for the Capomulin treatment regimen.
Linear Regression Model: I fitted a linear regression model to the data and plotted it on the scatter plot to visualize the relationship.

In conclusion, the analysis provides a better understanding of how different drug regimens affect tumor volumes in mice. The visualizations help highlight key patterns and potential outliers in the data. This help us to make informed decisions about the treatments.
