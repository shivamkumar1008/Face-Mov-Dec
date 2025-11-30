
# 🧠 Face-Mov-Dec
### A deep-learning powered system for real-time facial movement detection and analysis

Face-Mov-Dec is a lightweight computer-vision project designed to track and analyze facial movements in real time using **OpenCV**, **MediaPipe**, and **Python**.

---

## 🚀 Features
- Real-time webcam face detection  
- Facial landmark extraction using MediaPipe  
- Movement analysis for eyes, mouth, and head position  
- Fast & lightweight (CPU-friendly)  
- Modular and easy to extend  

---

## 🛠️ Tech Stack
- Python 3.x  
- OpenCV  
- MediaPipe  
- NumPy  

---

## 📁 Project Structure
```
Face-Mov-Dec/
│
├── main.py               # Main file for running detection
├── movement_utils.py     # Functions for face landmark & movement analysis
├── requirements.txt      # Dependencies
└── README.md             # Documentation
```

---

## 📥 Installation
### 1️⃣ Clone the repository
```bash
git clone https://github.com/shivamkumar1008/Face-Mov-Dec.git
cd Face-Mov-Dec
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

---

## ▶️ Run the project
```bash
streamlit run streamlit_app.py
```

---

## 📸 How It Works
1. Webcam video captured through OpenCV.  
2. MediaPipe detects 468 facial landmarks.  
3. Movement analysis includes:
   - Eye blinking  
   - Lip/mouth movement  
   - Head tilt/orientation  
4. Output rendered on video feed in real time.

---

## 📦 Dependencies
```
opencv-python
mediapipe
numpy
```

---

## 🤝 Contributing
Pull requests are welcome! Feel free to submit improvements or fixes.

---

## 📜 License
MIT License  
