Tony Cannistra
CSE512 Sp18 A1

The purpose of this visualization is in addressing whether or not the age group containing the majority of Americans has shifted in the data given, from 1900 to 2000. I chose to create two heatmaps, one for each study year (1900 and 2000), each describing the distribution of individuals in each age group represented as a percentage of total U.S. population during that year. 

I utilize position to display and differentiate among our two primary *dimensions*: Year and Age Group. I stack the two heatmaps vertically to allow for ease of pairwise comparison between years of a given set of adjacent age groups. The use of "xy" positioning of our dimensions was chosen to mirror the two dimensional nature of the grouping used to display the data. Note: though I believe this design allows for easy comparison across adjacent or spatially proximal age groups and for the observation of general trends, it is challenging to compare age groups which are spatially distant (we cannot "remember" color easily). 

I have chosen to use a sequential color gradient to display the distribution of individuals in each age group as a percentage of total population. (Note: we have chosen to explicitly avoid representing the total population sizes across the to years visualized as their stark difference is not related to the question being answered and thereby is distracting, but acknowledge that this is a contextually relevant piece of information as it is the denominator for our group percentages). This choice is motivated by the quantitative nature of the data being displayed (a ratio). I considered the use of shapes with different areas for this display but encountered an implementation challenge. 

In our analysis and visualization I compress ("roll up") an important data dimension (sex) as it is not relevant to the question being answered. I display a reference for my sequential color map on the bottom of the graphic, truncated to a range 0%-12% to highlight differences in age group composition. 

