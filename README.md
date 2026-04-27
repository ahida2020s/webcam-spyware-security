## Webcam Spyware Security System

A Python-based desktop application designed to protect webcams from unauthorized access and spyware attacks using authentication, face recognition, and intrusion detection.

---

###  Features

-  Enable/Disable webcam at system level  
-  Email-based authentication (OTP/password)  
-  Face recognition authentication  
-  Intruder detection with video recording  
-  Email alerts with captured evidence  
-  Privacy scheduling (auto-disable webcam)  
-  Encoded security logs (Base64)  
-  User-friendly GUI (CustomTkinter)  

---

### Technologies Used

- Python  
- OpenCV  
- CustomTkinter  
- Face Recognition  
- SMTP (Email Services)  
- Windows Registry  

---

## 📁 Project Structure
webcam-spyware-security/
│
├── main.py # Main application
├── requirements.txt # Dependencies
├── README.md # Documentation
├── .gitignore # Ignored files
│
├── screenshots/ # Screenshots (optional)
│
├── security_logs.txt # Runtime logs (auto-generated)
├── privacy_schedules.json # Schedule storage
├── authorized_faces.npy # Face data
└── intruder.mp4 # Intruder recording

> ⚠️ Note:
> Runtime files and `.env` are not included in this repository for security reasons.

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/webcam-spyware-security.git
cd webcam-spyware-security
pip install -r requirements.txt

