## KNN_Classifer_From_Scatch
The "KNN_Classifier_From_Scratch" script demonstrates the process of building a KNN classifier from the ground up, using both L1 and L2 distance metrics. The classifier was tested on a set of 3000 images and achieved an accuracy of over 50%. The script was compared with the scikit-learn KNN classifier and proved to be performing well. The code is open for modifications to enhance its accuracy.


## Class Animals classification using K-Nearest Neighbor classifier
In This Exercise , two  models   were used to check their performance . The models implement a method of selecting the closed neighbour from a dataset provided to give out the predicted values. The First model was implementation of K-nearest Neighbors implementation from scratch which used L1 and L2 (Manhattan ,  Euclidean) distances while the second model was from sklearn package .Based on the tests done , the model built from scratch performed well on both L1 and L2 distances than the model from sklearn.  L2 (Manhattan ) distance  performed very well  on normalized data thus was used to get the following scores .

From the training done using both distances , the best score value was  using the L1 distance norm when the data was normalized . The best score obtained from L1 distance was about 56.2% which was much better than using the model from sklearn package. This best score was obtained when the value of k was 7 hence making K=7 to be the best nearest neighbours to be used in the model.
Below are some of the diagrams that were used to select the model and distance to be used for final classification.
For the  model built from scratch  both L1 , L2  distances were used and also for sklearn package one trained over 3 , 5 and 7 as K values.




Bar Plot using L1 Distance Norm (best Score = 52.6% with k= 7)
![image](https://user-images.githubusercontent.com/43881878/215790704-99afcffe-6eb1-4f0f-93c4-80e8395f1f30.png)


Bar Plot using L2 Distance Norm (best score =49.50 with k = 7)
![image](https://user-images.githubusercontent.com/43881878/215790799-7609f581-ec5e-47dc-94ae-d5bf0ef1208f.png)


Bar Plot using Sklearn Inbuilt KNeighborsClassifier (Best Score 50.4 with k = 7)
![image](https://user-images.githubusercontent.com/43881878/215791459-ec90018f-e42c-4449-820e-f6c70126ac4f.png)


Using L1 as distance and Classifier built from scratch the following were the metrics for the best scoring model and k=7

Here are the Different Metrics Score from the model.
````
Accuracy Score is 0.5619047619047619
Recall Score is 0.5619047619047619
Precision Score is 0.6277182934325792
F-Score is 0.5739964477237577

````
The Confusion Matrix obtained for the predicted and real values was as follows.
````markdown
array([[109,  88,   3],
       [ 84, 109,   3],
       [ 46,  81, 107]])

````




The diagram below shows the Confusion Matrix obtained from the above data formatted.


![image](https://user-images.githubusercontent.com/43881878/215792271-345b3259-2afa-4780-9f42-74e6a397ec6d.png)



## YOu can check the article from here
https://medium.com/@stiveckamash/k-nearest-neighbors-algorithm-from-scratch-using-numpy-in-python-a-comprehensive-guide-for-f54b668db140
