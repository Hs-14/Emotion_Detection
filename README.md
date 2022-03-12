# Music-Recommendation-based-on-Emotion-Detection
It will detect emotion according to the facial expression and will Recommend a song based on detected emotion after the user hit the 'P' KEY on Keyboard. The user can stop the music by writing stop in IDLE 
## Brief Intro
The main goal of our project is to detect the emotions based on facial expressions into seven categories and recommend the music accordingly,using deep CNN. Our model is trained on the FER-2013 dataset which we got from ICML.In this dataset we have 35887 grayscale, 48x48 sized face images with seven emotions 
a. Angry 
b. Disgusted
c. Fearful 
d. Happy 
e. Neutral 
f. Sad  
g. Surprised

## Requirements
1. Opencv
2. Tensorflow
3. Pygame

## How to use?
Download the data.rar file from the drive link and extract it to the same folder as of main.py file
After extracting run main.py using IDLE, the program will run detecting the emotions. Get recommende
To play the recommended music press 'P' and to stop the music enter stop in IDLE.

Drive link : https://drive.google.com/file/d/1EVJGU710bxcRkjwK1yamrxtaKEIbrfdN/view?usp=sharing

## Algorithms Used
The haar cascade method is used to detect faces in each frame of the webcam feed.The region of image containing the face is resized to 48x48 and  passed as input to the Neural Network.The network outputs a list of soft scores for the seven classes of emotions and the emotion with maximum score will be displayed on the screen.


