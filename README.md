# Data Science Scraping Assingment
## Project A

This folder contains all of the components to this project including an R script which documents my data scraping procedure, many .csv files which include the data I was able to pull from the Twitter accounts of various media sources, and a table and several graphs that present my findings.

I chose to scrape tweets from the following news sources in order to obtain data from a wide range of media sources. I attempted to select 10 media sources that gave me the best picture of the current media landscape and allowed for the most interesting cross-sectional analysis. The primary differences between these organizations are ideology, geographic location, target audience, frequency of output, and method of delivery. The news sources are:

*  Television
   *  NBC News
   *  CBS News
   *  MSNBC
*  Newspaper/Print
   *  LA Times
   *  Boston Globe
   *  Weekly Standard
*  Internet
   *  Vox
   *  Slate
   *  Drudge Report
   *  Daily Caller

The percentage breakdowns for each news source's tweet classification are shown in Figure 1 below:

**Figure 1:**

News Source | Positive | Negative | Neutral
------------|----------|----------|---------
Overall | 22 % | 28% | 50% 
NBC News | 19% | 38% | 43% 
CBS News | 28% | 31% | 41% 
MSNBC | 29% | 26% | 45% 
LA Times | 23% | 24% | 53% 
Boston Globe | 25% | 22% | 53% 
Weekly Standard | 13% | 24% | 63% 
Vox | 26% | 24% | 50%  
Slate | 22% | 34% | 44% 
Drudge Report | 15% | 30% | 55% 
Daily Caller | 26% | 25% | 49% 

The results of this analysis show a number of interesting trends.  First of all, the majority of news in all forms is neutral, with negative news just edging out positive news for the second highest mark.  NBC News' Twitter handle sent out the greatest number of negative tweets while another television news source MSNBC tweeted the most positive messages.  When the data is broken down by partisan ideology, we see that handles which we expect to lean conservative are the most likely to be negative while those that are more liberal are also more positive in their sentiments.  If we instead look at the distribution of tweets across the news sources' method of delivery, the data suggests that television and online outlets were pretty similar while print organizations favored neutral tweets at the detriment of both positive and negative statements.  While this analysis is compelling, its important to remember that we are only sampling from ten media sources.  We would need to gather information from a wider array of outlets over a longer period of time before we could determine if these results are statistically significant, or simply due to random variation at the time we were sampling.  Overall, the Twitter news does seem to be more negative than positive, but neutrality still comes out far ahead of both.
