This project demonstrates the integration of face recognition functionality into a Unity application using a Python server backend. The Unity application captures an image and sends it to the Python server, which performs face recognition and returns the result back to Unity.

Features:
Image Capture in Unity: The Unity application allows users to capture images using a webcam.

Face Recognition with Python: Upon receiving the captured image, a Python server performs face recognition using the face_recognition library.

Integration with OpenCV: The Python server integrates with OpenCV for image processing and visualization.

Communication between Unity and Python: Socket communication is used to send images from Unity to the Python server and receive the face recognition results back.

Usage:
Clone the Repository: Clone this repository to your local machine.

Setup Unity Environment: Open the Unity project and ensure that the necessary dependencies and packages are installed.

Run Python Server: Start the Python server script (server.py) on your local machine.

Run Unity Application: Run the Unity application and capture an image using the provided functionality.

Face Recognition: The captured image is sent to the Python server for face recognition. If a match is found, the server returns the result to Unity.

Visualize Results: Unity displays the face recognition result, indicating whether a match was found or not.
