# Head-Pose-Estimation
Used the Media Pipe library to extract the face landmarks x, and y only.
Performed preprocessing step to make the model independent of the face position or scale using normalized data based
on position noise.
Trained a different regression model to estimate the values of the pitch, yaw, and roll.
Used rotation, translation, and projection of the axes on the image to visualize the direction the person islooking at.
Used the values of pitch, yaw, and roll to define the direction.
## Dataset:  
For this project, the dataset used is <a href=http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/Database/AFLW2000-3D.zip>AFLW2000 Dataset</a>, which consists of 2000 face images, with some information about them like the facial landmarks and the pitch, yaw, and roll values for each picture.

## Demo

https://user-images.githubusercontent.com/55801427/220383024-08b19d7d-f724-40fc-9f76-68cab661046b.mp4


## Solution:
1. Used the MediaPipe library to extract the face landmarks x,y.
2. Performed preprocessing step to make the model independent of the face position or scale using nomralize data based on position noise.
3. Trained a differnet regression model to estimate the values of the pitch, yaw, and roll.
4. Used rotation, translation, and projection of the axes on the image to visualize the direction the person is looking at.
5. Used the values of pitch, yaw, and roll to define the direction.  


## Libraries used:
1. MediaPipe
2. Numpy
3. OpenCV
4. Matplotlib
5. Pandas
6. Scikit-Learn

## Contributors
* Mohamed Badr (Me)
* <a href="https://github.com/mohamedaliELfeky" target="_blank"> Mohamed El-feky</a>
