# SleepSafe Drive: Your Companion for Safe Driving

# Overview

SleepSafe Drive is a drowsiness detection system that utilizes computer vision techniques to monitor individuals' eye states through a webcam feed. Implemented in Python and Keras, the system identifies when a person's eyes remain closed for an extended period, indicating possible drowsiness or fatigue. Upon detecting drowsiness, the system triggers an alarm to alert the individual.

# Features:-

* Real-time Eye Monitoring: Continuously tracks the state of your eyes (open or closed) using advanced computer vision techniques.
* Auditory Alert System: Emits a sound alarm to alert the user when drowsiness is detected.
* Customizable Sensitivity: Allows users to adjust the sensitivity level for detecting drowsiness according to their preference.
* User-Friendly Interface: Designed with simplicity and ease of use in mind, providing an intuitive user experience.

 # Installation:-
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/PandeyRahulPandey/SleepSafe-Drive-Your-Companion-for-Safe-Driving
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the detect drowsiness.py script:
   ```bash
   python detect drowsiness.py

# Usage:-
1. Connect Your Webcam: Ensure your webcam is properly connected and functioning.
2. Run the Script: Execute the detect drowsyness.py script.
3. Adjust Settings: Customize the alarm threshold and other parameters as needed.
4. Maintain Eye Visibility: Keep your eyes clearly visible to the webcam for accurate detection.
5. Alert Notification: An alarm will sound when drowsiness is detected.

# Dependencies:-
* OpenCV: Utilized for image and video processing to monitor eye state.
* Keras: Employed for building and training the neural network models.
* NumPy: Provides numerical computing capabilities essential for data processing.
* Pygame: Used for playing sound alerts when drowsiness is detected.
