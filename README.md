# Sign-Language-Detection

## inspiration
- In general, deaf people have difficulty expressing themselves in front of others. Natural vocal communication is not possible for them. 
- The majority of people are incapable of understanding sign language. The goal of this application is to fill the communication gap between normal people and deaf people. 

## What it does?
- The Sign Language Detection project will help deaf people while communicating. This could benefit people who are deaf or dumb, as they can communicate with others.
- The project is implemented for certain alphabets and special signs. Through the use of a webcam, a sign can be inputted into the computer, which then displays its meaning on the screen.

## How we built it?
- The application detects the alphabet or meaning of a hand gesture based on the captured hand gesture. 
- OpenCV is used to capture gestures using a webcam. OpenCV detects the gesture through a media pipe and processes it before being fed to the deep learning model.
- The LSTM model then processes the input and predicts the output based on the hand gesture in real-time. Besides detecting static signs like the alphabet, the model is capable of detecting dynamic signs like Danger, Wish, Wait, and Thief. 
- The Deep Learning model is further deployed on a webpage using the Flask framework. In order to design and style the webpage, HTML and CSS have been used. As a result, the user interface would be more interactive, which would make the application more usable. 

