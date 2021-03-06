***Project can be opened in a code editor if you don't have jupyter notebook***

***Features List***
1.	Create a dictionary or list, populate it with several values, retrieve at least one value, and use it in your program
2.	Read data from an external file, such as text, JSON, CSV, etc and use that data in your application
3.	Visualize data in a graph, chart, or other visual representation of data
4.	Use pandas, matplotlib, and/or numpy to perform a data analysis project. 
	Ingest 2 or more pieces of data, analyze that data in some manner, and display a new result to a graph, chart, or other display

***About Project*** 
A fictional dataset was used to visualize and analyze data. The goal would be to show that using the BodPod to measure body fat% (BF%) in spinal cord injured (SCI) participants is comparable to using the DXA.

The 1st and 2nd blocks are for my imports. First, the program visualizes and analyzes the dataset read from  the Excel workbook.

The 3rd block parses out the data into different variables for graphing purposes. Data were assigned to variables for each sex, injury level, and body composition test.

The 4th block calculates the mean and standard deviation for the BF% data and demographics. Then an array of each is populated to create a table later in the program.

The 5th block contains the dictionary of means and standard deviations, as well as the data frame created using the dictionary.

Blocks 6 through 10 are for visualization. First, the program calculates the BF% for the user to determine if the data are normally distributed by creating histograms and running a Shapiro wilks test. 
Results from this test dictate how to proceed with the analyses.

The bar graph graphically displays the mean and /standard deviation for the body composition variable in addition to error bars to present variability. 
The following block contains a nested pie graph stratifying spinal cord injury levels by sex.

The final graph is a scatter plot which presents the body composition data. A trendline was added to more clearly convey the positive correlation between the BF% of each test.

The last block contains the small bit of stats I could recall. First, I ran an f test to test and see if the variances of the DXA and BodPod were equal. 
They were not (p-value of 0.005). Based on that information, I ran a 2-sided t-test for unequal variances and got a p-value of 0.017. This tells me that the means are not equal.




