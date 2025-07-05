# UptimePro – Self-Hosted Uptime Monitoring Dashboard

A professional-grade self-hosted uptime monitoring system deployed on AWS using Docker.

## 🚀 Tech Stack
- AWS EC2 (Ubuntu)
- Docker & Docker Compose
- Uptime Kuma

## 📊 Live Demo
http://43.204.145.220:3001

## 🧩 Features
- Realtime monitoring of websites and APIs
- Easy UI to add/remove monitors
- Email/Telegram/Slack alert support
- Fully Dockerized with persistent data volume

## 📸 Screenshots

### Dashboard
![Dashboard](./screenshots/uptimepro-dashboard.png)


## 🛠️ Deployment Steps

1. Launch an EC2 (Ubuntu 24.04) instance on AWS
2. Install Docker + Docker Compose:
    ```bash
    curl -fsSL https://get.docker.com -o get-docker.sh
    sudo sh get-docker.sh
    sudo apt install docker-compose -y
    ```
3. Upload `docker-compose.yml` via SCP
4. Run:
    ```bash
    docker-compose up -d
    ```
5. Open in browser: `http://<your-ec2-public-ip>:3001`

## 👤 Author
**Rohan Reddy**  
🔗 [GitHub](https://github.com/RohanReddy-M)
