# Kidnapped Vehicle
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

[//]: # (Image References)
[image1]: ./images/image01.png

## Basic instructions to run the code
1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
   * On windows, you may need to run: `cmake .. -G "Unix Makefiles" && make`
4. Run it: `./particle_filter`

## [Rubric](https://review.udacity.com/#!/rubrics/747/view) Points
### Here I will consider the rubric points individually and describe how I addressed each point in my implementation.
---

### Accuracy

#### 1. This criteria is checked automatically when you do ./run.sh in the terminal. If the output says "Success! Your particle filter passed!" then it means you’ve met this criteria.
Below there is a print of the simulator with the success message.
![alt text][image1]

### Performance

#### 1. This criteria is checked automatically when you do ./run.sh in the terminal. If the output says "Success! Your particle filter passed!" then it means you’ve met this criteria.
Sames as before.The time could be improved wth less particles, however I choose 800 to be sure that it will work under 100 seconds. I tried with 100 particles, a number that was sugested in the walk through, however did nor work.
![alt text][image1]

### General

#### 1. There may be ways to “beat” the automatic grader without actually implementing the full particle filter. You will meet this criteria if the methods you write in `particle_filter.cpp` behave as expected.

It does behave as expected. I had a lot of helpful tips on this [link](https://youtu.be/-3HI3Iw3Z9g). Moreover, I got helpful ideas on the forum, like [this](https://discussions.udacity.com/t/x-error-larger-than-max/445861), and on the slack channee.