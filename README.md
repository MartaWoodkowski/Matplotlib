# The Power of Plots with Python's library Matplotlib
## Analysis of Py-maceuticals' anti-cancer drug "Capomulin" vs other treatments

![Laboratory](Images/Laboratory.jpg)

Py-maceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

I've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Py-maceuticals' drug of interest, Capomulin, versus the other treatment regimens. My task was to generate all of the tables and figures needed for the technical report of the study and provide top-level summary of the study results. 
## Steps

* Before I began the analysis, I checked the data for any mouse ID with duplicate time points and removed any data associated with that mouse ID.

* Used the cleaned data for the remaining steps.

* Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generated a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows  the number of total mice for each treatment regimen throughout the course of the study.

* Generated a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculated the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Used Matplotlib to generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlighted any potential outliers in the plot by changing their color and style.

* Selected a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

* Generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

* Looked across all previously generated figures and tables and wrote observations that I made from this data. Included these observations at the top of my notebook.


### Used:
* Python's libraries Matplotlib, Pandas, SciPy
* Jupyter Notebook