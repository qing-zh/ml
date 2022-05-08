I deleted position and texture variables because I think the location of objects doesn’t matter in art works, and you can’t tell the texture of paintings in small pictures. 

According to the result of first iteration, the optimal k value should be in between 5 and 15. I tried different n_clusters values of 5, 8, 10, 13, 15 first. Based on the result of silhouette plots, I thought the optimal k value should be in between 8 to 13. 

Then I tried different n_clusters values from 8 to 15, and surprisingly, I got the best result when the n_clusters value is 14. 

<img width="473" alt="Screen Shot 2022-05-08 at 1 01 29 PM" src="https://user-images.githubusercontent.com/95714345/167307127-45878aa2-c6f3-4390-a594-4014678fcb03.png"><img width="468" alt="Screen Shot 2022-05-08 at 1 01 40 PM" src="https://user-images.githubusercontent.com/95714345/167307128-a414599f-98f6-4b7e-b646-e3b8e0499a79.png">
<img width="482" alt="Screen Shot 2022-05-08 at 1 01 48 PM" src="https://user-images.githubusercontent.com/95714345/167307130-07e3b30d-8270-41c7-a121-009117c8a4b8.png">
<img width="479" alt="Screen Shot 2022-05-08 at 1 01 59 PM" src="https://user-images.githubusercontent.com/95714345/167307131-b4fcc2f8-64af-4302-a920-cd860830f3d3.png">
<img width="475" alt="Screen Shot 2022-05-08 at 1 02 09 PM" src="https://user-images.githubusercontent.com/95714345/167307133-59656b37-6007-4c8d-b87b-b11831d2217b.png">
<img width="479" alt="Screen Shot 2022-05-08 at 1 02 18 PM" src="https://user-images.githubusercontent.com/95714345/167307134-3aa2b766-9643-48a2-bc6a-cb4188333d84.png">
<img width="475" alt="Screen Shot 2022-05-08 at 1 02 27 PM" src="https://user-images.githubusercontent.com/95714345/167307135-43f558e3-3d1a-4d3f-a331-f65762781f21.png">
<img width="476" alt="Screen Shot 2022-05-08 at 1 02 37 PM" src="https://user-images.githubusercontent.com/95714345/167307136-36a69e9d-9b1b-4e55-8ed9-9586c2882496.png">
