# StormReport
Reproducible Research Course Project 2

## Data

The data for this assignment come in the form of a comma-separated-value file compressed via the bzip2 algorithm to reduce its size. You can download the file from the course web site:

Storm Data [47Mb]
There is also some documentation of the database available. Here you will find how some of the variables are constructed/defined.

National Weather Service Storm Data Documentation
National Climatic Data Center Storm Events FAQ
The events in the database start in the year 1950 and end in November 2011. In the earlier years of the database there are generally fewer events recorded, most likely due to a lack of good records. More recent years should be considered more complete.

## Assignment

The basic goal of this assignment is to explore the NOAA Storm Database and answer some basic questions about severe weather events. You must use the database to answer the questions below and show the code for your entire analysis. Your analysis can consist of tables, figures, or other summaries. You may use any R package you want to support your analysis.

### Questions

Your data analysis must address the following questions:

1. Across the United States, which types of events (as indicated in the 𝙴𝚅𝚃𝚈𝙿𝙴 variable) are most harmful with respect to population health?
2. Across the United States, which types of events have the greatest economic consequences?
Consider writing your report as if it were to be read by a government or municipal manager who might be responsible for preparing for severe weather events and will need to prioritize resources for different types of events. However, there is no need to make any specific recommendations in your report.

### Requirements

For this assignment you will need some specific tools

RStudio: You will need RStudio to publish your completed analysis document to RPubs. You can also use RStudio to edit/write your analysis.
knitr: You will need the knitr package in order to compile your R Markdown document and convert it to HTML
Document Layout

Language: Your document should be written in English.
Title: Your document should have a title that briefly summarizes your data analysis
Synopsis: Immediately after the title, there should be a synopsis which describes and summarizes your analysis in at most 10 complete sentences.
There should be a section titled Data Processing which describes (in words and code) how the data were loaded into R and processed for analysis. In particular, your analysis must start from the raw CSV file containing the data. You cannot do any preprocessing outside the document. If preprocessing is time-consuming you may consider using the 𝚌𝚊𝚌𝚑𝚎 = 𝚃𝚁𝚄𝙴 option for certain code chunks.
There should be a section titled Results in which your results are presented.
You may have other sections in your analysis, but Data Processing and Results are required.
The analysis document must have at least one figure containing a plot.
Your analysis must have no more than three figures. Figures may have multiple plots in them (i.e. panel plots), but there cannot be more than three figures total.
You must show all your code for the work in your analysis document. This may make the document a bit verbose, but that is okay. In general, you should ensure that 𝚎𝚌𝚑𝚘 = 𝚃𝚁𝚄𝙴 for every code chunk (this is the default setting in knitr).
