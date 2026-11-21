<h1 align="center">Tom Fournier</h1>

<p align="center">
  <b>Full-stack developer · Student at 42 Lyon</b><br>
  TypeScript · Node.js · C / C++ · Docker · Linux
</p>

<p align="center">
  <img src="https://img.shields.io/badge/42-Lyon-000000?style=flat-square&logo=42&logoColor=white" alt="42 Lyon">
</p>

<p align="center"><a href="https://github.com/Tommfnr">🇫🇷 Français</a> · 🇬🇧 English</p>

---

## About me

I've been a student at **42 Lyon** since 2024. The school has no lectures: you learn by building projects and by reviewing other students' work. I like building applications end to end: the interface, the API and the database, then deploying them and keeping an eye on them in production.

Alongside school, I built and maintain a **web application for a real non-profit**: a volunteer scheduling tool, deployed on a VPS and used every day.

## Projects

### 🤝 PEP, peer-to-peer lending · *ft_transcendence (final project of the 42 core curriculum)*
A platform where members of the same group lend each other objects, putting the social connection before the transaction. We built it as a team of 5, with a microservices architecture.

- **My role:** Product Owner and full-stack developer, co-author of the concept
- **My part:** the **real-time chat** (Socket.IO gateway with JWT authentication, one room per user so all their tabs and devices are reached, reconnection with a refreshed token, catch-up on missed messages), the object catalog (pagination, sorting), profiles and groups, and client-side error handling
- **Stack:** Angular · NestJS · TypeScript · PostgreSQL / Drizzle · Socket.IO · Docker · Prometheus / Grafana
- About 15 containers, close to 100 branches, pull-request workflow

### 📅 Volunteer scheduling for a non-profit · *Client project, in production*
A web application that runs a non-profit's yearly schedule: sessions, attendance, evening managers, exports and GDPR compliance.

- I designed it **as a multi-client template**: one container, database, domain and deploy repository per client, with no client-specific code
- **Deployment:** OVH VPS, Docker Compose, Nginx reverse proxy, HTTPS with Let's Encrypt and automatic renewal
- **Reliability:** functional tests run against every client on each deploy, pixel-by-pixel visual regression tests (Playwright), database backups, monitoring with Discord alerts
- **Stack:** Node.js · Express · SQLite · JavaScript · Docker · Nginx

### 🌐 Webserv · *HTTP/1.1 server in C++98*
A non-blocking web server written without external libraries and configured like Nginx. Team project.
- My part: request handling, paths and error pages, autoindex, redirects, the POST method and query strings
- 🔗 [mangojus/webserv](https://github.com/mangojus/webserv)

### 🧪 [Webserv42_tester](https://github.com/Tommfnr/Webserv42_tester)
A dependency-free Python tool that sets up the test environment by itself and runs **more than 100 HTTP tests** against a Webserv server. Other 42 students use it.

### 🐳 Inception · *System administration*
A complete WordPress infrastructure built with Docker Compose **without any ready-made image**: NGINX (TLS 1.2/1.3), WordPress + php-fpm and MariaDB, each in its own container built from Alpine, with a private network and persistent volumes.

### 🎮 [Cub3D](https://github.com/Tommfnr/Cub3D)
A raycasting 3D rendering engine in C, inspired by Wolfenstein 3D.

## Tech stack

**Languages**<br>
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Front-end and back-end**<br>
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Databases**<br>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)

**DevOps and tools**<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

---

<p align="center"><i>Open to opportunities: internship, work-study (alternance) or first developer role.</i></p>
