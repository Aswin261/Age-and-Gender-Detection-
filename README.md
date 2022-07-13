# Age-and-Gender-Detection-

Objective :
To build a gender and age detector that can approximately guess the gender and age of the person (face) in a picture or through webcam.

About the Project :
In this Python Project, I had used Deep Learning to accurately identify the gender and age of a person from a single image of a face. I used the models trained by Tal Hassner and Gil Levi. The predicted gender may be one of ‘Male’ and ‘Female’, and the predicted age may be one of the following ranges- (0 – 2), (4 – 6), (8 – 12), (15 – 20), (25 – 32), (38 – 43), (48 – 53), (60 – 100) (8 nodes in the final softmax layer). It is very difficult to accurately guess an exact age from a single image because of factors like makeup, lighting, obstructions, and facial expressions. And so, I made this a classification problem instead of making it one of regression.

Additional Python Libraries Required :
OpenCV
   pip install opencv-python
argparse
   pip install argparse
The contents of this Project :
opencv_face_detector.pbtxt
opencv_face_detector_uint8.pb
age_deploy.prototxt
age_net.caffemodel
gender_deploy.prototxt
gender_net.caffemodel

Usage :
Open your Command Prompt or Terminal and change directory to the folder where all the files are present.
Detecting Gender and Age of face in Image Use Command :
  python agender.py --image <image_name>
Note: The Image should be present in same folder where all the files are present
Execute using python agender.py

![WhatsApp Image 2022-07-13 at 6 42 58 PM](https://user-images.githubusercontent.com/97616116/178742098-104ed9ad-f14d-42c7-827d-8b29ab9d8f20.jpeg)
