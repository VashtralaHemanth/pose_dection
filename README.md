Human Pose Detection using MediaPipe & OpenCV

This project detects and visualizes human pose landmarks from videos or webcam input using MediaPipe Pose and OpenCV.

🔍 Features

Detects 33 full-body pose landmarks

Works with webcam or video files

Real-time FPS display

Visualizes pose skeletons with OpenCV

3D landmark plotting using matplotlib

🧠 Tech Stack

Python 3.x

MediaPipe

OpenCV

NumPy

Matplotlib

📦 Installation (Google Colab Friendly)

!pip install mediapipe opencv-python matplotlib

▶️ How to Run

For Webcam

video = cv2.VideoCapture(0)  # Use webcam

For Video File

video = cv2.VideoCapture('your_video.mp4')

Then run the full script in your Python environment or Google Colab. Output will show:

Annotated frames with pose skeleton

Frame rate (FPS)

📁 Files

pose_detection.py – main script

pose2.mp4 – example video (optional)

🧪 Example Use Cases

Fitness & Yoga pose analysis

Gesture-based interaction

Sports training feedback

AI research and human motion modeling

🚀 Future Improvements

Add gesture detection (e.g., raise hands, jumping)

Action recognition (e.g., running, dancing)

Control avatars or UI using body movement

🤝 Acknowledgments

MediaPipe Pose by Google

OpenCV community
