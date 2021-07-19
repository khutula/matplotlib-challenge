# GT Bootcamp Matplotlib Homework: Pymaceuticals

## Table of Contents
1. [Introduction](#introduction)
2. [Objectives](#objectives)
3. [Technologies](#technologies)
4. [Files](#files)
5. [Analysis](#analysis)

<a name="introduction"></a>
### Introduction
As a senior Data Scientist for Pymaceuticals Inc., I am be responsible for cleaning, summarizing, charting, and analyzing the data from our most recent animal study, which investigates ten potential treatments for squamous cell carcinoma (SCC) using mice as a study subject.  Our main drug of interest is Capomulin.

<a name="objectives"></a>
### Objectives
Write a Python script using Jupyter Lab that summarizes and displays study data by:
* Summary Statistics Dataframe by Drug Regimen
* Bar Chart of Unique Mice tested with each Drug Regimen
* Pie Chart showing distribution of Mice Gender in overall study
* Outliers in Final Tumor Volume for the four most promising treatments of Capomulin, Ramicane, Infubinol, and Ceftamin
* Boxplots comparing Final Tumor Volume for the four most promising treatments
* Line plot of Timepoint vs Tumor Volume for one mouse in the Capomulin drug treatment
* Scatter plot of Mouse Weight vs Average Tumor Volume for mice in the Capomulin drug treatment
* Linear regression model and correlation coefficient for the scatter plot above

<a name="technologies"></a>
### Technologies
This project uses: 
* Python Version 3.6.13
* Jupyter Lab Version 2.2.6

<a name="files"></a>
### Files
* [Mouse_metadata.csv](data/Mouse_metadata.csv): raw data file for mouse data
* [Study_results.csv](data/Study_results.csv): raw data file for study results
* [pymaceuticals.ipynb](pymaceuticals.ipynb): Jupyter Lab file with data analysis, summary charts, various plots, and observations
* [Jupyter Notebook Viewer of pymaceuticals.ipynb](https://nbviewer.jupyter.org/github/khutula/matplotlib-challenge/blob/main/pymaceuticals.ipynb): use this link to view the Jupyter Lab file in a friendly viewer version

<a name="analysis"></a>
### Analysis

1. Our drug treatment of interest, Capomulin, is in tight competition with drug treatment Ramicane for best results on final tumor volume. This conclusion is supported by the summary stats tables as well as the box plot comparison.
2. The correlation coefficient between mouse weight and average tumor volume for the Capomulin regimen is 0.84. This is a strong, positive correlation. Further analysis may need to be performed to determine if this correlation is hinting that our drug is less effective for mice of higher weights or if this is simply an indication that mice of higher weights tend to have larger tumors.
3. Based on the gender pie chart, we can see that this study as a whole is pretty evenly balanced between male and female mice. As long as the genders are also balanced in each drug regimen, we can feel more confident that we have representative samples along gender lines.