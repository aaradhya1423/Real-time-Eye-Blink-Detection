#Real-time Eye Blink Detection using OpenCV

This Python script utilizes OpenCV to perform real-time face and eye detection, specifically focusing on detecting eye blinks once the detection is initiated. The script uses Haar cascades for detecting faces and eyes, providing visual feedback on whether eyes are open or closed.

#Requirements:
Python 3.x
OpenCV (opencv-python package)
NumPy (numpy package)

#How it Works
The script initializes the face and eye cascade classifiers from XML files.
It starts the video capture and continuously processes frames from the camera.
When the user presses 's', the script detects faces and eyes in the video stream.
If both eyes are detected as open, it displays "Eyes open!" on the screen.
If the eyes are not detected or if a blink is detected, it provides appropriate feedback.
Pressing 'q' stops the program and releases the camera resources.
