👀 Face and Eye Detection

This project demonstrates real-time face and eye detection using OpenCV and Haar Cascade Classifiers with a webcam. It draws bounding boxes around detected faces and eyes in live video feed.

---

🚀 Features

• Real-time video capture from webcam
• Face detection using Haar Cascade Classifier
• Eye detection within detected face regions
• Bounding box visualization for faces and eyes
• Exit with key press for smooth closing

---

🛠 Tech Stack

• Python 
• OpenCV (cv2)

---

🔎 Workflow

1. Load Haar Cascade classifiers for face and eyes
2. Access webcam feed using VideoCapture
3. Convert each frame to grayscale
4. Detect faces using detectMultiScale
5. For each detected face, detect eyes inside region of interest
6. Draw bounding boxes around faces and eyes
7. Display live detection window until user presses q

---

🎯 Use Cases

• Real-time face tracking
• Eye blink detection systems
• Attendance and authentication systems
• Human-computer interaction projects
