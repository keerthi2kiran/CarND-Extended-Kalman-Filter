# Extended Kalman Filter Project
Self-Driving Car Engineer Nanodegree Program

---

## Dependencies

* cmake >= 3.5
 * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools]((https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

## Basic Build Instructions

1. Clone this repo.
1.5. Extract the Eigen.zip file in its directory.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make` 
   * On windows, you may need to run: `cmake .. -G "Unix Makefiles" && make`
4. Run it: `./ExtendedKF path/to/input.txt path/to/output.txt`. You can find
   some sample inputs in 'data/'.
    - eg. `./ExtendedKF ../data/sample-laser-radar-measurement-data-1.txt output.txt`

## Results: 
Here are the results of the EKF. 
Dataset1: <br/>
Accuracy - RMSE:<br/>
0.0651665<br/>
0.0605376<br/>
0.543836<br/>
0.544203<br/>
![alt text](https://github.com/keerthi2kiran/CarND-Extended-Kalman-Filter/blob/master/Images/Dataset1.png "Dataset 1")<br/>

Dataset2:<br/>
Accuracy - RMSE:<br/>
0.185904<br/>
0.190417<br/>
0.474047<br/>
0.825168<br/>
![alt text](https://github.com/keerthi2kiran/CarND-Extended-Kalman-Filter/blob/master/Images/Dataset2.png "Dataset 2")<br/>

