## Applications
This code can be used by drivers who tend to drive for a longer period of time and by students who study late at nights for exam 😉.

### Description

A computer vision system that can automatically detect driver drowsiness in a real-time video stream and then play an alarm if the driver appears to be drowsy.

### Algorithm

Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye:.

<img src="https://github.com/ashutosh1997/Drowsiness_Detection/blob/master/eye1.jpg">

### Condition

It checks 20 consecutive frames and if the Eye Aspect ratio is lesst than 0.25, Alert is generated.

#### Relationship

<img src="https://github.com/ashutosh1997/Drowsiness_Detection/blob/master/eye2.png">

#### Summing up

<img src="https://github.com/ashutosh1997/Drowsiness_Detection/blob/master/eye3.jpg">

Reference: https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/


### Working Example

<img src="https://github.com/ashutosh1997/Drowsiness_Detection/blob/master/drowsiness_detection.gif">
<video width="800" height="600" autoplay>
  <source src="https://github.com/ashutosh1997/Drowsiness_Detection/blob/master/drowsiness_detection.mp4" type="video/mp4">
</video>



### Execution
* First install all the requiremnets from requirements.txt file:
  dlib==19.17.0
  imutils==0.5.2
  numpy==1.17.0
  opencv-python==4.1.0.25
  pygame==1.9.6
  scipy==1.3.0

* Then, type:

```
python Drowsiness_Detection.py
```
