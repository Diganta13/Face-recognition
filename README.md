# Face-recognition
Detect face and recognise
There ae several steps for face recognition 

1. Background on face recognition
When you look at an apple, your mind immediately tells you: that is an apple. This process is recognition in the simplest of terms. So, what’s facial recognition? The same, but for faces, obviously.

But, the real question is: How can a computer recognize a face?
Take a real life example: When you meet someone for the first time, you don’t know who that person is at once, right? While he's talking to you or shaking your hand, you’re looking at his face: eyes, nose, mouth, skin tone… This process is your mind gathering data and training for face recognition.

2. Theory of OpenCV face recognizers
Thanks to OpenCV, coding facial recognition is now easier than ever. There are three easy steps to computer coding facial recognition, which are similar to the steps that our brains use for recognizing faces. These steps are:

Data Gathering: Gather face data (face images in this case) of the persons you want to identify.
Train the Recognizer: Feed that face data and respective names of each face to the recognizer so that it can learn.
Recognition: Feed new faces of that people and see if the face recognizer you just trained recognizes them.
It's that simple!

The LBPH Face Recognizer Process
Take a 3×3 window and move it across one image. At each move (each local part of the picture), compare the pixel at the center, with its surrounding pixels. Denote the neighbors with intensity value less than or equal to the center pixel by 1 and the rest by 0.

After you read these 0/1 values under the 3×3 window in a clockwise order, you will have a binary pattern like 11100011 that is local to a particular area of the picture. When you finish doing this on the whole image, you will have a list of local binary patterns.

3. Coding Face Recognition using Python and OpenCV
We are going to divide the Face Recognition process in this tutorial into three steps:
i)Prepare training data
ii)Train facerecognizer
iii)Prediction




