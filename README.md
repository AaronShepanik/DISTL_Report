<h1>DISTL Report </h1>



<h2>Description</h2>
Principal author of a comprehensive data-driven’ report on the Swenson College of Science and Engineering’s retention rates, graduation rates, etc., including a SWOT analysis with an ROI from researched based solutions. This required a substantial amount of data sourcing and processing from both internal and external sources, multivariate analyses, and enhanced return-on-investment metrics based on advanced statistical modeling techniques. 

The largest skill check during this project was not the actual data analysis, but the aggregation of everything in a single, professional, visually attactive, clear yet detailed document. I'll mention that whis was done while I was on summer vacation and is serving as the foundation and starting point for large collaborative external grant applications for my former colleagues at the university. You can view the full redacted version by clicking on the file above.
<br />


<h2>Languages and Software used Used</h2>

- <b>Google Apps for collaboration with co-author(Sheets, Docs, etc)</b> 
- <b>Microsoft Office </b>

<h2>Techniques Used </h2>

- <b>Exploratory Data Analysis and Summary Statistics (Pivot Tables, Cross-Tabs, etc)</b>
- <b> Data Viz</b>
- <b> Poisson Distribution and Parameter Estimation (for ROI) </b>

<h2>Project walk-through or samples:</h2>

The full report can be viewed [here](https://github.com/AaronShepanik/DISTL_Report/blob/main/DISTL%20Plan%20Redacted.pdf). Unfortunately some of the internal data is private so many of the tables are redacted. One aspect worth highlighting is the Return On Investment metrics based on Poisson models. The report leverages several studies that outline solutions to reducing students lack of success, namely those earning DFW grades. We used these solutions to estimate how much additional resources we'd need to increase student performance to a desired benchmark. And while student success is certainly correlated to retention, there's no literature on how much retention is lifted if we improve the average student exam score by, say, one letter grade. 

To estimate this, I used data from a period of three years to compute ratios of lost students to DFWs, and then weighted these ratios based on the relative enrollments during those years to estimate the most likely value for the average Poisson rates. In other words, for every X DFWS we lose 1 student in the first year, and for every Y DFWs we lose 1 student in their second year, on average. With these parameters, we could then say if we reduce DFWs by a certain number, the probability that we lose 300 or less students in the first year (for example) is 10% based on the Poisson CDF. 

Now that we can estimate the chance of losing a certain number of students, we can directly translate that to tution and revenue for various ROI outlooks. The three outlooks included in the report were optimistic (25% chance or less), likely (over 50% chance of occuring), and conservative (higher than a 90% chance of occuring) scenarios based on the likelihood of only losing a certain number of students. 

<p align="center">
Optimistic Outlook ROI: <br/>
<figure>
<img src="https://github.com/AaronShepanik/DISTL_Report/blob/main/Images/ROI_Optimistic.png"/>
</figure>
<br />
<br />

<p align="center">
Likely ROI:  <br/>
<img src="https://github.com/AaronShepanik/DISTL_Report/blob/main/Images/ROI_Most_Likely.png"/>
<br />
<br />

<p align="center">
Conservative ROI: <br/>
<img src="https://github.com/AaronShepanik/DISTL_Report/blob/main/Images/ROI_Conservative.png"/>
<br />
<br />



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
