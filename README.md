
# Kickstarter Analysis


  This analysis is built to try an answer two questions. Does campaign launch month affect success rate and secondly does the campaign-goal-amount affect success rate.
 A necessary step in getting the data ready for analysis was converting the deadline and launched_at dates to a useable format.
 
This image shows this challenge was overcome simply by using the formula " **=(((J2/60)/60)/24)+DATE(1970,1,1)** ".

![Date Conversion.png](/resources/date%20conversion.png)






## A custom enumeration of ranges was needed
I used a formula to build a concatenation like ' **=A4&" "&B4&" "&C4** '.
If a different range enumeration is needed, it can be customized easily with the formulas.

![range enumeration.png](/resources/range%20enumeration.png)





# With the preparation complete the analysis can begin.

  The following chart shows Theater Outcomes by Launch Date

![Theater_Outcomes_vs_Launch.png](/resources/Theater_Outcomes_vs_Launch.png)

From the following chart we can see a indication launch date has an effect on campaign success, with 
large numbers of campaigns succeeding in May/June/Jul. Additionally avoiding launch months in Nov/Dec seems to be indicated.



  Our 2nd chart shows Outcomes Based on Goals
![Outcomes_vs_Goals.png](/resources/Outcomes_vs_Goals.png)

From the 2nd chart, we can draw a conclusion that Goal amount has some effect on success rate. Campaigns over $45,000 seem to be less likely to succeed, while campaigns asking $5,000 or less seem to be more successful.

 Limitations is this dataset may include, how much the campaign was advertised, and how widespread/how many people were given the choice to contribute.  These metrics weren't collected and could have a large impact on success rate.

 If desired additional time could be invested to create an analysis based on how long the campaign ran, and how that affected success rate.
 
 
 
