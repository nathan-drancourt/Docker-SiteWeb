# 🚀 Projet Docker – Site Web Personnel
#Docker #NGINX #DevOps #Virtualisation #Conteneurisation #IT

## 📌 Description
Ce projet illustre la création et le déploiement d’un **site web statique hébergé dans un conteneur Docker** basé sur NGINX.  
L’objectif est de comprendre les bases de la conteneurisation et de mettre en pratique un premier déploiement reproductible et portable.

## 🛠️ Compétences mises en œuvre
- Utilisation de **Docker Desktop** sous Windows
- Manipulation des **images et conteneurs** (docker run, docker build)
- Construction d’une image personnalisée avec un **Dockerfile**
- Déploiement d’un serveur web avec **NGINX**
- Gestion des ports et de la redirection (exposition du site sur `localhost`)

## ⚙️ Technologies utilisées
- Docker Desktop (Windows 11)
- NGINX (image officielle Docker Hub)
- HTML (site statique basique)

## 🚀 Comment tester
1. Cloner ce dépôt :
   ```bash
   git clone https://github.com/nathan-drancourt/Docker-SiteWeb.git
   cd Docker-SiteWeb/site-web
2. Construire l'image Docker :
   ```bash
   docker build -t mon-site-docker .
3. Lancer le conteneur :
   ```bash
   docker run -d -p 8081:80 mon-site-docker
4. Accéder au site dans le navigateur :
   ```bash
   👉 http://localhost:8081
   
