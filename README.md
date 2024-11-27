# Driver_Drowsiness_Detection-using-Python
A safety mechanism designed to alert drivers when they show signs of drowsiness. It uses a webcam for data collection, a Raspberry Pi for data processing, and an alarm for audible alerts.

The system continuously monitors the driver’s eye movements and if he/she feels the sign of drowsiness(yawning or closing eyes) it triggers a loud alarm if the driver’s eyes remain closed for more than 10 seconds, thereby helping to prevent accidents.The system employs a deep learning framework and computer vision to detect the driver's face and analyze their state.

 It is designed to be user-friendly and can be incorporated into existing cars or installed as an aftermarket accessory. The system can also be implemented in compatible smart devices like laptops, smartphones, or smart media players in the vehicle. However, it’s important to note that the effectiveness of such systems can vary based on the specific vehicle and the conditions under which it is used.
### Hardware Configuration
- Webcam
- __Raspberry Pi__
- Buzzer

### Software Configuration
- Operating System    :- Windows 7/8/10 /Rasbian
- Server side Script  :- Python
- IDE                 :- Jupyter NoteBook
- Libraries           :- Opencv , Keras , Tensorflow , Pygame
- Technology          :- Python 3.6+

### Working

- Capture image/frame from webcam. 
- Detect and isolate face, creating a Region of Interest (ROI).
- Identify eyes within ROI.
-Feed eye data to classifier.
- Classifier categorizes eye state (open/closed).
- Calculate drowsiness score based on eye/mouth state.
- Continuously monitor driver's eyes via webcam.
- Transmit data to Raspberry Pi for analysis.
- Classifier flags prolonged eye/mouth closure.
- Activate alarm for driver alert.
- Alarm persists until driver shows attentiveness.
