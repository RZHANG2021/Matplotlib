# Matplotlib-Pymaceuticals

Backgroud

The dataset is provided by a pharmaceutical company Pymaceuticals based out of San Diego. The company specializes in anti_cancer pharmaceutical. In the company's most recent efforts, it began screening for potential treatments for squamous cell carcinoma, a commonly occurring form of skin cancer.

The data set is provided by the company based on their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. 

The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.


Process of the analysis:
- Check the data, eliminates the duplicated/ invalid data, generate a clean data frame

- Generate a bar plot to show the total number of timeports for all mice tested for each drup regimen.
  also generate a pie plot to shwo the distribution between sex of all micein the study
  (using Pandas's DataFrame.plot() and Matplotlib's pyplot)
  
- Calculate the final tumor volume of each mouse across four of the most promising treatment   regimens: Capomulin, Ramicane, Infubinol, and 
  Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment 
  regimens.
  
- Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential   
  outliers in the plot by changing their color and style.

- Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

- Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

- Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment.   Plot the linear regression model on top of the previous scatter plot.

Observations:
- Among all the tested drug regimens, Capomulin and Ramicane recorded most of the timepoint counts. 
  Capomuli has 230 counts of timepoint recorded, Ramicane has 178 counts of timepoint recorded.
- The sex distribution among all of mice tested in the study is evenly distributed, female and male distribution percentage is 49.6% and  
  50.4% correspondingly. 
- Among four chosen drug regimens, the data regarding tumor size and Weight of the mouse are normally distributed. Only exception is drug 
  Infubinol, which shows 1 outlier based on the analysis.
- Sample study on the mouse y793 under the drug Capomulin shows steady reduce on the tumor size over the course of 45 days .
  The tumor size and body weight appear to have strong positive correlation. 

