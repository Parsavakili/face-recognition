# Face Recognition System

## 🔥 Real-time Face Recognition with OpenCV & Face_recognition

This project is a **real-time face recognition system** built using Python, OpenCV, and the `face_recognition` library. It allows you to detect, recognize, and register new faces dynamically.

## 🚀 Features
- **Real-time Face Detection** using OpenCV.
- **Face Recognition** with a threshold-based matching system.
- **Dynamic Face Registration**: If an unknown face is detected, you can register it with a name.
- **Automatic Image Quality Check**: Filters blurry images using sharpness detection.
- **Multi-face Support**: Detect and recognize multiple faces simultaneously.
- **User-Friendly Interface**: Displays detected faces with names in real-time.
- **Data Storage**: Saves known faces in a structured folder format for future recognition.

---

## 📌 How It Works
1. The system continuously scans for faces using your webcam.
2. If a recognized face appears, it displays the saved name.
3. If an **unknown face** is detected, it prompts the user to input a name.
4. The best image (based on sharpness) is saved for future recognition.
5. The new face is added to the dataset and recognized in future sessions.

---

## 🛠️ Installation & Setup
### Prerequisites
Ensure you have Python installed. Recommended: Python 3.7+

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Clone This Repository
```bash
git clone https://github.com/Parsavakili/face-recognition.git
cd face-recognition
```

### Run the Program
```bash
python face_recognition.py
```

---

## 🎯 Usage
- The camera will start detecting faces automatically.
- Recognized faces will be labeled in green.
- Unknown faces will be labeled in red.
- If an unknown face is detected, the system will prompt for a name.
- Press `Enter` after typing the name to register the face.
- Press `Q` to exit.

---

## 📂 Folder Structure
- `known_faces/` → Stores images of registered faces.
- `unknown_faces/` → (Optional) Can be used for logging unknown faces.

---

## 🎨 Preview
🚀 **Live Face Recognition in Action**

![image](https://github.com/user-attachments/assets/d572a98c-907c-4e85-8f0a-f109d3681e93)


---

## 🌟 Contributions
Feel free to contribute by submitting pull requests or raising issues! 🚀

### 🔧 Future Enhancements
- **Add Face Mask Detection**
- **Improve Matching Algorithm**
- **Support for Multiple Cameras**

---

## 💡 Credits
Developed by **Your Name**

### ⚡ Inspired by OpenCV & Face_recognition Library

**📌 Star this repository if you find it useful! ⭐**

### 🔗 GitHub Repository
[🔗 Face Recognition GitHub](https://github.com/Parsavakili/face-recognition)

