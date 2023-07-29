# Face_recognition
Face recognition is a computer vision technology that involves the automatic identification of a person's face, typically using a digital image or video feed. 

It is a widely studied area in computer science and has a diverse range of applications, including security and surveillance systems, access control systems, and personal identification.

In recent years, face recognition algorithms have improved significantly, thanks to the availability of large datasets and advances in deep learning techniques. 
These algorithms typically operate by extracting key features from the face, such as the distance between the eyes, nose, and mouth, and using these features to create a unique digital representation, called a face template or face signature.

# Model Architecture:
The model architecture used in this project consists of two main parts. The first part is a pre-trained InceptionV3 model that is used as a feature extractor. 
The second part is a fully connected layer with ReLU activation, which is added on top of the InceptionV3 model. 
The final output of this architecture is a feature vector for each image, which is obtained by passing the image through the InceptionV3 model and then through the fully connected layer.
This feature vector captures the important features of the image and can be used for Face recognition task.
