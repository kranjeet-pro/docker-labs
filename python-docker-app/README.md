# 🚀 Python Docker App (Flask + Nginx)

This is a simple multi-container application built using **Flask (Python)** and **Nginx**, containerized with Docker and managed using Docker Compose.

---

## 📌 Project Overview

* Flask application running on port 5000
* Nginx acting as a reverse proxy
* Docker used for containerization
* Docker Compose used for multi-container setup

---

## 🛠️ Tech Stack

* Python (Flask)
* Docker
* Docker Compose
* Nginx

---

## 📁 Project Structure

python-docker-app/
│
├── app/
│   ├── app.py
│   ├── requirements.txt
│
├── nginx/
│   └── default.conf
│
├── Dockerfile
├── docker-compose.yml
└── README.md

---

## ▶️ How to Run the Project

### 1. Clone the repository

git clone https://github.com/YOUR-USERNAME/python-docker-app.git

### 2. Go to project directory

cd python-docker-app

### 3. Run using Docker Compose

docker compose up --build

---

## 🌐 Access Application

Open browser:

http://localhost

---

## 🧠 Key Concepts Learned

* Containerization using Docker
* Multi-container setup using Docker Compose
* Reverse proxy using Nginx
* Service-to-service communication (nginx → app)

---

## 💡 Future Improvements

* Add CI/CD using GitHub Actions
* Deploy on AWS EC2
* Add logging & monitoring

---

## 👨‍💻 Author

Ranjeet Singh
DevOps Enthusiast 🚀
