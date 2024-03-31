Brand tracking is essential to a business because the information obtained from the process can be used in making business decisions involving marketing such as strategic advertising campaigns, they also help facilitate product development. Additionally, monitoring conversations helps businesses understand what is lacking with their customer support which can then be improved. It can also provide insights on possible competitors, major influencers, and understand their target market. Overall, it can help the business optimize their social media presence. The goal is to analyze how people feel about a brand, the key topics customers are talking about with regards to that brand, as well as get some insight into the demographics and overall engagement of people with the brand.

# Data 
We are collecting the data from twitter on a weekly basis for the month of February. February can be a valuable month for businesses to advertise deals and discounts, as well as release new products on account of the major events such as Super Bowl (12th Feb), Valentine’s Day (14th Feb.) and Mardi Gras (21st Feb.). This data is being pulled using the python package ‘tweepy’ and a standard twitter API. The tweets will be analyzed for 2 similar companies who belong to 3 distinct business categories, namely:

Starbucks/Dunkin's [Food industry]
Netflix/Hulu [Online Streaming Service]
Southwest/Delta Airlines [Airline company]

Once collected, sentiment will be analyzed for each brand. This provides an opportunity to describe the overall sentiment about major companies in each business category as well as compare the rivaling company’s current appeal based on customer opinions. 

Data collected for the purpose of this project would be: 
Tweets Text Data: Tweets posted over a period of time that is about a specific brand, including tweet time, number of views, retweets, likes, favorites, etc. Tweets will be pulled separately for each of the 6 brands. 
User Data: Data about the user who has posted the tweets in the tweets dataset, including follower counts, following count, listed count, verified status etc.
Brand Data: Data about the brand, the brand name, brand logo, bio, location, tagline, etc. This data is further categorized into the 3 types of industries that are being compared. 

The information pulled from the API is used to derive the following:
Sentiment Data: sentiment for each tweet and hence the overall brand.  This can contain dimensions such as sentiment comparison between the 3 different pairs, sentiment trends (positive, negative, neutral), and the general distribution of customer sentiment along with hierarchies like Tweet ID, Brand Name, Sentiment Score. 
Brand Comparison Data: to finally display the results of the analysis, this table stores the brand’s current popularity along with the sentiment difference when compared to its rivaling brand in the same industry. 



# Results
1. Sentiment analysis: A majority of the tweets overall were seen to be positive or neutral. This suggests that customers generally have positive or neutral experiences with the brands being analyzed. This information can be helpful for businesses to identify areas of improvement in their customer experience and also to focus on maintaining positive interactions with their customers

2. Engagement rates: Streaming industries received the highest engagement rates, followed by coffeehouses, and airlines received the lowest engagement rates. This information can help businesses to identify which industries have higher engagement rates and develop strategies to increase engagement on their social media platforms.

3. Correlation between engagement rates and tweet count: The reason for the trend in engagement rates shows a positive correlation with the count of tweets for each brand in its respective industry. This indicates that brands that have a higher volume of tweets tend to have higher engagement rates. This information can be helpful for businesses to increase their social media presence and engagement by creating more content.

4. Correlation between sentiment and revenue: On comparing the overall sentiment type of each company with their yearly revenue, we see some correlation wherein the companies with a higher percentage of positive sentiment seem to have higher revenue across all brands. This suggests that maintaining a positive brand image and customer experience can have a positive impact on revenue.

5. Identifying prospective influencers: Additionally, we can find out users who are prospective influencers for a brand based on their high follower count and positive sentiment towards a given brand. This information can be helpful for businesses to identify potential influencers for their brand and collaborate with them to increase their brand reach and engagement.

