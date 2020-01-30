# Automobile-Consumer-Perception-Analysis

Customer association is a key driving factor for growth and higher sales in consumer driven industries. To be able to find these associations in social media, and to give insights based on these perceptions is what forms the business purview of this project. We have used Edmunds car forum to scrape data off in the entry level luxury car brands.  

# A more detailed outline of the project:
We are analytics consultant to a (i) brand manager, (ii) product manager and (iii) advertising manager. Our job is to give advice/insights to these individuals based on the analysis of social media conversations. We have used cars as they are good examples of a “high involvement” good.
1.	A web craper using Selenium to fetch messages posted in Edmunds.com discussion forums

2.	 Fetched around 4,000-5000 posts about cars from a General topics forum, here, the Entry Level Luxury forum https://forums.edmunds.com/discussion/2864/general/x/entry-level-luxury-performance-sedans

3.	Found the top 10 brands from frequency counts (stopwords were not counted). Replaced frequently occurring car models with brands so that from now on we  had to deal with only brands and not models
Task A: Identified top 10 brands by frequency. From the posts, calculated lift ratios for associations between the brands. 
Showed the brands on a multi-dimensional scaling (MDS) map

Task B: Insighted to brand managers from  analysis in Task A 
  
Task C: Identified 5 most frequently mentioned attributes of cars in the discussions

Task D: Business advices  to a (i) product manager, and (ii) marketing/advertising manager of these brands based on our analysis in Task C

Task E: Identified business implications for most aspirational brand in our data in terms of people actually wanting to buy or own
