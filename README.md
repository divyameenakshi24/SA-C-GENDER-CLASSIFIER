# SA-C-GENDER-CLASSIFIER
# Algorithm
1.To classify the gender of a person use the DeepFace library. <br>
2.DeepFace library is developed based on deep learning algorithms. <br>
3.Import the deepface class from DeepFace library, cv2 class from openCv2 library and Matplot library according to the requirements. <br>
4.Load and display the imported image. <br>
5.Pass the image to DeepFace library and analyze the image to predict gender of a person. <br>
6.This prediction is stored in result variable. <br>
7.Finally print the prediction using this algorithm. <br>


## Program:
```
/*
Program to implement 
Developed by   : A.Divya Meenakshi
RegisterNumber :  212220230014
*/
```

## OUTPUT:
```
/*
1. CODE :
!pip install deepface
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt
img1=cv2.imread('girl1.jpg')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img1,actions=['gender'])
print("Gender : ",result['gender'])
img2=cv2.imread('boy1.jpg')
plt.imshow(img2[:,:,::-1])
plt.show()
result=DeepFace.analyze(img2,actions=['gender'])
print("Gender : ",result['gender'])

![image](https://user-images.githubusercontent.com/75235402/173230766-39ee9f6e-99f1-4250-b37a-7a6d3643d5f5.png)
![image](https://user-images.githubusercontent.com/75235402/173230824-70ffdfce-2685-4deb-9785-6267a11803fa.png)

*/
```

2. DEMO VIDEO YOUTUBE LINK:
 
https://youtu.be/9K5bMgWyQ8w


