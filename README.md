### **Face Emotion Recognition** 😃😢😠  

This project detects human emotions in real-time using OpenCV and a trained deep learning model. It identifies emotions such as **happy, sad, angry, neutral, surprise, fear, and disgust** from webcam video input.

## 🚀 **Features**
- **Real-time face detection** using OpenCV.
- **Emotion classification** using a pre-trained deep learning model.
- **Live video processing** from the webcam.


## 📂 **Project Structure**
```
face-emotion-reco/
│── emotiondetector.h5         # Trained model weights
│── emotiondetector.json       # Model architecture
│── emotiondetector.keras      # Keras model file
│── realtimedetection.py       # Main script for real-time detection
│── requirements.txt           # List of dependencies
│── trainmodel.ipynb           # Notebook for training the model
│── README.md                  # Project documentation (this file)
```

---

## 🎯 **How It Works**
1. **Face Detection**: Uses OpenCV’s `haarcascade_frontalface_default.xml` to detect faces.
2. **Feature Extraction**: Extracts the face region, resizes it to 48×48 pixels, and normalizes it.
3. **Emotion Classification**: The deep learning model predicts the emotion and overlays the result on the video feed.

---

## 🖼️ **Demo Output**
When you run the script, it will open your webcam and display a window with detected faces and their predicted emotions.

---

## 📝 **Future Improvements**
- Enhance accuracy with a larger dataset.
- Deploy as a web app using Flask or FastAPI.
- Integrate with mobile applications.

---

## 🤝 **Contributing**
Feel free to fork the repo, open an issue, or submit a pull request!

---

## 📜 **License**
This project is licensed under the **MIT License**.

