# kickstarter-analysis
kickstarter data set for module 1
### Challenge

#### Draws three reasonable conclusions from the data:
1. The optimal Goal range for success within the subcategory “plays” when based on the Goal amount to be raised is $1000 to $4999.  This optimal goal range also holds true when you combine all sub-categories in the dataset with cap of 50000+ for the top bucket.

2. Worldwide over this entire timeframe the category “theater” has the 2nd highest success rate. Theater has a 60% success rate and only Music has a higher success rate with 77%.  The 65% success rate that the category “theater” with the sub-category “plays” indicates that within the category of “theater” it has a very high success rate relative to this spcific category and all sub-categories in general.  The subcategory "Plays" also is raising the mean for the entire category of "Theater".

3. "GB" has the highest success rate amongst all sub-category ‘plays’, if you remove countries that have only one campaign for that country.  So launcing in "GB" will create a better oportinity for success. 

#### States limitations of the dataset and suggestions for additional tables of graphs:

Displaying data only as %, like the Outcome Based on Goals Chart, at smaller sample sizes of data can be mis-leading.  When the dataset has a very low total count can easily show either very high or very low %.  An example of that is the $45,000 to $49,999 category that has only 1 value and has a 0% success rate. To mitigate this you could include a 2nd chart that is based on the campaign count or you can create a 2nd axis on the same graph and display the campaign count for a quick reference; I like the 2nd option as 1) we already have that column of data to display 2) displaying that data on the same chart makes it easier to reference at one glance.


#### Outcomes Based on Goal

![Outcomes Based on Goals](https://github.com/swund283/kickstarter-analysis/blob/master/Goal%20Outcomes%20plays.png)


#### Outcomes Based on Launch Date

![Outcomes Based on Launch Date](https://github.com/swund283/kickstarter-analysis/blob/master/Outcomes%20Based%20on%20Launch%20Date.png)


#### NOTED ERRORS ON RUBRIC

FYI I ignored the errors on the Rubric and used the guidance from the application instructions online.

The 2 errors are below in this section: 1) list only 11 rows, missing the 50,000+  2) 20,000 to 24,000 leaves a gap in the data.  I used 20,000 to 24,999.

And​ twelve new rows were correctly created for:
Less Than 1000
1000 to 4999
5000 to 9999
10000 to 14999
15000 to 19999
20000 to 24000
25000 to 29999
30000 to 34999
35000 to 39999
40000 to 44999
45000 to 49999