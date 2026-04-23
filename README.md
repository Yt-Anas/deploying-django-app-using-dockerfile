# Deploying Django App Using Dockerfile

This repository demonstrates how to containerize and run a **Django web application** using **Docker**. It is a beginner-friendly project that helps understand how Django apps can be deployed consistently across different environments.

## 🚀 Project Overview

The project contains:

- A Django project setup
- A Django app named `demo`
- Dockerfile for containerization
- Requirements file for dependencies
- SQLite database for local development

Using Docker, this application can run on any system without manually installing Python or Django.

---

## 🛠️ Tech Stack

- Python 3
- Django
- Docker
- SQLite3

---

## 📂 Project Structure

```bash
deploying-django-app-using-dockerfile/
│── Dockerfile
│── requirements.txt
│── devops/
│   │── manage.py
│   │── db.sqlite3
│   │
│   ├── devops/          # Main Django Project
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── wsgi.py
│   │   └── asgi.py
│   │
│   └── demo/            # Django Application
│       ├── migrations/
│       ├── templates/
│       ├── admin.py
│       ├── models.py
│       ├── views.py
│       └── urls.py
⚙️ Prerequisites

Make sure you have installed:

Docker
Git
📥 Clone the Repository
git clone https://github.com/Yt-Anas/deploying-django-app-using-dockerfile.git
cd deploying-django-app-using-dockerfile
🐳 Build Docker Image
docker build -t django-app .
▶️ Run Docker Container
docker run -p 8000:8000 django-app
🌐 Access Application

After running the container, open:

http://localhost:8000
📌 Useful Docker Commands
Check Running Containers
docker ps
Stop Container
docker stop <container_id>
Remove Container
docker rm <container_id>
Remove Image
docker rmi django-app
🎯 Learning Objectives

This project is useful for learning:

How to create a Dockerfile for Django
How to build Docker images
How to run Django in containers
Basic deployment workflow
Portable application environments
🤝 Contributing

Contributions are welcome. Fork this repository and improve the project.

📄 License

This project is open source and free to use.

👨‍💻 Author

Created by Nomadic Anas
GitHub: https://github.com/Yt-Anas
