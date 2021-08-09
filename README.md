# Bikesharing
## Overview
This analysis is to look at Citi Bike, a bicycle rental company in New York City, to get a better understanding of what a similar company can learn from the data they make publicly available. By looking at the month of August, we hope to get a good idea of how the business generally goes with a slight bent towards getting a feel for the target demographics to market towards and some understanding of when to expect certain things. 
## Results

![Screenshot1](https://user-images.githubusercontent.com/83182353/128652876-24fb879c-4aff-4d90-b2a3-f6c6280a9b58.png)

We start with the overly simple total number of trips take in August to show that there is enough business to make this a lucrative endeavor.

![Screenshot2](https://user-images.githubusercontent.com/83182353/128652885-04f76826-d477-4e3b-bff6-d790b425a669.png)

Next, we use color to get a feel for when is busy. Throughout the week, the busiest hours are seen to be before 9 AM and after 5PM, which lines up with the idea that commuters use the bikes and that they are the most plentiful source of business. We can also see that there are a few hours in the morning around 3 AM when there are significantly fewer customers, and therefore it would be a good time to do bike repairs. 

![Screenshot3](https://user-images.githubusercontent.com/83182353/128653030-d1769d21-21ee-4c42-8bab-4757f1719128.png)
![Screenshot3b](https://user-images.githubusercontent.com/83182353/128652908-aead5022-78b3-40c9-8e95-8d3f722096d4.png)

Another important breakdown to understand our target audience is gender. We easily see that males make up most of the business. By filtering this, we see that the one-time customers are nearly evenly likely to be male as to state gender as unknown. One possible reason for that is because tourists may prefer to leave as little personal information in an unfamiliar city.

![Screenshot4a](https://user-images.githubusercontent.com/83182353/128653048-688780c7-5911-40e8-abc2-3a29443727e7.png)
![Screenshot4b](https://user-images.githubusercontent.com/83182353/128653055-1bc0d254-f1f3-4db4-a586-16a451357d7c.png)
![Screenshot4c](https://user-images.githubusercontent.com/83182353/128653062-a087fcb6-9793-4d5c-88ed-56d2fe6f9305.png)

The male and female heatmaps are similar to the overall heatmap, showing that most of this group seem to be commuters using the bike to get to and from work with a currently unexplained spike in business Thursday evening. The unknown gender is the odd one out, with Saturday, starting around 11 AM, being the busiest day by far, Sunday being the easy second busiest. This makes sense with the idea that unknown gender seems to indicate a higher likelihood of the customer being a tourist. 

![Screenshot5](https://user-images.githubusercontent.com/83182353/128653237-a656ffdf-f0f6-4cd8-a7d4-e245f42836c8.png)
![Screenshot5b](https://user-images.githubusercontent.com/83182353/128653075-3a5d6de9-b71f-44e0-a082-85f5f4bdd51e.png)

The next visualization seems to confirm the theory above. Mal subscribers are most of the business and are more likely to go out during the week. Looking at just the customers, we have a shift where unknown is slightly more common than males. Although all three genders seem to follow the tourist frequency, the unknown gender has a significantly larger proportion on the customer side, which makes sense given our existing theory about tourists.

![Screenshot6](https://user-images.githubusercontent.com/83182353/128653083-d023fcfa-639a-4375-ac9b-78928d8aa2fe.png)

The last thing to consider for marketing is the age range to market your product for. The birth year of 1969 is an outlier that consists mostly of customers, leading to the reasonable assumption that those who don’t want to share their information will instead choose the number 69 for their own amusement. With this data point thrown out of consideration, we can easily see the trend that the younger age groups are more likely to be customers and especially subscribers. 

![Screenshot7](https://user-images.githubusercontent.com/83182353/128653088-e3470282-d14a-4a8d-83d4-fe1deb2c6b44.png)

For logistical reasons, it is a good idea to understand how long a rental is likely to be used. Looking at the line, the vast majority being returned within the first hour, and a large chunk of that is within the first 5 minutes of the rental being checked out. This seems to bode well.

![Screenshot8](https://user-images.githubusercontent.com/83182353/128653095-043324b9-bf87-4d8d-8b05-85b254f4d3fe.png)

Our last visualization looks at the trip duration sorted by gender. Males and females seem to follow the patter of most returns happening 5 minutes into the trip. The unknown gender has an equal chance to keep the bike for 20 to 30 minutes as to return it just 5 minutes into the trip. This lines up with the idea that unknow is more indicative of tourists, who are more likely to go for a scenic ride around town than use it to just get from one place to another. 
## Summary
 Most of those who use Citi Bike seem to be subscribed commuters, with most of them being male. More than a third of the ordinary customers left gender as an unknown, leading to the theory that they are tourists who don’t want to give any personal information. This is backed up by when they get bikes being the more tourist heavy weekends, and the fact that an unreasonably large number of these customers putting their birth year as 1969. With a decent understanding of the two main customer bases, it would be worth while to understand a little more about the geographics of both groups. Looking at the starting and ending locations, filtered to just subscribers and potentially further filtered to the hours when commuters are most often. For the other geographic visualization, it should be filtered to fust customers, maybe even just look at Saturday. It may also be beneficial to note where airports of other major transportation inroads that tourists are likely to use. Ideally, these maps would help understand where these demographics may be found and whether the bikes would need to be shifted to a different area for the weekend.
