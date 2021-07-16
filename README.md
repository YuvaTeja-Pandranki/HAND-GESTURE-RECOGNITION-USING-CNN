# HAND-GESTURE-RECOGNITION-USING-CNN


# Researched based Project

## ABSTRACT
Communication plays a key role wherever we are. In order to make communication possible between people who are physically challenged people and normal people, different communities follow different hand sign languages. Every language differs in hand signal patterns. Present day technologies made it feasible to develop applications related to hand signal recognition.
In our project we have taken the American Sign Language into consideration.Our application detects hand movements in the view of display and translates the gesture into corresponding symbol. For training, the hand gesture detection model we used Convolutional Neural Network(CNN).


## EXISTING SYSTEM
The system takes a video of gestures as input through a web camera. These images are formed as a histogram using the opencv. After this these images are examined for relevant hand gestures.Then data augmentation is performed to eliminate noise and light which may result in  overfitting.Then the images are trained using keras CNN model. Later the augmented images are fed to Keras CNN model[2]. This model searches for the relevant hand gestures and converts them into relevant words.The output is in the form of a text of the recognised sign.


## PROBLEM STATEMENT
 As communication is a very important thing in existence there's a necessity of a machine which will help disabled people to speak with normal people effectively and convey exactly what they require. Hence there is a need for something that can act as a mediator and help to act as a bridge of communication.The problem is that not everyone can understand the linguistic communication and it would be difficult for communicating.The objective of the project is to make normal people understand the unique language that's utilized by disabled people to communicate through the hand signs. Within the existing system the key problem is overfitting of the machine learning model[1]. This is due to the data augmentation that is performed to remove the noise and blur of the image. To handle this problem we are using the gaussian filter for filtering the noise and to smoothen the image. 
 
 
 ## SYSTEM DESIGN
 ![block](https://user-images.githubusercontent.com/42350361/125915003-b2592225-b7d0-43a1-8380-e2561cfdd03f.PNG)


## DATA FLOW DIAGRAM 
It represents the flow of data in a system graphically.The data flow diagrams have two parts, one is logical and the other is physical. 

![dataflow](https://user-images.githubusercontent.com/42350361/125915533-7dca7621-a639-478f-a65a-e7f0568f564f.PNG)


# TECHNOLOGIES

- Programming Language --> "PYTHON"
- Platform --> "Jupyter notebook"
- Libraries [OpenCV, Numpy, Matplotlib, Keras, Tensorflow]

# METHODOLIGIES:
- 	RGB to Grayscale conversion
- 	Gaussian Filters
- 	Otsu Thresholding
- 	Otsu Thresholding
- 	Training using CNN
- 	- Sequential model
- 	- Convolution layer
- 	-	Max Pooling: 
- 	-	Flatten
- 	-	Dense
- 	-	Dropout
- 	-	Optimizers
- 	-	Epoch

# DATA COLLECTION

For the implementation of the system, the foremost step is collecting a dataset.For this i created my own data set to avoid the problem of overfitting due to the similarities between the hand gestures. The data collection program is available in "collect_data.ipynb".
(or)
- train data link : https://drive.google.com/drive/folders/1cIRDggheNw7RPxiW6GQE28PInoVNpAHh?usp=sharing
- test data link : https://drive.google.com/drive/folders/1ULPJwwHtpmhkADJq5Niicso5uI0OONb9?usp=sharing


## TRAIN MODEL

training source is available in the file "train.ipynb"
 and 
the models that are trained by me --> "best_model_data.h5" & "best_model_data1.h5"

## PREDICTING THE GESTURE
 source code for predicting the gesture is available in the file "gesture.ipynb"



## CONCLUSION

Through this application i have  developed a hand gesture recognition system based on American Sign Language. This real-time system framework is implemented effectively with python and its libraries. First, i created a dataset of 1000 images containing hand gestures related to different classes corresponding to alphabets(A-Z) and numbers(0-9). Images are preprocessed for reduction of noise and blur using gaussian filter and otsu algorithm. These training images are given as input to an object recognition model which is built using convolutional neural networks. For the real-time prediction, frames are extracted from the live web-cam video streaming by the application



# FUTURE SCOPE

project can be extended with the following features:
- Conversion of hand gesture sequence into readable sentences in natural language.
- Conversion of hand gesture sequence into voice.



## REFERENCE

- [1] V. Elavarasi, N. Parkavi, Dr. B. Padmanaban & Dr. A. Sundar Raj, “ Hand Gesture Recognition and Word Conversion for Specially Challenged and Rehabilitated People” Journal of Shanghai Jiaotong University, Volume 16, Issue8, August - 2020.
- [2] Rosemary Antony, Stephy Paul, Silji Simon C, Scaria Alex, “Sign Language Translation System'' International Journal of Scientific Research & Engineering Trends, Volume 6, Issue 3, May-June 2020.
- [3] Basel A.Dabwan, “Convolution Neural Network-Based Sign Language Translation System” International Journal of Engineering, Science and Mathematics, Vol.9, Issue 6, June 2020.
- [4] Ankit Ojha, Ayush Pandey, Shubham Maurya, Abhishek Thakur, Dr. Dayananda P, “Sign Language to Text and Speech Translation in Real Time Using CNN Network” International Journal of Engineering Research & Technology, Volume 8, Issue 15, 2020. 
- [5] R Srinivas, "Sign Language Interpreter using Deep Learning" Alochana Chakra Journal, Volume IX, Issue VI, June/2020.
- [6] S.S.Kadam, Bhagyashree Sarode, Chinmayee Modak, Khushboo Singh, "Sign Language Translation System for Dumb and Deaf" IJRESM Volume-3, Issue-4, April-2020
- [7] Bhargav Hegde, Dayananda P, Mahesh Hegde, Chetan C, “Deep Learning Technique for Detecting NSCLC”, International Journal of Recent Technology and Engineering (IJRTE), Volume-8 Issue-3, September 2019, pp. 7841-7843
