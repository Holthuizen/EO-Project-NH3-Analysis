# NH3 Analysis
**This repository contains all code related to the Statistical modelling, Time Series Decomposition and Line & Box-plotting, used for atmospheric NH3 concentration analysis project for the EO HTHT Minor.**

All files are [Jupyter Notebooks](https://jupyter.org/), which can be opened using the Jupyter client or using VSCode with Jupyter plugins. The code within these notebooks is normal Python (uses Python 3.10)

## Statistical analysis
- mannwhitney.ipynb
    
    Performs the Mann Whitney U-test on the data from the LML network
- manure.ipynb
  
  Performs a comparative analysis for the period where manure spreading is allowed vs. when it is not allowed
- seasons.ipynb
  
  Performs a comparative analysis in which the meteorological seasons are compared in plot and average
- weekday.ipynb
  
  Performs a comparative analysis in which the average trend in weekdays of all stations are plotted
  
  
## Time Series Decomposition

- dissecting a timeseries into 3 components: Trend, Seasonality and Residual. 
- plotting the input, and its components on subplots with a shared axis for equal comparison 

## Boxplot

matplotlib box plots, to vizualise the distribution of the hourly measurments, grouped by days of the week.
Different time frame/periods where selected

