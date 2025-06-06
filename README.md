# 👁️ Real-Time Face Detection using OpenCV

This project demonstrates a real-time face detection system using Python and OpenCV. It captures live video from a webcam, detects human faces using Haar Cascade Classifier, and highlights them with bounding boxes.

---

## 📌 Table of Contents
- [About the Project](#about-the-project)
- [Tech Stack](#tech-stack)
- [Setup Instructions](#setup-instructions)
- [How it Works](#how-it-works)
- [Result](#result)
- [Future Scope](#future-scope)
- [Author](#author)
- [License](#license)

---

## 🧠 About the Project

Real-time face detection is a key component in various AI applications such as surveillance, access control, and user interaction systems. This project leverages OpenCV’s pre-trained Haar cascade classifier to detect faces from live webcam feed efficiently.

---

## 🛠️ Tech Stack

- **Language**: Python 3.13  
- **Library**: OpenCV (`cv2`)  
- **Tools**: Jupyter Notebook / Any Python IDE  
- **Hardware**: Webcam-enabled system

---

## ⚙️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/face-detection-opencv.git
   cd face-detection-opencv
2. Install Required Packages

   ```bash
   pip install opencv-python
3. Run the Script

   ```bash
   python face_detection.py
4. Exit

   Press a to close the webcam window.

🔍 How it Works
-Loads Haar cascade XML file.

-Captures video from the default webcam.

-Converts each frame to grayscale.

-Detects faces using detectMultiScale().

-Draws green rectangles around detected faces.

    ```python
    faces = face_cap.detectMultiScale(gray_frame, scaleFactor=1.1, minNeighbors=5)
🖼️ Result

  ✅ Faces detected and outlined in real-time.

  ✅ Smooth performance on standard hardware.

![Screenshot 2025-06-06 225132](https://github.com/user-attachments/assets/6f2f49c6-543e-40b8-837b-9039e9c0d908)


🚀 Future Scope
-Add face recognition to identify individuals.

-Implement emotion or mask detection.

-Deploy to Raspberry Pi or Jetson Nano for edge computing.

-Upgrade to deep learning-based detectors (e.g., DNN or MTCNN).

-Build a GUI for user-friendly interaction.

🙋 Author

Jeyaguru J.

Department of B.Tech Artificial Intelligence and Data Science

📧 jeyaguru1507@gmail.com

🎓 AICTE Internship Project

📜 License

This project is open-source and available under the MIT License.

