# Music-Recommendation-based-on-Emotion-Detection
It will detect emotion according to the facial expression and will Recommend a song based on detected emotion after the user hit the 'P' KEY on Keyboard. The user can stop the music by writing stop in IDLE 
## Brief Intro
The main goal of our project is to detect the emotions based on facial expressions into seven categories and recommend the music accordingly,using deep CNN. Our model is trained on the FER-2013 dataset which we got from ICML.In this dataset we have 35887 grayscale, 48x48 sized face images with seven emotions:
1. Angry
2. Disgusted
3. Fearful
4. Happy
5. Neutral
6. Sad
7. Surprised

As per the emotion detected over a short period of time, it will recommend song accordingly from the following 4 categories:
1. Happy
2. Sad
3. Energetic
4. Calm

## Requirements
1. Opencv
2. Tensorflow
3. Pygame

## How to use?
Download the data.rar file from the drive link and extract it to the same folder as of main.py file
After extracting run main.py using Python, the program will run detecting the emotions.
To play the recommended music press 'P' and to stop the music enter stop in Terminal.

Drive link : https://drive.google.com/file/d/1EVJGU710bxcRkjwK1yamrxtaKEIbrfdN/view?usp=sharing

## Algorithms Used
The haar cascade method is used to detect faces in each frame of the webcam feed.The region of image containing the face is resized to 48x48 and  passed as input to the Neural Network.The network outputs a list of soft scores for the seven classes of emotions and the emotion with maximum score will be displayed on the screen.

## Contributors
1. Harsh Verma (2nd year EE btech)
2. Nishir Agrawal (2nd year EE btech)
3. Kartik Aggarwal (1st year EE btech)
4. Mimat Singh (1st year EE btech)
