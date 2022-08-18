# Bikesharing with NYC Citibike Data from 2019

This data is solely from August 2019. Tableau presentation can be found in https://public.tableau.com/app/profile/miranda.jimenez/viz/BikesharingCitibikeproject/FinalPresentation?publish=yes

## Overview

The purpose of this project was to analyze the bikeshare data from CitiBike in New York City and give a presentation to investors interested to begin a bikeshare program in Des Moines, Iowa. Although New York and Des Moines are vastly different, this analysis can help in answering a few key questions:

- Who uses bikeshare programs?
- What general area of a city sees the most bikeshare usage?
- Which hours of the day are bikes used the most and least?

## Results

First, let's look at who might bikeshare appeal to.
![image](https://user-images.githubusercontent.com/104941338/185016958-2a9b17fa-6206-49aa-848c-b43f8f45eafa.png)
In the image above you can see 3/4's of the 2,344,224 customers (number of customers will vary as Des Moines is much less populous than New York city) are **subscribers** meaning they are regular bikeshare clients thus, giving a clear idea on the amount of stable income bikeshare has. Furthermore, one can infer that customers are predominantly male and roughly 1/4 of the customers are female as shown in the "Gender Breakdown" graph. 

![image](https://user-images.githubusercontent.com/104941338/185019787-9e0ba9dc-6a4b-410c-af98-43f95952dc10.png)

In the map above you can see the bike stations where recorded bike trips started. The size of the circle indicate the relative number of trips started at those locations. The same goes for the color of the circles, the bluer the tinge, the lower the count, the more red the tinge, the higher the count. It is apparent that the buld of the bike trips are starting in the bustling commercial heart of Lower Manhattan thus bike usage is lower in less densely packed surrounding neighborhoods.

![image](https://user-images.githubusercontent.com/104941338/185184603-b166f0ee-d9e7-41d2-bb61-7ad497caeca7.png)

The bar graph displays the number of bike rides started during each hour of the day which were totaled across the month of August. As we can see, peak hours of usage are during working rush hours (8/9am to 5/6pm) and, the time period with the least amount of bike activity is between 1am and 4am. That would be the optimal time window for repairs, small management and even redistributions of the bikes to ensure complete machinery safety to the customers.

![image](https://user-images.githubusercontent.com/104941338/185198261-16ca0a09-d32e-4fe4-86c9-b756287122d2.png)

The heatmap also helps in looking at the weekly patterns of bike usage. This reinforces the idea of the bikes being used the most during work rush hours, introducing the idea of the bikes being used as a form of transportation for work rather than a faster way to tourist around a busy city.

![image](https://user-images.githubusercontent.com/104941338/185202128-195be466-d209-4dee-bb3a-c628ddd9b7d8.png)

The line graph shows the average trip duration in minutes with the number of rides happening. For example, according to the graph above the most frequent trip duration of a bike ride is 5 minutes meaning that, repairs/maintainance will not be required often saving money on repairs.

![image](https://user-images.githubusercontent.com/104941338/185204971-12136dc4-2400-4d84-b73b-99d065b70993.png)

To take this a little further, the heatmap and line graph above are the same as previous but these ones are divided by gender. As stated earlier, a large portion of the demographic are male and these graphs further reinforce that idea. Additionally, even though there's a much larger number of male customers than female customers, the bike usage pattern; of peaking during working rush hours; are the same therefore, if we appeal to one (most likely male) it can also count as for appealing towards female customers as well. 

![image](https://user-images.githubusercontent.com/104941338/185280067-e3a38c2d-ffdd-477e-ad84-66ad13cefdac.png)

## Summary 

In conclusion, bikeshare is incredibly popular in busy metropolitan areas and where parking may be scarce. The user base is made up mostly of male customers providing a regular income to the project/program. Some research/outreach should be done to appeal to more female customers while maintaing the solid male customer base. Lastly, usage seems to be the busyest during morning hours.
Two additional visualizations that I'd suggest for further analysis are:
- The starting and ending points throughout the day hourly to have an idea for realocation if needed during maintainance hours. 
- Bike utilization with their ending points in order to see the location of the bikes are more in need for maintainance and prioritize those bikes first furing maintainance hours.    
