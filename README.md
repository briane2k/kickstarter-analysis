
Kickstarter Analysis


  This analysis is built to try an answer two questions. Does campaign launch month affect success rate, and does the campaign goal amount affect success rate.
 A neccessary step in getting the data ready for analysis was converting the deadline and launched_at dates to a useable format.

<img>
as you can see this challenge was overcome simply with 
the formula " =(((J2/60)/60)/24)+DATE(1970,1,1) ".

A custom range enumeration was built 
<img>

using a concatination like ' =A4&" "&B4&" "&C4 '.
If a different range enumeration is needed, it can be customized easily with the formulas.
With the preparation complete the analysis can begin.

  The following chart shows Theater Outcomes by Launch Date
<img> chart 1
From the following chart we can see a indication launch date has an effect on campaign success, with 
large numbers of campaigns succedding in May/June/Jul. Additionally avoiding launch months in Nov/Dec seems to be indicated.

  Our 2nd chart shows Outcomes Based on Goals
<img> chart 2

From the 2nd chart, we can draw a conlcusion that Goal amount has some affect on succes rate. Campaigns over $45,000 seem to be less likely to succeed, while campaigns asking $5,000 or less seem to be more successfull.

 Limitations is this dataset may include, how much the campaign was advertised, and how widespread/how many people were given the choice to contribute.  These metrics wern't collected, and could have a large impact on success rate.

 Additional time could be invested to create an analysis base on how long the campaign ran, and how that affected success rate.