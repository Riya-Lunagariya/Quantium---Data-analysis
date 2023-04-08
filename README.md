# Quantium---Data-analysis
Conducted data analysis using data preparation, customer analytics, experimentation, uplift testing, and commercial application. Conducted data analysis using Python to understand purchasing trends and performed high-level data checks. Created measures to compare control and trial stores, reducing re-analysis. 

Programming language: Python
Libraries used: Numpy, Pandas, Matplotlib, seaborn, sklearn, datetime

Task 1: 
Download the resource csv data files and performe high level data checks using Python such as:
 Creating and interpreting high level summaries of the data
 Finding outliers and removing these (if applicable)
 Checking data formats and correcting (if applicable)

Also deriving extra features such as pack size and brand name from the data and define metrics of interest to draw insights on who spends on chips and what drives spends for each customer segment

Data Cleaning: Checking outliers

![Screenshot (223)](https://user-images.githubusercontent.com/81770671/230743320-a8052e04-0ec8-4a72-bf97-1fa57c7eb699.png)

Task 2: 
To get started use the QVI_data dataset below or your output from task 1 and consider the monthly sales experience of each store. 
This can be broken down by:
total sales revenue
total number of customers
average number of transactions per customer

Create a measure to compare different control stores to each of the trial stores to do this write a function to reduce having to re-do the analysis for each trial store. Consider using Pearson correlations or a metric such as a magnitude distance e.g. 1- (Observed distance – minimum distance)/(Maximum distance – minimum distance) as a measure.

Once you have selected your control stores, compare each trial and control pair during the trial period. You want to test if total sales are significantly different in the trial period and if so, check if the driver of change is more purchasing customers or more purchases per customers etc.

![Screenshot (268)](https://user-images.githubusercontent.com/81770671/230743356-1d98a229-3815-4cea-a809-a2a415ac7a53.png)

Task 3:
Task 3 is targeted specifically at building the ability to recognise commercial, actionable insights from your analysis and displaying it in a clear and concise way for the company's client, with minimal jargon.

As both technical tasks 1 and 2 were open ended in terms of insights, this model answer will focus on the layout and the order of your inclusions, including where to include graphs, taglines, written insights and recommendations.

