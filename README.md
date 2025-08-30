# 🎯 Face Recognition Attendance System

A **Machine Learning & Computer Vision** project using **Python, OpenCV, MediaPipe, and Random Forest** to automate attendance marking in real time.

---

## 📌 Project Overview
This project solves the problem of manual and error-prone attendance systems by using **face recognition**.  
The system detects faces, recognizes individuals, and automatically records:
- Login Time  
- Logout Time  
- Working Hours  
- Attendance Status (On-time / Late)  

All attendance records are stored in a **CSV file** for easy tracking.

---

## ⚙️ Technologies & Tools Used
- **Python** – Programming language  
- **OpenCV** – Real-time face detection  
- **MediaPipe** – Facial landmark extraction (468 points per face)  
- **Random Forest Classifier** – Face recognition model  
- **Pandas** – Data storage & processing  

---

## 🚀 Features
✅ Real-time face recognition  
✅ Contactless attendance system  
✅ Marks login, logout, and working duration  
✅ Tracks late/on-time attendance  
✅ Stores all records in CSV for analysis  

---

## 🛠️ Project Workflow
1. **Data Collection** – Extracted 468 facial landmarks per face using MediaPipe.  
2. **Data Preprocessing** – Normalized landmark values and stored in CSV.  
3. **Model Training** – Used Random Forest Classifier for face recognition.  
4. **Real-time Detection** – Integrated trained model with OpenCV.  
5. **Attendance Logging** – Marked login, logout, working hours, and stored records in CSV.  

---

Clone this repository  
   ```bash
   git clone https://github.com/Bhagyasri0912/Face-Recognition-Attendance-System-Using-Machine-Learning
