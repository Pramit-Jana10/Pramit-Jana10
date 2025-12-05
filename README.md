<div align="center">

# ✒️ **Signify – Signature Verification System**
AI-powered signature verification using **Flask**, **TensorFlow (ResNet50)**, and **MongoDB Atlas**.

---

## 🚀 Powerful • 🔐 Secure • ⚡ Fast

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-API-black?logo=flask)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Model-orange?logo=tensorflow)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-brightgreen?logo=mongodb)
![License](https://img.shields.io/badge/License-MIT-yellow)

</div>

---

## ⭐ **Features**

### 🔐 User Authentication
- User registration & login  
- Admin login with auto-created default admin from environment variables  

### 🧠 AI-Powered Signature Verification
- ResNet50 pretrained on ImageNet  
- Feature extraction + cosine similarity  
- Threshold-based match detection  

### 📂 Verification Logs
- Stored in MongoDB  
- Includes filenames, confidence score, match result, time, timestamp  

### 🛢️ Cloud Database (MongoDB Atlas)
- Environment-based configuration  
- Auto-admin creation  
- Secure cloud storage for users and logs  

### 🌐 REST API Support
- Login  
- Register  
- Verify  
- Fetch logs  

