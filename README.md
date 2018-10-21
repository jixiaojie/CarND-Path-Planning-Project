# Path Planning Project Starter Code
Self-Driving Car Engineer Nanodegree Program

In this project I will utilize a Path Planning in the simulator. 

The goals / steps of this project are the following:

* 1.The code compiles correctly.
* 2.The car is able to drive at least 4.32 miles without incident.
* 3.The car drives according to the speed limit.
* 4.Max Acceleration and Jerk are not Exceeded.
* 5.Car does not have collisions.
* 6.The car stays in its lane, except for the time between changing lanes.
* 7.The car is able to change lanes
  
### [Rubric](https://review.udacity.com/#!/rubrics/1020/view) Points
### Here I will consider the rubric points individually and describe how I addressed each point in my implementation.  
  
#### 1.The code compiles correctly.
I compile project by following instructions:

1. mkdir build
2. cd build
3. cmake ..
4. make
5. ./path_planning
  
  
#### 2.The car is able to drive at least 4.32 miles without incident.
My car can drive 4.32 miles, here is a screenshot:
<div class="test">
<img src="Docs/img01.png" width="600" />
</div>

  
  
#### 3.The car drives according to the speed limit.
My car follows a speed limit of 50 MPH, here is a screenshot£º
<div class="test">
<img src="Docs/img02.png" width="600" />
</div>

  
  
#### 4.Max Acceleration and Jerk are not Exceeded.
My car take a total acceleration of 10 m/s^2 and a jerk of 10 m/s^3, here is a screenshot£º  
<div class="test">
<img src="Docs/img03.png" width="600" />
</div>

 
  
  

#### 5.Car does not have collisions.
My car does not actively collide with other vehicles,   
but other vehicles occasionally suddenly change lanes and collide.
  
  
#### 6.The car stays in its lane, except for the time between changing lanes.
My car can change lanes quickly.

 
  
#### 7.The car is able to change lanes.
My car can change lanes, here is a screenshot£º
<div class="test">
<img src="Docs/img04.png" width="600" />
</div>

  