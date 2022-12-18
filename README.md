# surfs_up

## Overview
The purpose of this analysis is to provide the investor with data surrounding the temperatures in Oahu in June and December, to determine if the surf and ice cream shop business is sustainable year-round. We used a query to access the SQLite database 

## Results
We extracted the June and December data separately, converted the data to a list, then created a dataframe from the list, and obtained the relevant data: 
June: 
![image](https://user-images.githubusercontent.com/115745142/208325536-996e30e1-0626-46f8-bd06-952b6f8107d9.png)
December: 
![image](https://user-images.githubusercontent.com/115745142/208325546-f3b51202-6e3f-47eb-af32-a8e33a931917.png)

- The data shows us that the mean temperature in June was 75 degrees, while the mean temperature in December was 71 degrees. 
- We can also view the max temperatures for each month (85 in June and 83 in December), to determine whether or not it is logical to have the business open during both months. Since the weather for both months is relatively mild (not drastically hot), that can also play a factor in whether or not the business stays open. 
- Perhaps the most interesting data point found during this comparison is the minimum temperatures, which were 64 degrees in June and 56 in December. 

## Summary
If we plot the data we extracted, we can easily see the variance between min and max temperatures, and where the most common temperatures fell. 

June: 
![image](https://user-images.githubusercontent.com/115745142/208325865-d2d52a2f-adbe-4d4d-9f01-abed290cbaea.png)

December: 
![image](https://user-images.githubusercontent.com/115745142/208325874-577261ee-ba18-4e41-9ae5-9e7a51092ed2.png)

The data shows the weather is relatively stable between the two months that were compared, and it seems like having the business open year-round would be ideal for profits. 
