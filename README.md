# GDP_vs_Internet_Usage
## Overview
This is the repo for the very first analysis I performed in Python: using UN data on GDP and Internet Usage.
## Project Takeaways
This was one of those really well-rounded projects that was an excellent introduction to python's capabilities. I got a firm introduction to correlations, visualization, merging, and data cleaning in Python. 
## The Pitch
Using Python in Jupyter Notebook, analyze the UN's datasets on GDP and Internet Usage. Pick out any correlations you can find, using visualizations and other tools.

## The Data
This was the first time I had really worked not only python, but with a project that required 2 datasets. Further, both datasets were a little messy: they had footnotes and extra spaces and oddly named columns. There was some trimming necessary, so I was able to get a really good intro to what python is capable of in one big bang. 

## Approach to the Problem 
This was a moderately guided analysis, meaning that I followed a set of instructions that walked me through the basic steps of my analysis. Below is a sampling:

 - Which country had the highest percentage of internet users in 2014? What was the percentage? 

 - Which country had the lowest percentage of internet users in 2014? What was the percentage?

 - Repeat for 2004 and 2009.

 - Which country had the highest gdp per capita in 2014? What was the gdp per capita?

 - Which country had the lowest gdp per capita in 2014? What was the gdp per capita?

 - Create some scatterplots:

    a. 2004 Percent Using the Internet vs GDP Per Capita

    b. 2009 Percent Using the Internet vs GDP Per Capita

    c. 2014 Percent Using the Internet vs GDP Per Capita
![image](https://user-images.githubusercontent.com/52726447/71551878-89265980-29b6-11ea-8a56-cc06521698c4.png)

Are there differences across years? What do the plots tell you about any relationship between these two variables? Enter your observations as a markdown cell.

 - Look at the distribution of gdp per capita values for 2014. Is it unimodal?

 - Look at the distribution of Internet Use for 2014. Is it unimodal?

 - What are the top 5 countries in terms of internet use in 2014?

 - Create a data frame called top_5_internet from the combined data frame that has all three years for these 5 countries. You should have 15 rows. Check that this is true.

 - Create a seaborn FacetGrid to show the internet usage trend over time for these 5 countries (those with the highest reported internet use in 2014). Which country had the greatest growth between 2004 and 2014? Is there a plotting issue with Bermuda? Can you fix it?

 - Find the top 5 countries for 2014 in terms of GDP per capita; create a dataframe to look at 10-year trends in gdp per capita for those 5 countries. Use a seaborn facet grid for this.
![image](https://user-images.githubusercontent.com/52726447/71551846-21700e80-29b6-11ea-9ce1-2b4ba5e88f03.png)

