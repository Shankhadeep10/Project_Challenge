# YouTube dislikes dataset analysis
-------------------------------------
# Objective :

To do data analysis and explore on the YouTube dislikes data using numpy,pandas,matplotlib and seaborn libraries
and extarct meaningfull insights by performing EDA.

# Requirements tools :

Python(Numpy,Pandas) and visualization libarires like Matplotlib and Seaborn.

# Insights :

At beginning I have checked the missing values in this dataset .I saw in this dataset column "Comments" has some missing values.
After statistically analysis I dropped them because the datatype of column is object and I was not getting any statistical
information from this column.

i.Finding the title of video which has maximum numbers of like and maximum numbers of dislikes.

ii.Also find which channel has munimum numbers of likes and dislikes.

iii.Added a new column "published_month" based on column "published_date".

iv.Also find the month wise published videos counts on each channels.

v.In the end plotted scatter plot for the columns dislikes and view_counts.
(from this scatter plot I can see numbers of dislikes and view_counts have positive correlationship between them it can be empact on 
our target variable.)


