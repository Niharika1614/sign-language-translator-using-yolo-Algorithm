
# 🖐️ Sign Language Translator using YOLO Algorithm

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![YOLO](https://img.shields.io/badge/YOLOv8-Ultralytics-green)
![Streamlit](https://img.shields.io/badge/Streamlit-Web_App-red)

---

## 📌 Overview
This project is a **Bi-Directional Sign Language Translator** built using **YOLOv8 (You Only Look Once)** for real-time gesture detection.  

✅ **Sign → Text → Speech**  
✅ **Text → Sign (with voice input)**  

The app recognizes sign language gestures from a **webcam feed**, converts them into **text** and **speech output**, and also translates **typed or spoken text** into sign language animations/images.

---

## 🚀 Features
- ✅ Real-time **Sign Detection** using YOLOv8
- ✅ Converts **Signs → Text → Speech**
- ✅ Converts **Text/Voice → Sign Language**
- ✅ User-friendly **Streamlit Web Interface**
- ✅ Lightweight, Fast & Accurate

---

## 🛠️ Tech Stack
- **Python**
- **YOLOv8 (Ultralytics)**
- **OpenCV**
- **Streamlit**
- **PyTTSx3** (Text-to-Speech)
- **SpeechRecognition**
- **PyAudio**

---

## 📂 Project Structure
```

Sign Language/
│
├── images/               # Images for training/testing
├── runs/                 # YOLO model runs
├── train/                # Training dataset
├── valid/                # Validation dataset
├── best.pt               # Trained YOLO model weights
├── model.py              # YOLO model loading & detection
├── run2.py               # Streamlit app for sign translation
├── requirements.txt      # Required Python packages
└── README.md             # Project documentation

````

---

## ⚙️ Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Niharika1614/sign-language-translator-using-yolo-Algorithm.git
cd sign-language-translator-using-yolo-Algorithm
````

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application

```bash
streamlit run run2.py
```

---

## 🖼️ Demo



## ✅ Future Improvements

* Add **more sign gestures**
* Multi-language support
* Deploy on **Streamlit Cloud** or **Mobile App**

---

## 🤝 Contributing

Contributions are welcome! Please open an **issue** or submit a **pull request** for any changes.



✅ Do you want me to **also update this README with a section for Text-to-Sign feature explanation** and **add sample image/video placeholders**?  
Or should I **give you a version with badges + clickable demo link placeholder** for a more professional look?
