# HAND-GESTURE-RECOGNITION-USING-CNN


# Researched based Project

## ABSTRACT
Communication plays a key role wherever we are. In order to make communication possible between people who are physically challenged people and normal people, different communities follow different hand sign languages. Every language differs in hand signal patterns. Present day technologies made it feasible to develop applications related to hand signal recognition.
In our project we have taken the American Sign Language into consideration.Our application detects hand movements in the view of display and translates the gesture into corresponding symbol. For training, the hand gesture detection model we used Convolutional Neural Network(CNN).


## EXISTING SYSTEM
The system takes a video of gestures as input through a web camera. These images are formed as a histogram using the opencv. After this these images are examined for relevant hand gestures.Then data augmentation is performed to eliminate noise and light which may result in  overfitting.Then the images are trained using keras CNN model. Later the augmented images are fed to Keras CNN model[2]. This model searches for the relevant hand gestures and converts them into relevant words.The output is in the form of a text of the recognised sign.


## PROBLEM STATEMENT
 As communication is a very important thing in existence there's a necessity of a machine which will help disabled people to speak with normal people effectively and convey exactly what they require. Hence there is a need for something that can act as a mediator and help to act as a bridge of communication.The problem is that not everyone can understand the linguistic communication and it would be difficult for communicating.The objective of the project is to make normal people understand the unique language that's utilized by disabled people to communicate through the hand signs. Within the existing system the key problem is overfitting of the machine learning model[1]. This is due to the data augmentation that is performed to remove the noise and blur of the image. To handle this problem we are using the gaussian filter for filtering the noise and to smoothen the image. 
 
 
 # SYSTEM DESIGN
 ![block](https://user-images.githubusercontent.com/42350361/125915003-b2592225-b7d0-43a1-8380-e2561cfdd03f.PNG)
