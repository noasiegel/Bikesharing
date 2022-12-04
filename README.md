# Bikesharing

Link to Tableau Public workbook: https://public.tableau.com/shared/JK5GX2KTF?:display_count=n&:origin=viz_share_link

## Purpose of Analysis

The purpose of this analysis is to determine baseline understandings and benchmarks of the bikeshare industry to have more information before creating a bikeshare option in a new city. By using existing data from CitiBike in NYC, we are able to see who uses bikeshare options, how they use the bikes, and much more. Because NYC is the largest metropolitan area that uses bikeshare, this gives us a great place to start to understand how to launch a similar idea in a smaller area.

## Results

Here we begin with the first page of the Tableau Story.

![Screen Shot 2022-12-04 at 3 24 12 PM](https://user-images.githubusercontent.com/110838228/205513741-02ef88b0-e091-42ea-aa2c-77d8693e767a.png)

In this screenshot you can see three visualizations: othe number of rides, customer type, and gender breakdown of customers. We can discern that most customers are male subscribers.


![Screen Shot 2022-12-04 at 3 25 39 PM](https://user-images.githubusercontent.com/110838228/205513790-20c2d49a-0d83-4b8d-a4e0-3bbf7718ee02.png)


This next screenshot depicts an hourly breakdown of trips by gender. The darker purple boxes show more trips, while the lighter purple boxes show less. We are able to toggle the menu between male, female and unspecified users. Right now, all three options are selected, and if we hover our mouse, we can see specific data associated with each box. Generally, the graph here shows that 6-8am and 4-7pm are the most popular times to use a CitiBike for both male and females. This is true for Monday-Friday, which makes sense because these are traditional hours of commute to and from work. It's no surprise that weekends see a steady usage of the bikes all day, presumably because less people are at work. 

![Screen Shot 2022-12-04 at 3 35 22 PM](https://user-images.githubusercontent.com/110838228/205514188-b4f6681a-52e3-49f2-b7b5-6db6ffaa6fc8.png)



Here, we can see a similar breakdown as the screenshot prior, but in the purple graph to the left, it is a combination of all genders in one. Here we can see the most popular times to take a trip on a CitiBike by hour. It looks like Thursdays from 5-7pm are quite popular no matter the gender. The blue graph shows us trips by gender by weekday with a filter option of user type. We can see here that there are many more users who are subscribers, especially males. Additionally, we can see that Thursdays are the most popular day among male subscribers to use CitiBike. For females, Saturday and Thursday are popular days.


![Screen Shot 2022-12-04 at 3 37 54 PM](https://user-images.githubusercontent.com/110838228/205514277-0d4d9b15-2b34-4dcb-a12a-030d20e62d9c.png)

Finally, our last dashboard in our story shows bike checkout times by trip and gender. The top line graph shows that as shorter trips, between the durations of 3 and 30 minutes, are the most popular. Trip numbers sharply decrease after that. The graph below shows a similar story, but by gender breakdown as well. Here we have all hours selected in the menu on the right, but that is completely toggleable. Similar to the top line graph, the most popular trip durations are proportionally distributed across genders, based on the amount of users.

## Summary

Overall, the results show us two major trends: one, males use bikesharing options more frequently, and are also more likely to be a subscriber to the service as opposed to a one-time user. Two, bikesharing is very popular during traditional commute hours of the weekday. This indicates that bikesharing is a viable option for many people to use in place of other public transit or a car. However, based on usage on the weekends, bikesharing is a widely used transportation option for leisure activities.

Two additional visualizations that I would recommend for future analysis include:

1. A map that shows common routes of bikes. This would include using start and stop longitude and latidude data. This would help us understand where to put pickup and dropoff places. 
2. A bike usage map that shows which bikes have the most usage to inform which bikes might need repair or reitrement.


