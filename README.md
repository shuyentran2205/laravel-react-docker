# Laravel + React + MySQL Docker Compose

## 1. Giới thiệu
Dự án này là bài tập Docker, mục tiêu là đóng gói một ứng dụng full-stack gồm:
- Backend: Laravel 12 (PHP 8.4)
- Frontend: React (Create React App)
- Database: MySQL 8
- Web Server: Nginx

Toàn bộ hệ thống được chạy bằng Docker Compose, giúp chuẩn hoá môi trường và dễ dàng chạy lại trên máy khác.

---

## 2. Yêu cầu môi trường
- Docker
- Docker Compose
- Windows + WSL2 hoặc Linux / macOS

---

## 3. Cấu trúc thư mục
laravel-react-docker/
├── backend/ # Laravel backend
│ ├── Dockerfile
│ ├── nginx.conf
│ └── .env.example
├── frontend/ # React frontend
│ └── Dockerfile
├── docker-compose.yml # Docker Compose cấu hình toàn hệ thống
└── README.md
---
### 4 Clone source code
```bash
git clone https://github.com/shuyentran2205/laravel-react-docker.git
cd laravel-react-docker
Cách chạy dự án: docker compose up --build

