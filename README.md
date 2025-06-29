💪 RepCounter – Real-Time Exercise Repetition Tracker using MediaPipe & OpenCV
RepCounter is a real-time fitness application developed in Python that uses MediaPipe and OpenCV to track body movements via webcam and count repetitions for various exercises. It's designed to help users monitor their workouts accurately without the need for external devices.

🏋️ Supported Exercises
💪 Bicep Curls

🏋️ Squats

🦵 Lunges

🤸 Jumping Jacks

🤜 Pushups

🚀 Features
📸 Real-time pose detection using webcam

🔢 Automatic rep counting for 5 common exercises

🎯 Accurate joint-angle-based tracking logic

📊 Live display of exercise name, rep count, and feedback

⚙️ Modular code for easy integration of new exercises

🧰 Technologies Used
Python

MediaPipe

OpenCV

NumPy

Matplotlib (optional for visualization/debugging)

📦 Installation
Make sure Python is installed, then install required packages:

bash
Copy
Edit
pip install mediapipe opencv-python numpy matplotlib

⚙️ How It Works
Pose Estimation: Uses MediaPipe to track body landmarks in real time.

Angle Calculation: Measures joint angles to determine movement depth and direction.

Repetition Logic: Detects a full rep based on entry and exit of angular thresholds.

Exercise Detection: Identifies the current exercise based on body movement pattern.

Real-Time Feedback: Displays the name of the exercise and ongoing rep count.

🙋‍♂️ Author
Mahuli Uniyal
B.Tech CSE | Passionate about AI + Fitness | Developer of RepCounter

