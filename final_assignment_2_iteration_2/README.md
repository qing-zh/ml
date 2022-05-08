While reviewing the false result, I noticed that the false results and correct results look similar because they are too pixelated, so I was thinking maybe it needs a more accurate input. So I changed the down-scaling factor. I tried downscaling 30% and 35%, and got the best result when downscaling 30%. 

I changed the mode of resize function to default because it didn't work well after I changed the down-scaling factor. Then I tried increasing the anti_aliasing_sigma value to make the images less pixelated. However it didn't work out. I also tried adding 3 layers to the nural network model. It performs better, but not as good as prc model. 


dims = (18, 42) # 30% of the original size![image](https://user-images.githubusercontent.com/95714345/167309365-3aa737cf-04b5-45fc-b557-426c96eb21d1.png)
dims = (21, 49) # 35% of the original size![image](https://user-images.githubusercontent.com/95714345/167309377-11185bd9-bb2b-4e21-8fa1-39c1980bd166.png)
