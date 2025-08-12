
# Face Detection App using OpenCV Haar Cascade Classifier

This is a simple **real-time face detection** application built with **Python** and **OpenCV** using the **Haar Cascade Classifier**.  
It captures live video from your webcam and detects faces, drawing green rectangles around them.

---

## 📌 Features
- Real-time face detection using webcam
- Pre-trained Haar Cascade model
- Easy to run and lightweight
- Works on most devices with Python & OpenCV

---

## 🛠️ Technologies Used
- **Python 3**
- **OpenCV (cv2)** library
- **Haar Cascade XML Model** (from OpenCV)

---

## 📂 Project Structure
```

.
├── face\_detection.py         # Main Python script
├── README.md                 # Project documentation
└── haarcascade\_frontalface\_default.xml  # Haar Cascade model (optional, OpenCV includes it)

````

---

## 🚀 How to Run

### 1️⃣ Install dependencies
```bash
pip install opencv-python
````

### 2️⃣ Run the application

```bash
python face_detection.py
```

---

## 📷 Output Example

When you run the app, your webcam feed will appear with a green rectangle drawn around any detected faces.


---

## 💡 Future Improvements

* Add eye and smile detection
* Build a GUI version using Tkinter or Streamlit
* Save detected face images
* Improve detection accuracy using DNN models

---

### 👤 Author

Developed by Shaik Muhammad saif 
```
