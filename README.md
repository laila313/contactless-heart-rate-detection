# contactless-heart-rate-detection
Contactless Heart Rate Detection using Green Channel Analysis and FFT - HeartWave Application
## 📌 Project Description
A contactless real-time heart rate detection application using webcam and 
green channel analysis. The system detects facial regions and extracts 
heart rate (BPM) using signal processing techniques.

## 🔍 How It Works
- 📷 Detects face using webcam in real-time
- 🟢 Extracts green channel signal from forehead and nose region
- 📊 Applies Butterworth bandpass filter to remove noise
- 🔢 Uses FFT (Fast Fourier Transform) to calculate BPM
- 📈 Displays live heart rate curve graph

## 🧠 Technology Used
- Python
- OpenCV
- PyQt5
- SciPy (Butterworth Filter)
- NumPy (FFT Analysis)
- LBP Cascade Face Detector

## 🚀 How to Run
```bash
python app.py
```

## 📊 Normal Heart Rate Range
- Normal: 60–100 BPM
- Athletes: 40–60 BPM
- Alert: Above 100 or Below 50 BPM

## 👩‍💻 Author
- laila313
