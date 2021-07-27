***project can be opened in a code editor if you don't have jupyter notebook***

***Features List***
1)	Create a dictionary or list, populate it with several values, retrieve at least one value, and use it in your program

2)	Read data from an external file, such as text, JSON, CSV, etc and use that data in your application

3)	Visualize data in a graph, chart, or other visual representation of data

4)	Use pandas, matplotlib, and/or numpy to perform a data analysis project. Ingest 2 or more pieces of data, analyze that data in some manner, and display a new result to a graph, chart, or other display

***About Project***
I made up a small data set and attempted to visualize and analyze the data. The goal would be
to show that using the BodPod to measure body fat% (BF%) in spinal cord injured (SCI) participants
is comparable to using the DXA.

The 1st and 2nd blocks are for my imports. First, the programs needed to visualize and analyze the data and then the excel sheet that contains the data.

The 3rd block is just separating out the data into different variables for graphing purposes. Variables were made for each sex, injury level, and body composition test.

The 4th block creates mean and standard deviation variables for both columns of BF% data. Then an 
array of each is made so creating a table will be easier.

The 5th block contains the dictionary of means and standard deviations, as well as the data frame
created using the dictionary.

The next few blocks are for visualization. First, I checked to see if the BF% data sets were normally 
distributed by creating histograms and running a Shapiro wilks test. This helps dictate how to proceed
with the analyses.

I then messed around with bar graphs by using the mean/stdev body composition data to create
a bar graph with error bars. The following block contains a nested pie graph showing the break down 
of spinal cord injury levels by sex.

The final graph is a scatter plot showing the body composition data. I created a trendline and ran
a correlation which shows a positive relationship between the BF% of each test.

The last block contains the small bit of stats I could recall. First, I ran an f test to test and see
if the variances of the DXA and BodPod were equal. They were not (p-value of 0.005).
Based on that information, I ran a 2-sided t-test for unequal variances and got a p-value of 0.017.
This tells me that the means are not equal.



