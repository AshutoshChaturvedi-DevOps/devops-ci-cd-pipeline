# 🚀 Automated CI/CD Pipeline

## 📖 Overview
This project demonstrates an **end-to-end Continuous Integration and Continuous Deployment (CI/CD)** pipeline using:
- **GitHub Actions** for automation
- **Docker** for containerization
- **GitHub Container Registry (GHCR)** for image hosting
- **Docker Compose** for deployment

Whenever code is pushed to the `main` branch:
1. Tests are executed.
2. A Docker image is built.
3. The image is pushed to the container registry.
4. The staging environment is updated.

---

## 🛠 Tech Stack
- **Language:** Node.js (Express)
- **CI/CD:** GitHub Actions
- **Containers:** Docker
- **Registry:** GitHub Container Registry (GHCR)
- **Deployment:** Docker Compose

---

## 📂 Project Structure
