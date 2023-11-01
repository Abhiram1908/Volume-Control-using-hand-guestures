# Volume-Control-using-hand-guestures
 The Aim of this project is to develop a real time Gesture Volume Control System. This paper explains a model that is useful in controlling Audio volume of system with the help of hand gestures. We have achieved 95% of accuracy using Media pipe’s technology and Machine Learning.
As a first step we try the hand detection based on available database of OpenCV. Then for capturing live hand of Camera the initialization has been done. The two gesture detection like palm and fist by green line which is trained by integral images.
The second step is the extracted image gestures which are compared with stored positive-negative integral image dataset and perform finger tip tracking by contour detection. 
The third step Mediapipe locate the palm and detect the 21 hand Landmarks according to Action. Mediapipe tracks the action between thumb and index finger and give command to Pycaw to maximize or Minimize the audio.
