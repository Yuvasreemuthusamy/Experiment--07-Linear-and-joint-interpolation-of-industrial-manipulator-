# Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-

###  DATE: 29-04-2024
###  NAME: Yuva Sree M 
###  ROLL NO : 212223230251
###  DEPARTMENT: AI-DS
### Aim :
      To understand linear and joint interpolation of industrial manipulator and develop a program for the same 
      
### Equipment Required: 
      Instrial manipulator , teach pendant and associated program platform 
      
### Theory 
    The following interpolation schemes are available in most of the robot controllers.
1. Joint interpolation
2. Straight line interpolation
3. Circular interpolation
4. Irregular smooth motions (manual lead through programming).
#### Joint interpolation: 
The controller determines how far each joint must move to get from the first point defined in the programme to the next. It then selects the joint that
requires the longest time. This determines the amount of movement for other axes such that all the axes start and stop at the same time. Joint interpolation is the default procedure for many commercial robots.

#### Straight-line interpolation: 
In this interpolation, the robot controller computes the straight-line path between two points and develops the sequence of addressable point along the path for the robot to pass through.

#### Circular interpolation: 
This requires the programmer to define a circle in the
robot’s workspace. This is done by specifying three points that lie along the circle. The controller constructs the circle by selecting a series of points that lie closer to the circle. These movements are actually small straight lines. If the addressable points are dense then the linear approximation becomes very much like circle.


#### Manual lead through Programming: 
When the manipulator wrist is moved by the programmer to teach, the movements consist of combination of smooth motion segments. These segments are sometimes approximately straight lines or curves or back and forth motions. These movements are referred as irregular smooth motions and an interpolation is involved to achieve them.




![Robot-interpolation-PTP-LIN-CIRC](https://user-images.githubusercontent.com/36288975/201615171-d0886aaa-8220-4b0c-8a1d-3d8a5c69c76a.png)

### Figure -01 difference between P-P , joint and linear interpolation 


### Program : 
DART studio screen shots for linear interpolation 


![WhatsApp Image 2024-04-29 at 08 12 25_992e7579](https://github.com/Yuvasreemuthusamy/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144870887/90e1c5a2-04a6-4ff2-b1c4-f884edb3c81f)


DART studio screen shots for joint interpolation 


![WhatsApp Image 2024-04-29 at 08 12 44_7b672bad](https://github.com/Yuvasreemuthusamy/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144870887/93cd6117-34bf-4480-9273-3dcbd71a2ea3)


### Robot movements 

![WhatsApp Image 2024-04-29 at 08 13 14_d0189c82](https://github.com/Yuvasreemuthusamy/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144870887/78d453a4-692a-4dbf-9712-61c5221359eb)

![WhatsApp Image 2024-04-29 at 08 13 26_955958ad](https://github.com/Yuvasreemuthusamy/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/144870887/5565697d-dd76-42b8-9215-e027a6a32f01)




### Results:

Thus linear and joint interpolation of industrial manipulator is studied and understood.

