I tried different n_features values and noticed that the smaller the n_features is, the better performance for the training set, but worse for the test set. So I changed n_features to 2*18. I’ve also tried different value of ngram_range. Then I tried changing TfidfVectorizer values, but it didn't work out because I kept getting error messages.  

ngram_range=(1,3)
![image](https://user-images.githubusercontent.com/95714345/167310857-841dc6e8-4f38-48a7-831c-6b7a10619e43.png)

ngram_range=(1,2)
![image](https://user-images.githubusercontent.com/95714345/167310870-6ba705b0-d9eb-403c-9cd4-7981040c3173.png)
