# Face_Recognition_System

 Face Detection is the process where the image, given as an input (picture) is searched to find any face, after finding the face the image processing cleans up the facial image for easier recognition of the face.
Facial recognition system is a technology capable of identifying or verifying a person from a digital image or a video frame from a video source. Generally, this technology works by extracting features from images of objects using computer vision.
It is also described as Biometric Facial recognition in the market which is a full proof solution to attendance taking for employees .Facial recognition features are also coming with age detection algorithms in mobiles. Recognition algorithms can be divided into two main approaches: geometric, which looks at distinguishing features, or photometric, which is a statistical approach that distills an image into values and compares the values with templates to eliminate variances. Some classify these algorithms into two broad categories: holistic and feature-based models. The former attempts to recognize the face in its entirety while the feature-based subdivide into components such as according to features and analyze each as well as its spatial location with respect to other features.
 
We expect that Facial recognition technology can be further enhanced by following way:
1.  	Implementing in Prior criminal activity interference by extracting sentiments
2.  	Crowd control in public places to prevent nuisance
3.  	Monitoring ICU (Intensive care unit) patients
4.  	Real time attendance and emotion monitoring in classrooms
# Tools Used:
We are implementing the FRS (face Recognition System) with the help of Raspberry pi 4.The RPi 4 runs on forthcoming Debian 10 Buster release. It comes packed with a powerful ARM processor, Ethernet, onboard Wi-Fi and Bluetooth, HDMI ports. Apart from that USB 3, dual HDMI, an upgraded CPU, and massive memory would provide much better performance to run applications. RPi comes with a dedicated GPU for image processing.
The script is written in python language. That contains Dataset collection, training data set and recognition of faces. Open CV 4 is used as the main library for face recognition. 
# Face Detection:  
We are using Haar cascade for detection of face detection. A Haar Cascade is basically a classifier which is used to detect particular objects from the source. The haarcascade_frontalface_default.xml is a haar cascade designed by Open CV to detect the frontal face.
# Face recognition:   
With the facial images already extracted, cropped, resized and usually converted to grayscale, the face recognition algorithm is responsible for finding characteristics which best describe the image.
We are using LBPH (Local Binary Patterns Histogram) for training data set for recognition. LBPH is a simple yet very efficient texture operator which labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number.
