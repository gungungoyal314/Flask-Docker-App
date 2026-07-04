# Flask-Docker-App

A simple Flask application containerized using Docker and integrated with GitHub Actions for Continuous Integration (CI). The Docker image is automatically built and pushed to Docker Hub whenever changes are pushed to the `main` branch.

## 🚀 Features

- Flask Web Application
- Docker Containerization
- Docker Hub Integration
- GitHub Actions CI Workflow
- Easy Deployment

## 📁 Project Structure

```
Flask-Docker-App/
│── app.py
│── Dockerfile
│── requirements.txt
└── .github/
    └── workflows/
        └── docker.yml
```

## 🛠️ Technologies Used

- Python 3.11
- Flask
- Docker
- Docker Hub
- GitHub Actions

## ⚙️ Build Docker Image

```bash
docker build -t flask-docker-app:v1 .
```

## ▶️ Run Docker Container

```bash
docker run -d -p 5000:5000 --name flask-container flask-docker-app:v1
```

Open your browser:

```
http://localhost:5000
```

## 🐳 Docker Hub Image

```bash
docker pull gungungoyal0511/flask-docker-app:v1
```

## 🔄 CI Workflow

Whenever code is pushed to the `main` branch:

- GitHub Actions starts automatically.
- Docker image is built.
- Image is pushed to Docker Hub.

## 📸 Output

```
Hello Gungun! Docker Project Successfully Running.
```

## 👩‍💻 Author

**Gungun Goyal**

GitHub: https://github.com/gungungoyal314

Docker Hub: https://hub.docker.com/u/gungungoyal0511
