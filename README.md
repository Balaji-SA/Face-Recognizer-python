# Face-Recognizer-python
This is a python script with deep learning and LBPH (Local Binary Pattern Histogram)  to detect, train and recognize faces. Can be used in security cameras to detect suspicious faces by training the machine.

To know about LBPH, check out this link..
https://towardsdatascience.com/face-recognition-how-lbph-works-90ec258c3d6b


# Prerequisites
1.Python 3.0 >
2.Camera with atleast capability to capture 480P images
3.opencv library
4.PILLOW

# Steps to follow
1. Run dataset.py to capture atleast 30 images with the camera.
2. Run trainer.py to train the images captured with the cascades (xml file). Output -> trainer.yml
3. Run recognizer.py to detect the trained face with LPBH accuracy. The accuracy percentage may be low due to lightings and other qualities.Make sure that you stay in the legit position of your face.

