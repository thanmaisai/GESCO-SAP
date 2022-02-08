# RevaHack21
The problem GESCO SAP solves
we have seen many physically impaired people face difficulty in communicating with other people as many people don't know sign language thus we decided to help out the physically impaired people by creating a Machine Learning model which can detect the gestures of the impaired person and then compare it with the training data thus identifying the gestures and converting them to text form(alphabets, numbers, key gesture, etc) and displaying the text over the screen, thus making it easy for impaired people to communicate with un-challenged people.

Challenges we ran into
We developed the project over a macOS platform where the TensorFlow framework is not yet modified to support M1 macs due to which we are not successfully able to train the ML model.
Even we had faced a few problems while searching for datasets to train the ML model as it was difficult in collecting appropriate data sets.
since are not able to use the TensorFlow framework on macOS we have limited our ML model to the identification of 0-5 numbers alone and couldn't include alphabet recognition with gestures.

Technologies we used
TensorFlow
OpenCV
Machine Learning
Python
Mediapipe
