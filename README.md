Download Link: https://assignmentchef.com/product/solved-ece4710j-homework-2
<br>
2: Cleaning the Business Data Postal Codes

The business data contains postal code information that we can use to aggregate the ratings over regions of the city. Let’s examine and clean the postal code field. The postal code (sometimes also called a ZIP code) partitions the city into regions:

<h1>Question 5a</h1>

Let’s look at the distribution of inspection scores. As we saw before when we called head on this data frame, inspection scores appear to be integer values. The discreteness of this variable means that we can use a bar plot to visualize the distribution of the inspection score. Make a bar plot of the counts of the number of inspections receiving each score.

It should look like the image below. It does not need to look exactly the same (e.g., no grid), but make sure that all labels and axes are correct.

Distribution of Inspection Scores

2000

1750

1500

1250

1000

750

500

250

Score

Now, create your scatter plot in the cell below. It does not need to look exactly the same (e.g., no grid) as the sample below, but make sure that all labels, axes and data itself are correct.

First Inspection Score vs. Second Inspection Score

100

5555        60        65        70        75        80        85        90  95        100 First Score

Key pieces of syntax you’ll need:

plt. scatter plots a set of points. Use facecolors= ‘none and edgecolors= ‘b’ to make circle markers with blue borders.

plt. plot for the reference line.

plt.xlabel , plt.ylabel , plt.axis , and plt.title .

Hint: You may find it convenient to use the zip( ) function to unzip scores in the list.

<h2>Question 6d</h2>

To wrap up our analysis of the restaurant ratings over time, one final metric we will be looking at is the distribution of restaurant scores over time. Create a side-by-side boxplot that shows the distribution of these scores for each different risk category from 2017 to 2019. Use a figure size of at least 12 by 8.

The boxplot should look similar to the sample below. Make sure the boxes are in the correct order!

Moderate Risk

High Risk

m17    m18      319 par

Hint: Use sns. boxplot( ) . Try taking a look at the first several parameters. <u>The documentation is linked here!</u>

Hint: Use plt. figure( ) to adjust the figure size of your plot.