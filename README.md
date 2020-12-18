
## ada-2020-project-milestone-p3-p3_bcd

# ___How do major social and cultural events affect human mobility?___

### 1. Abstract:
- One could expect that on event days like Christmas or New Year's Eve, our mobility patterns would break. By studying mobility on different type of events (religious, cultural and sport events) compared to the rest of the year we find that we don’t change much our usual patterns of mobility and neither our presence on social medias.


### 2. Research questions :
 - Do certain events specifically influence people’s mobility? 
 - Is people’s mobility due to important events different in each region of the world? 
 - How far from their homes do people tend to travel for specific and important events? 
 - Lastly, if there is a change in mobility, will it cause an increase or a decrease in the total check-ins count?
 
 ### 3. Proposed datasets:
 - Datasets containing checkins of location-based social networks Brightkite and Gowalla.
 - For the events, the eligible ones where religious celebrations, major sports events, start of a new year and national days. Due to the constraint of the temporal span of the Brightkite and Gowalla datasets, we selected events that happened between April 2008 and October 2010: Christmas and New Year Eve, the 4th of July and the Winter Olympic Games of 2010. We considered them as, respectively, religuous/cultural event, cultural event and major sport event.
 - For the regions of the world studied, after analyzing the dispersion of the checkins in the world, we decided to restrict our analyze to the USA (mainland), Western Europe and East Asia that we delimited using abstract rectangles and defined those rectangles using a bottom-left point coordinate and a top-right point coordinate.

### 4. Methods:
1. Create the event dataset for Christmas and New Year Eve, the 4th of July and the Winter Olympic Games of 2010 with their name, their type and the spanned period we will consider.
2. Delimit and create the regions of the world dataset for the USA, Western Europe and East Asia.
3. Find the home and the origin of each user. 
4. Study the distribution of distance travelled from home over the years and over the events :
  A) Compute the distribution of the distance from home travelled in general and in each region
  B) Compute the distribution of the distance travelled from home in each region and during each event
  C) Compute the probability to travel from home during these events in 2009
  D) Special analysis for the USA
5. Study the distribution of the number of checkins over the year 2009 (only year in common with the 2 datasets) and over the events :
  A) Compute the distribution of the number of checkins all year long in the world and per region
  B) Study of the outliers
  C) Compute the distribution of the number of checkins on the special days in the world and per region
6. Statistically analyse and draw conclusions

### 5. Proposed Timeline:
- Finalize the dataset containing the major events
- Delimit the continents in terms of latitude and longitude
- Compute the distribution of distance travelled from home, over the year and on the special days
- Compute the distribution of number of checkins daily, over the year 2009 and on the special days
- Analyze our plots, statistically test our hypotheses and conclude
- Make the report
- Shoot the 2 min video

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
