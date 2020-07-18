Follow this below step:

Prerequisites : 
The requirement for this Python project is a webcam through which we will capture images.
 You need to have Python (3.6 version recommended) installed on your system, then using pip, you can install the necessary packages.

OpenCV – pip install opencv-python (face and eye detection).
TensorFlow – pip install tensorflow (keras uses TensorFlow as backend).
Keras – pip install keras (to build our classification model).
Pygame – pip install pygame (to play alarm sound).

 Firstly you have to install some packages/module:

a. pip install keras == 2.3.0
b. pip install tensorflow==2.0
c. pip install opencv-python
d. pip install opencv-contrib-python
E. pip install pygame==1.9.6



How To Run : 

1. Goto Command prompt to this folder location and then run
	pip install -r requirements.txt

2. python Driver Cam.py (To run your Project)

Step 1 – Take image as input from a camera.

Step 2 – Detect the face in the image and create a Region of Interest (ROI).

Step 3 – Detect the eyes from ROI and feed it to the classifier.

Step 4 – Classifier will categorize whether eyes are open or closed.

Step 5 – Calculate score to check whether the person is drowsy.

