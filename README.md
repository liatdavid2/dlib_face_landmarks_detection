# Dlib face landmarks detection

What is Dlib?
It‘s a landmark’s facial detector with pre-trained models, the dlib is used to estimate the location of 68 coordinates (x, y) that map the facial points on a person’s face like image below.

Facial landmark points detection through Dlib's 68 Model:
There are mostly two steps to detect face landmarks in an image which are given below:

1. Face detection: Face detection is the first methods which locate a human face and return a value in x,y,w,h which is a rectangle.

2. Face landmark: After getting the location of a face in an image, then we have to through points inside of that rectangle.


<img src="https://user-images.githubusercontent.com/11797397/182599096-ec880ae1-90a0-49d3-ac32-13bc8237a923.png" width="300">
 iBUG300-W dataset was used.
 
The face detector is made using the classic Histogram of Oriented
Gradients (HOG) feature combined with a linear classifier, an image pyramid,
and sliding window detection scheme. 







https://user-images.githubusercontent.com/11797397/182602596-fc882ce9-053d-4e94-8b64-3ff29d16ce1d.mp4

Distinguish different parts of the face.

https://user-images.githubusercontent.com/11797397/182601597-f2caf58c-8b59-4861-bede-c1abb0ac4497.mp4

<!---https://user-images.githubusercontent.com/11797397/182599917-e423460f-0590-4082-99e4-91bb98a59246.mp4--->


