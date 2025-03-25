# AlphaDigitNet

## 📌 Project Overview
AlphaDigitNet is an AI-powered **handwritten digit and text recognition system** that evolves through multiple versions:
- **V0.0**: Single-digit recognition via image upload
- **V0.1**: Multi-digit recognition via image upload
- **V1.0**: Digit & alphabet recognition via image upload
- **V1.1**: Digit & alphabet recognition via image upload or webcam
- **V2.0**: Full-text recognition from images, webcam, or user-drawn input

## 🛠 Tech Stack
### **Programming Languages & Frameworks**
- Python, JavaScript
- Flask (Backend API)
- HTML, CSS, JavaScript (Frontend)

### **Machine Learning & Deep Learning**
- TensorFlow/Keras
- OpenCV (Image processing)
- Scikit-Learn
- EMNIST/MNIST Dataset

### **Deployment & Tools**
- Docker (For containerization)
- GitHub Actions (CI/CD)
- AWS / Hugging Face Spaces (Future hosting)

## 📂 Project Structure
```
AlphaDigitNet/
│── app/
│   │── static/ (CSS, JS, assets)
│   │── templates/ (HTML pages)
│   │── uploads/ (Uploaded images)
│   │── routes.py (API endpoints)
│   │── model.py (ML model loader)
│   │── preprocessing.py (Image preprocessing)
│── model/
│   │── train.py (Training script)
│   │── test.py (Testing script)
│   │── saved_model/ (Trained models)
│── notebooks/
│   │── exploration.ipynb (Data exploration)
│   │── training.ipynb (Model training)
│── scripts/
│   │── data_preprocess.py (Preprocessing utilities)
│── docker/
│   │── Dockerfile
│── .gitignore
│── README.md
│── run.py (Main script)
│── requirements.txt (Dependencies)
│── setup.sh (Setup script)
```

## 🚀 How to Run the Project
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/IAMNEERAJ05/AlphaDigitNet.git
cd AlphaDigitNet
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Application**
```bash
python run.py
```

### **4️⃣ Access the App**
Open **http://127.0.0.1:5000/** in your browser.

## 📈 Future Enhancements
- ✨ Add real-time webcam-based recognition
- 🖊️ Handwritten text-to-digital conversion
- 🌍 Deploy as a cloud-based API

## 🤝 Contributing
Feel free to fork, improve, and submit PRs!

---
📝 **Author:** S. Neeraj Kumar  
📧 **Contact:** seeramneeraj2005@gmail.com 
