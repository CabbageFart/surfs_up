# Surfs up!
![image](https://user-images.githubusercontent.com/111661058/217638319-f3d3140f-f6c0-4ab0-91fb-575b0237e510.png)
## Surf and Shake Shop
  After my recent visit to O'ahu I discovered that I never wnated to leave. So after many ideas I settled on one that would make both my soul and body happy. A surfing and ice cream business! Now all I needed was the capital. I found an investor, W. Avy, that had the same love for both surfing and ice cream but he wasn't as ready as I was to dive head first. He wanted to know the avg temperatures for both June and December inorder to see if the business could operate year round.

## Results
### How's the Weather
  * I gathered data from the sqlite file produced by the weather stations located around the island. Nine stations in all.
  
  
  ![image](https://user-images.githubusercontent.com/111661058/217645737-f8cbadff-af65-46ac-8600-11fc703dfcb0.png)

  * Using my Python, Pandas, and SQLAlchemy skills I was then able to extract the temperatures from both June and December. With this formula you can few any month you wish by simply changing the 6(June) to any number 1-12.

![image](https://user-images.githubusercontent.com/111661058/217646359-26060931-8dd8-49d1-a209-a097a27eb4ed.png)

  * After gathering up this data I converted everything over to a pandas dataframe. Which in turn allowed me to easily get the max, min, and mean temps for both months.

![image](https://user-images.githubusercontent.com/111661058/217647086-3c22c5aa-0fc3-4809-a809-e11f556bdf66.png)

## Summary

  With this data W. Avy will be able to see that the temperatures do not deviate that much throughout the year. One analysis that I will have to do after this is to find how much it rains during particular months. The code I used to find the temps can be easily repurposed for this task.
  
![image](https://user-images.githubusercontent.com/111661058/217660034-7b68083a-1940-46aa-8d10-200f57b6f167.png)
  
Another more in depth query we could do is to search out specific dates and find temps/prcp with the station number that recordeed the info. Here is an example of the temps caode.

![image](https://user-images.githubusercontent.com/111661058/217660427-84c628b9-58ba-4a83-8faf-68039db457f3.png)
