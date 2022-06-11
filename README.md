# Traffic-Road-Accident-Prevention-using-Deep-Learning

  
### Introduction  
  
The increasing number of automobiles on the road has increased the number of road accidents occurring on a daily basis at an alarming rate in today's fast-paced world. As more individuals own automobiles, the number of traffic accidents continues to rise. Research shows in America Poll found that 60% of adult drivers reported driving while drowsy in the past year. Survey data from the CDC indicated that one in every 25 adults 2 had fallen asleep behind the wheel in the past month.  
  
Drowsy driving significantly increases the risk of car accidents. Microsleeps are when a person dozes off for just a few seconds5, and when they occur while driving, it’s easy for the car to run off the road or collide with another vehicle. The damage from these crashes increases when they occur at high speeds.  
  
  
In this project, I have created a system that can track your eye movement and if you fall asleep then it will give you a warning with sound. This can prevent the accident  
  
---  
  
### Requirements  
Our model is implemented using TensorFlow. Required packages are listed below  
  
```  
cv2  
tensorflow  
tensorflow.keras.models  
numpy  
pygame  
```  
  
To install these packages, run  
``` pip install package-name ```  
  
---  
### DataSet  
- To train our model I have used data that is freely available online. It contains images of eyes in the open and closed states which everyone can access from [here](http://mrl.cs.vsb.cz/eyedataset )  
  
- we have trained our model with ***40,920*** open and closed images to get more accurate results  
  
  
  
![Flowchart drawio](https://user-images.githubusercontent.com/88913986/169628974-97233c4a-d40f-4044-8327-c842d0d059fb.png)


![before](https://user-images.githubusercontent.com/88913986/169628993-0e945aa5-8e0f-4209-bf7b-bbd004f53ae4.png)



![after](https://user-images.githubusercontent.com/88913986/169628997-497d96f4-aace-4904-8f33-2b6e0319c1ca.gif)

