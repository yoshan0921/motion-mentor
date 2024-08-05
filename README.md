# Motion Mentor

## Purpose of this project
The purpose of this project is to gain practical experience in real-time detection and inference processing on streaming data, utilizing MediaPipe, an open-source framework for building pipelines to perform computer vision inference.

## Features
TBD

## Screens
TBD

## Quick Start
```
$ pipenv install
```

If VSCode cannot find the path to the libraries installed in your virtual environment, try the following VSCode setting:
* Go to "Python › Analysis: Extra Paths"
* Add the library paths to Extra Paths. The following is how to check the paths of the libraries installed in the virtual machine. Add the path of the folder, not the library file itself. 
```
$ pipenv shell
$ python 
Type "help", "copyright", "credits" or "license" for more information.
>>> import cv2
>>> print(cv2.__file__)
[Library path installed in your virtual environment]
>>> 
```
* Also, make sure that the Python interpreter configured to run Python scripts in VSCode is that of the virtual environment.

## Technologies
* Python
* MediaPipe
* OpenCV
* NumPy
