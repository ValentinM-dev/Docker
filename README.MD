# 🐳 Docker Cheat Sheet

## 🔑 Termes importants
- **Registre (Registry)** : Stockage de multiples Images
- **Image** : Image statique et persistée d'un conteneur
- **Conteneur (Container)** : Instance d'une image en cours d'exécution

## 🌐 Hub Docker
[Docker Hub](https://hub.docker.com) : Site permettant d'installer des systèmes / extensions

## ⚙️ Structure de Docker
Serveur → Système d'exploitation → Moteur Docker → Applications + Librairies (Conteneurs)

## 📋 Commandes de base

### 🔍 Gestion des conteneurs
- `docker ps` ou `docker container ls` : Liste les conteneurs existants
- `docker run <image>` : Exécute une image existante
- `docker stop <conteneur>` : Stoppe un conteneur
- `docker rm <conteneur>` : Supprime un conteneur  
  👉 Supprimer plusieurs conteneurs :  
  `docker rm <container1> <container2> <container3>`

### 📦 Gestion des images
- `docker image ls` : Liste les images existantes
- `docker image rm <id>` : Supprime une image via son ID

### ⚡ Gestion via configuration (docker-compose)
- `<configuration> up` : Lance un conteneur et installe les composants nécessaires
- `<configuration> down` : Stoppe et supprime un conteneur

## 🎛 Options utiles en terminal
- `-a` : Sélectionne tous
- `-d` : Détaché (background)
- `-p` : Ports
- `--name` : Définit le nom d'un conteneur

⚠️ Docker fonctionne avec un serveur **Linux**.
