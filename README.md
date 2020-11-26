
## ada-2020-project-milestone-p3-p3_bcd

# ___How do major social and cultural events affect human mobility?___

### 1. Abstract:
- The paper explores the periodicity of movements in time and location upon friendship. We propose to explore the changes in mobility on special days of the year in different regions. For example, does Christmas make a difference in mobility and if yes, where? We will build an additional dataset containing those important dates. We will then analyze the average distribution of mobility in each region and compare this distribution to the mobility observed on those special days. We will detect cultural differences between regions and whether an event creates an increase or a decrease in mobility. We will create appropriate visualizations for each important date representing the variations in mobility in each region to highlight significant differences. The different regions of the world are set to be the different continents.


### 2. Research questions :
- Do certain events specifically influence people’s mobility ? If yes, does the nature of the event affect its influence on people’s mobility (religious celebrations, sports events, historic dates, etc.) ?
- Is people’s mobility due to important events different in each region of the world?
- How far from their homes do people tend to travel for specific and important events? 
 
 ### 3. Proposed datasets:
- We want to evaluate the impact of big social and cultural events on people’s mobility. Hence we need to establish a list of the events we want to consider. Eligible dates are: religious celebrations, major sports events, start of a new year in different calendars, social manifestations, impactful election days, etc.. We saw that most check-ins occured in North-America, Europe or Asia, so the events we will consider should be culturally attached to at least (but not only) one of these regions. Moreover, we want events that cover the period from April 2008 to October 2010 (years on which we have the social networks data). As the dates considered are very few and specific, we find it easier to construct the dataset ourselves instead of trying to look for one online that might not comply with our requirements.
- Gowalla dataset from the paper. This dataset contains all checkins made on Gowalla between February 2009 and October 2010. With this dataset we will be able to see the trends in mobility all year long and on the special days of the other dataset.
- Brightkite dataset from the paper. This dataset contains all checkins made on Brightkite between April 2008 and October 2010. Thanks to the analysis of the checkins we will have an additional trend of mobility that we will be able to compare.

 - First draft of the dates we will consider (we might modify it if we see that some events are not relevant, or that we are missing important ones) :
 
| Event  |  Dates |  Year | Location  | Type |
|---|---|---|---|---|
|  Christmas |  24/12 |  All |  NA |  Religious Celebration |
|  New Years Eve |  31/12 | All  | NA  |  Cultural Celebration |
|  Thanksgiving | 26/11  | 2009  |  North America |  Cultural Celebration |
|   |  27/11 | 2008  |  North America |  Cultural Celebration |
|  Passover |  20/04 to 26/04 | 2008  |  All |  Religious Celebration |
|   | 09/04 to 15/04  |  2009 | All  |  Religious Celebration |
| | 30/03 to 05/04  |  2010 | All  | Religious Celebration  |
| Ghandi's Birthday  | 02/10  | All  |  Asia |  Religious/Cultural Celebration |
| Halloween |  31/10 | All  |  North America, Europe | Cultural Celebration  |
| Chinese New Year  | 26/01  |  2009 |  Asia | Cultural Celebration  |
|   |  14/02 | 2010  | Asia  | Cultural Celebration  |
|  Easter | 23/03 & 24/03  | 2008  |  NA | Religious Celebration |
|   |  13/03 & 14/03 |  2009 | NA | Religious Celebration  |
|   |  04/03 & 05/03 | 2010  | NA  | Religious Celebration  |
|  Ramadan | 01/09 to 30/09  | 2008  | NA  | Religious Celebration  |
|   |  21/08 to 20/09 |  2009 |  NA |  Religious Celebration |
|   |  10/08 to 09/09 |  2010 |  NA |  Religious Celebration |
|  Election USA | 04/11  | 2008  | North America  | Major Poitical Event  |
|  USA National Day |  04/07 |  All | USA  |  Cultural Celebration |
|  French National Day | 14/07  | All  | France  | Cultural Celebration  |
|  Chinese National Day |  01/10 | All  |  China |  Cultural Celebration |
|  St. Patrick's Day |  17/03 |  All | NA |  Religious/Cultural Celebration |
|  Soccer Wolrd Championship | 11/06 to 11/07  | 2010  | All  | Major Sports Event |
|  Summer Solstice |  21/06 |  All | Nordic Countries Europe  | Religious/Cultural Celebration  |
|  Gay Pride NYC |  29/06 |  2009 | North America  |  Cultural/Social Event |
|   | 28/06  |  2010 |  North America |  Cultural/Social Event |
|  Olympic Games | 08/08 to 24/08 | 2008  | All  | Major Sports Event  |
|   | 12/02 to 28/02  | 2010  | All | Major Sports Event |
|  International Day of Commemoration in Memory of the Victims of the Holocaust |  27/01 |  All | NA  | Cultural/Social Event |
|  International Day for Women's Rights |  08/03 |  All | NA  | Cultural/Social Event |
|  Super Bowl |  03/02 |  2008 |  North America |  Major Sports Event |
|   |  01/02 | 2009  |  North America | Major Sports Event |
|   |  07/02 | 2010  |  North America | Major Sports Event |


### 4. Methods:
1. Finalize the dataset of the dates that will contain the name of the events, the dates for the 3 years (2008 to 2010) we have data on.
2. We delimit continents Europe, Asia, North America, Australia, Africa and South America by latitudes and longitudes.
3. We define each user’s origin by the continent his home is located in.
4. We plot the distribution of how far people travel from their home.
5. For each special event and each continent, we find how far from their home people tend to travel. 
6. We then calculate the ratio between the two distributions and display it using appropriate visualization the modification of mobility per continent on those special days. Thus, we compare travel and mobility patterns on the events considered compared to the rest of the year.
7. Analysis of our results and conclusions.

### 5. Proposed Timeline:
- 28/11-30/12 : Finalize the dataset containing the major events
- 28/11-30/12 : Delimit the continents in terms of latitude and longitude
- 01/12-04/12 : Plot the distribution of how far people tend to travel from their home
- 05/12-08/12 : Plot the distribution of how far people tend to travel from their home on the special dates and on each continent
- 09-/12-12/12 : Plot the ratio between the two distributions
- 13/12-14/12 : Analysis and conclusion on results
- 15/12-18/12 : Make the report
- 19/12-23/12 :  Shoot the 2 min video 

### 6. Organization within the team:
- Pauline :
  - Delimit the continents in terms of latitude and longitude
  - Plot the ratio between the two distributions
- Clémence :
  - Create the dataset containing the major events
  - Plot the distribution of how far people tend to travel from their home
- Eloïse :
  - Plot the distribution of how far people tend to travel from their home on the special dates and on each continent
- All :
  - Analysis and conclusion on results
  - Make the report
  - Shoot the 2 min video

### 7. Questions for TAs:
- Does this extension seem feasible in the allocated time?
- Is our constructed dataset diverse enough?
- Is the ratio (in point 4.6) a good way to evaluate the impact of the events on the distributions?
- Is our proposal a coherent extension of the original paper?
