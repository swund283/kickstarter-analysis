# kickstarter-analysis
kickstarter data set for module 1
### Challenge

#### Draws three reasonable conclusions from the data:
1. The optimal range for success within the subcategory “plays” when based on the Goal amount to be raised is $1000 to $4999.  This also holds true when you combine all sub-categories with the upper bucket being capped at $50,000.

2. Worldwide over this entire timeframe the category “theater” has the 2nd highest success rate. Theater has a 60% success rate and Music has a 77%-win rate.  The 73%-win rate that the category “theater” with the sub-category “plays” has indicates that within the category of “theater” it has a very high success rate. 

3. GB has the highest success rate amongst all subcategory ‘plays’, if you remove countries that have less than 2 successful campaigns.  

#### States limitations of the dataset and suggestions for additional tables of graphs:

Displaying data only as %, like the Outcome Based on Goals Chart, at smaller sample sizes of data can be mis-leading.  When the dataset has a very low total count can easily show either very high or very low %.  An example of that is the $40,000 to $44,999 category that has only 2 values and has a 0% success rate. To mitigate this you could include a 2nd chart that is based on the count or you can create a 2nd axis on the same graph and display the count of the instances for a quick reference; I like the 2nd option as 1) we already have that column of data to display 2) displaying that data on the same chart makes it easier to reference at one glance.


#### Outcomes Based on Goal

![Outcomes Based on Goals](https://github.com/swund283/kickstarter-analysis/blob/master/Outcomes%20based%20on%20Goals%20Line%20Chart.png)


#### Outcomes Based on Launch Date

![Outcomes Based on Launch Date](https://github.com/swund283/kickstarter-analysis/blob/master/Outcomes%20Based%20on%20Launch%20Date.png)

