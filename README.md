# Using MatPlotlib to compare tumor development

## https://colab.research.google.com/github/ClovisL/Analyzing-tumor-development/blob/main/Pymaceuticals/pymaceuticals_starter.ipynb

## Compares tumor development in mice over the course of 45 days, with different drug treatments. Generates tables and charts for analysis. Final notebook performs the following:

Checks the data for any mouse ID with duplicate time points and removes any data associated with that mouse ID.


Generates a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.


Generates a bar plot using Pandas' DataFrame.plot() and Matplotlib's pyplot that shows the total number of measurements taken for each treatment regimen throughout the course of the study.


Generate a pie plot using Pandas' DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.



Calculates the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculates the quartiles and IQR and quantitatively determines if there are any potential outliers across all four treatment regimens.


Uses Matplotlib to generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.


Selects a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.


Generates a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.


Calculates the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.
