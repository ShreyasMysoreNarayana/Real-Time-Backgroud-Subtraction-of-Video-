# 🎥 Real-Time Background Subtraction System

🚀 A real-time computer vision system that detects and isolates moving objects in video streams using background subtraction techniques.

---

## 💡 Why This Project Matters

Background subtraction is widely used in:

- 🎯 Surveillance systems  
- 🚗 Traffic monitoring  
- 🧍 Human activity detection  
- 🎮 Augmented reality applications  

👉 This project demonstrates how to process live video streams and extract meaningful motion-based insights in real time.

---

## ⚡ Key Features

- 🎥 Real-time video processing using webcam input  
- 🧠 Background subtraction for motion detection  
- 👤 Object detection (face & body using Haar cascades)  
- 🔧 Noise reduction using morphological operations  
- 🌗 Works under varying lighting conditions  
- 🌐 Web-based output using Flask  

---

## 🏗️ System Architecture

```text id="xv9h2r"
Video Input → Frame Processing → Background Subtraction → Object Detection → Output Stream (Web UI)
```

## 🛠️ Tech Stack
- Python
- OpenCV
- Flask
- NumPy
- 
## ⚙️ Setup Instructions

1. Install Dependencies
```bash
pip install flask
pip install opencv-python
pip install numpy
```
2. Open Project in VS Code
- Open the entire project folder in VS Code
- Ensure Python environment is configured

## ▶️ How to Run

Step 1: Configure Camera
To use your default webcam, update:
```bash
cv2.VideoCapture(0)
```
👉 Use:
- 0 → Default webcam
- 1 → External webcam
- 
Step 2: Run the Application
```bash
python app.py
```

Step 3: View Output
- A local URL will appear in the terminal
- Copy and paste it into your browser

👉 You will see the live processed video stream

## 📊 Output
- 🎥 Real-time video feed
- 🟩 Highlighted moving objects
- 👤 Detected faces and bodies

## 🚀 Impact
- Demonstrates real-time video processing
- Applies computer vision techniques in practical scenarios
- Bridges backend processing with web-based visualization

## 🔮 Future Enhancements
- 🔍 Integrate YOLO for advanced object detection
- 📈 Improve accuracy under extreme lighting conditions
- ☁️ Deploy as a cloud-based video processing service
- 🎯 Add motion tracking and analytics

## 👤 Author

Shreyas Mysore Narayana

Data Scientist | Computer Vision Enthusiast | AI Engineer
