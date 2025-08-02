# 📷 Haar Cascade Face Detection

This project demonstrates real-time **face detection** using the **Haar Cascade Classifier** in OpenCV.

It uses your system's webcam to detect human faces and draws rectangles around them in a live video feed.

---

## 🛠️ How It Works

- Loads a pre-trained Haar Cascade model for frontal face detection  
- Captures live video using your webcam  
- Detects faces in real-time and highlights them with rectangles  

---

## 🧪 Requirements

- Python 3.x  
- OpenCV  

Install OpenCV if you haven't already:

```bash
pip install opencv-python
```

🚀 Run the Code
1. Download the Haar cascade XML file: [haarcascade_frontalface_default.xml](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml)
2. Place it in the same directory as the Python script.
3. Run the script:
```bash
  python face_detect.py
```
You should see a window with your webcam feed and rectangles around detected faces.

📁 File Structure

```bash
haar-cascade/
├── face_detect.py                      # Main Python script
├── haarcascade_frontalface_default.xml # Haar cascade model
└── README.md
```

📝 Notes
- This method is fast and works well for basic face detection.
- It’s not suitable for detecting multiple object types or high-accuracy use cases.
