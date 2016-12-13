PlotlyAssignment
========================================================
author: Luke Shulman
date: 12/12/2016
autosize: true



Patient Risk Scores
========================================================

The following scatter plot reflects calculated risk of patient's future cost based on the [CMS-HCC](https://www.cms.gov/Medicare/Health-Plans/MedicareAdvtgSpecRateStats/Risk-Adjustors.html) algorithm. The patient data is taken form one of CMS' Public Use Files and are completely identified.

The risk algorithm was run on 114,000 synthetic patient records. 
ins



Grouped bar Histogram
========================================================

For the plot, I chose a histogram. I had assumed I would make it myself by placing bars at the midpoints outputted by the `hist` function. I then grouped the bars one for each year to show the changes.

As shown, patients in 2010 were overall much riskier than in their previous years. This was not the most efficient way to create the plot. See below





```
Error in file(con, "rb") : cannot open the connection
```
