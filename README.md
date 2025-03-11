# 🐳 Dockerized Flask App

## 🚀 Introduction
Welcome to the **Docker-ITI-Flask** project! This repository contains a **Flask web application** that is fully containerized using **Docker**. The project is designed to demonstrate best practices for deploying Flask applications in a scalable and efficient manner.

## 🎯 Key Features
✅ **Flask-based Web App** - A simple yet powerful web application using Flask.  
✅ **Dockerized** - Easily deployable with Docker containers.  
✅ **Scalable & Portable** - Run the app seamlessly on any environment.  
✅ **Pre-configured Dependencies** - All required dependencies are included within the container.  

## 🛠 Installation & Usage
### Prerequisites
Ensure you have the following installed:
- **Docker** (latest version recommended)
- **Python 3.x** (optional for local execution)

### 🚀 Quick Setup
1️⃣ Clone the repository:
   ```bash
   git clone https://github.com/ahmedkhamees37/Docker-ITI-flask.git
   cd Docker-ITI-flask
   ```
2️⃣ Build the Docker image:
   ```bash
   docker build -t flask-app .
   ```
3️⃣ Run the container:
   ```bash
   docker run -p 5000:5000 flask-app
   ```
4️⃣ Access the application:
   Open your browser and go to **`http://localhost:5000`** 🎉

## 🔧 Running Without Docker
If you prefer running the Flask app without Docker:
```bash
pip install -r requirements.txt
python app.py
```

## 📌 Technologies Used
🔹 **Flask** - Lightweight Python web framework.  
🔹 **Docker** - Containerization platform.  
🔹 **Gunicorn** - WSGI server for running Flask in production.  

## 🤝 Contribute & Collaborate
We welcome contributions! Follow these steps to contribute:
1️⃣ Fork the repository.  
2️⃣ Create a new branch (`feature-branch`).  
3️⃣ Commit your changes.  
4️⃣ Push to the branch and submit a Pull Request.  

## 📜 License
This project is open-source and available under the **MIT License**. Feel free to use, modify, and share! 🚀

---
📌 **Created with passion by Ahmed Khamis Hassan.** 🎓 🐳

