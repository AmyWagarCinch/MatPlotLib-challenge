# MatPlotLib-challenge
In this exercise, we look to Pymaceuticals Inc., a fictional burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer that I was recently diagnosed with.

We've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. We have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

In this exercise, I completed the following tasks:

Before beginning the analysis, I checked the data for any mouse ID with duplicate time points and removed the data associated with that mouse ID.

I used the cleaned data for the remaining steps.

I generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

I generated a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of measurements taken for each treatment regimen throughout the course of the study.

I generated a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.

I calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin and calculated the quartiles and IQR and quantitatively determined if there are any potential outliers across all four treatment regimens.

Using Matplotlib, I generated a box and whisker plot of the final tumor volume for all four treatment regimens.

I then selected a mouse that was treated with Capomulin and generated a line plot of tumor volume vs. time point for that mouse.

I generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

I calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment and plotted the linear regression model on top of the previous scatter plot.

I looked across all previously generated figures and tables and wrote three observations or inferences that could be made from the data and included these observations at the top of notebook.
