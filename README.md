# Smart-Detection-Suite-Face-Eye-and-Vehicle-Movement-Detection
This project uses OpenCV and Python for real-time detection of faces, eyes, and moving cars. Face and eye detection are performed using live webcam feed, while moving car detection uses a video file. Haar Cascade Classifiers are applied for detection. Ideal for beginners exploring computer vision techniques.
📁 Project Description:
This project is a real-time detection system implemented in Python using OpenCV. It showcases three key detection capabilities:

Face and Eye Detection:
Utilizes Haar Cascade Classifiers to detect faces and eyes from a live webcam feed. The face is marked with a blue rectangle, while detected eyes are marked with green rectangles.

Moving Car Detection:
Detects moving vehicles from a pre-recorded video using a car-specific Haar Cascade Classifier. Detected cars are marked with yellow rectangles.

Right Eye Detection:
Captures a live webcam feed to detect the right eye of individuals, using a dedicated Haar Cascade Classifier for right eyes. Detected right eyes are marked with yellow rectangles.

🔧 Libraries and Tools Used:
Python

OpenCV

Haar Cascade XML files for face, eye, and car detection

🚀 How to Run:
Install OpenCV: pip install opencv-python

Download the required Haar Cascade XML files from the OpenCV GitHub repository or use the ones provided in the project directory.

Adjust the file paths for Haar Cascade XMLs and video file as needed.

Run each script individually for respective detections.

📝 Usage:
Press 'q' to quit the detection window.

Ensure the video feed or video file is available and accessible.
