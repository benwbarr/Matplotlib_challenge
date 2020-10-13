# **Matplotlib challenge  The Power of Plots**
> Pymaceuticals Matplotlib challenge

![alt text](https://www.qualtrax.com/wp-content/uploads/2018/02/Crime-Lab.jpg)

A recent animal study. In this study, 250 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 


## Dependencies

>This was done in Jupyter Notebooks and you will need to install and import the following

-matplotlib.pyplot

-pandas 

-numpy 

-scipy.stats

-seaborn 


## Assigned Tasks

You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results..

1. Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.


2. Use the cleaned data for the remaining steps.


3. Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.


4. Generate a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows  the number of total mice for each treatment regimen throughout the course of the study.


![alt text](https://github.com/benwbarr/Matplotlib_challenge/blob/main/Images/bar%201.PNG?raw=true)



5. Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.

![alt text](https://github.com/benwbarr/Matplotlib_challenge/blob/main/Images/pie1.PNG?raw=true)

NOTE: These plots should look identical.



6. Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.


7. Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.



8. Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

![alt text](https://github.com/benwbarr/Matplotlib_challenge/blob/main/Images/scat1.PNG?raw=true)

9. Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

![alt text](https://github.com/benwbarr/Matplotlib_challenge/blob/main/Images/scat2.PNG?raw=true)

10 Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

![alt text](https://github.com/benwbarr/Matplotlib_challenge/blob/main/Images/scat3.PNG?raw=true)

### Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook. ###

1. 






