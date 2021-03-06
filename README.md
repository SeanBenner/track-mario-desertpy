# Summary

This demo will be a basic introduction to computer vision and image processing. We'll go over how images are typically stored in Python libraries and how to manipulate them. We'll then apply some basic functions in OpenCV to find Mario inside an image, and then apply the same methods to video to track Mario in a SMB level playthrough, like this: https://www.youtube.com/watch?v=zo3U3a4nmyY

# Get started

### 1. Set up your environment for OpenCV
Clone [this repository](https://github.com/alkasm/cvpy) and follow the instructions in the `README` to create an Anaconda environment `cvpy` which will include everything needed like `OpenCV`, `matplotlib`, `numpy`, `Jupyter`, etc.

### 2. Clone this repository
Clone this repository to grab the Jupyter notebook and the video and image file.

### 3. Startup the Jupyter notebook or run the Python script
Once you've created the Anaconda environment simply start it up with
```bash
$ source activate cvpy
```
You should see `(cvpy)` added to the beginning of your terminal lines. To start up the Jupyter notebook you can browse to the folder containing this repo and start with
```bash
(cvpy) $ jupyter notebook 
```
and follow the tutorial, **or** if you prefer to be outside of Jupyter, run the included Python script with
```bash
(cvpy) $ python3 trackMario.py
```
