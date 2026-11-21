<h1 align="center">Tom Fournier</h1>

<p align="center">
  <b>Développeur full-stack · Étudiant à 42 Lyon</b><br>
  TypeScript · Node.js · C / C++ · Docker · Linux
</p>

<p align="center">
  <img src="https://img.shields.io/badge/42-Lyon-000000?style=flat-square&logo=42&logoColor=white" alt="42 Lyon">
</p>

<p align="center">🇫🇷 Français · <a href="https://github.com/Tommfnr/Tommfnr/blob/main/README.en.md">🇬🇧 English</a></p>

---

## À propos

Je suis étudiant à **42 Lyon** depuis 2024. On y apprend en faisant des projets, sans cours magistraux, et en corrigeant le travail des autres. J'aime construire des applications de bout en bout : l'interface, l'API et la base de données, puis la mise en production et la surveillance.

En parallèle de l'école, j'ai développé et je maintiens une **application web pour une vraie association** : un outil de planning des bénévoles, déployé sur un VPS et utilisé tous les jours.

## Projets

### 🤝 PEP, Prêt Entre Particuliers · *ft_transcendence (projet de fin de tronc commun 42)*
Une plateforme pour se prêter des objets entre membres d'un même groupe, où le lien entre les gens compte avant la transaction. Nous l'avons construite à 5, avec une architecture microservices.

- **Mon rôle :** Product Owner et développeur full-stack, co-auteur du concept
- **Ma partie :** le **chat en temps réel** (gateway Socket.IO avec authentification JWT, une room par utilisateur pour joindre tous ses onglets et appareils, reconnexion avec un token rafraîchi, rattrapage des messages manqués), le catalogue d'objets (pagination, tri), les profils et les groupes, et la gestion des erreurs côté client
- **Stack :** Angular · NestJS · TypeScript · PostgreSQL / Drizzle · Socket.IO · Docker · Prometheus / Grafana
- Environ 15 conteneurs, près de 100 branches, workflow par pull requests

### 📅 Planning de bénévoles pour une association · *Projet client, en production*
Une application web qui gère le planning annuel d'une association : sessions, présences, responsables de soirée, exports et conformité RGPD.

- J'ai conçu l'application **comme un template multi-clients** : un conteneur, une base, un domaine et un dépôt de déploiement par client, sans code propre à un client
- **Mise en production :** VPS OVH, Docker Compose, reverse proxy Nginx, HTTPS avec Let's Encrypt et renouvellement automatique
- **Fiabilité :** tests fonctionnels lancés sur chaque client à chaque déploiement, tests de non-régression visuelle pixel par pixel (Playwright), sauvegardes de la base, monitoring avec alertes Discord
- **Stack :** Node.js · Express · SQLite · JavaScript · Docker · Nginx

### 🌐 Webserv · *Serveur HTTP/1.1 en C++98*
Un serveur web non bloquant, écrit sans bibliothèque externe et configurable comme Nginx. Projet d'équipe.
- Ma partie : le traitement des requêtes, les chemins et les pages d'erreur, l'autoindex, les redirections, la méthode POST et les query strings
- 🔗 [mangojus/webserv](https://github.com/mangojus/webserv)

### 🧪 [Webserv42_tester](https://github.com/Tommfnr/Webserv42_tester)
Un outil Python sans dépendance qui prépare tout seul l'environnement de test et lance **plus de 100 tests HTTP** sur un serveur Webserv. Il est utilisé par d'autres étudiants de 42.

### 🐳 Inception · *Administration système*
Une infrastructure WordPress complète montée avec Docker Compose, **sans aucune image toute faite** : NGINX (TLS 1.2/1.3), WordPress + php-fpm et MariaDB, chacun dans un conteneur construit depuis Alpine, avec un réseau privé et des volumes persistants.

### 🎮 [Cub3D](https://github.com/Tommfnr/Cub3D)
Un moteur de rendu 3D par raycasting en C, inspiré de Wolfenstein 3D.

## Technologies

**Langages**<br>
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Front-end et back-end**<br>
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Bases de données**<br>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)

**DevOps et outils**<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

---

<p align="center"><i>Ouvert aux opportunités : stage, alternance ou premier poste en développement.</i></p>
