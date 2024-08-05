# Motion Mentor

## Quick Start
```
$ pipenv install
```

If VSCode cannot find the path to the libraries installed in your virtual environment, try the following VSCode setting:
* Go to "Python › Analysis: Extra Paths"
* Add the path of libraries to the Extra Paths
* How to find the libraries path installed in your virtual machine is as follow.
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

## Quick Start

## Technologies
* Python
* MediaPipe
* OpenCV
