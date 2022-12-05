# Processing of a recorded data of the moving car

## General Description

This repository contains a file called project.ipynb in which the entire code, explaination and outputs of the project are present in detail.
 
 There is also a folder called Dataset2022 which contains the dataset of recordings of a moving car. The recordings are taken by 2 types of lidar sensors, 1 radar sensors and a camera. The folder also contains ground truth data which refers to the bounding box the containing car. The content of this folder is described in detail inside project.ipynb.

The objectives of this project are as follows:-

1.  Plot a 3D scatter plot of the recordings from each lidar and radar sensor.
2.  Plot a 3D bounding box inside the plot using the given ground truth data.
2.   Seperate the points inside the bounding box from outside.
4.   Calculate the number of points inside the bounding box.
5.   Create a plot of the no. of points inside bounding box vs the distance of the car from the sensor. This plot should be created for both lidar sensors.

## Dependencies
* Python 3.10.4
* Python Packages: NumPy, Matplotlib, plotly, opencv-python

## Problems and solutions
**Problem:** You might see an error similar to 'Mime type rendering requires nbformat>=4.2.0 but it is not installed', the key word here is 'nbformat'. 

**Solution:** 
1. Install or update nbformat
   * python 3.0 :- $ pip3 install nbformat
   * python 2.0 :- $ pip install nbformat
2. Restart the notebook after installation

## Results
* The output of the first three objectives is as follows
 ![blick frame 80 img1](https://user-images.githubusercontent.com/67382565/205645668-5a096b5b-2031-4537-a812-d59c74f83e74.png)
 ![blick frame 80 img2](https://user-images.githubusercontent.com/67382565/205645777-8444f06a-84de-40fa-8fcc-203fd80b1c07.png)

 The points inside the bounding box are coloured blue and the points outside the bounding box are coloured green. This output is from Velodyne Puck lidar sensor. We can see that the data represents the trunk of the car.

 * The output of the objectives 3 and 5 is as follows
  ![both sensors graph](https://user-images.githubusercontent.com/67382565/205646922-26a171ef-a962-429e-9fdc-869ec0079e52.png)

The name of lidar sensors is BlickfeldCube
1 and Velodyne Puck.