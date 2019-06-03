# Buoy-Detection-using-Color-Segmentation

## **PROJECT DESCRIPTION**

The aim of this project is to

Please refer to [Project Report](https://github.com/adheeshc/Buoy-Detection-using-Color-Segmentation/blob/master/Report/Final%20Report.pdf) for further description

### Preparing the Input

<p align="center">
  <img src="/Images/combined_hsl.png" alt="Input Prep">
</p>

<p align="center">
  <img src="/Images/homography.png" alt="Homography">
</p>

### Lane Detection Candidates



#### Hough Lines

<p align="center">
  <img src="/Images/hough.gif" alt="Detect Tag">
</p>

#### Histogram of Lane Pixels

<p align="center">
  <img src="/Images/histogram.png" alt="histo">
</p>


### Refining Lane Detection and Turn Prediction

<p align="center">
  <img src="/Images/histo.gif" alt="final_histo">
</p>


## **DEPENDANCIES**

- Python 3
- OpenCV
- Numpy
- Matplotlib
- Copy (built-in)


## **FILE DESCRIPTION**

- Code Folder/[Cropping.py](https://github.com/adheeshc/Buoy-Detection-using-Color-Segmentation/blob/master/Code/cropping.py) - This file is used for cropping out our original dataset
- Code Folder/[EM.py](https://github.com/adheeshc/Buoy-Detection-using-Color-Segmentation/blob/master/Code/EM.py) - This file is used for implementing the EM for a random set of datapoints
- Code Folder/[Project_3.py](https://github.com/adheeshc/Buoy-Detection-using-Color-Segmentation/blob/master/Code/Project_3.py) - This is the main file that implements the contours onto the buoys
- Code Folder/[(OPTIONAL) multivariate_gaussian.py](https://github.com/adheeshc/Buoy-Detection-using-Color-Segmentation/blob/master/Code/(OPTIONAL)%20multivariate_gaussian.py) - Here I implemented a 3D gaussian to fit the dataset

- Datasets folder - Contains 1 video input file, all the frames of the video and 3 folders containing images for Green, Yellow and Red Buoys 

- Images folder - Contains images for github use (can be ignored)

- Output folder - Contains output videos

- Report folder - Contains [Project Report](https://github.com/adheeshc/Buoy-Detection-using-Color-Segmentation/blob/master/Report/Final%20Report.pdf)

## **RUN INSTRUCTIONS**

- Make sure all dependancies are met
- Ensure the location of the input video files are correct in the code you're running
- Comment/Uncomment as reqd

- RUN Cropping.py if you want to create a new Dataset
- RUN EM.py if you want to implemenet EM from scratch for a randomly generated dataset
- RUN Project_3.py as is for Buoy Detection
- RUN (OPTIONAL) multivariate_gaussian.py if you want to test Buoy Detection it for a Multivariate Gaussian

