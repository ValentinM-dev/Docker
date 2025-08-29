Ce document permet de suivre la découverte de Docker.

Termes Important : 
- Registre (Registry) : Stockage de multiples Images
- Image : Image statique et persistée d'un conteneur
- Conteneur (container) : Instance d'une image en cours d'éxécution

Hub Docker : 
Site permettant d'installer des systèmes / Des extensions : [Docker](https://hub.docker.com)

Structure de Docker: 
Serveur -> Système d'exploitation -> Moteur Docker -> Applications + Librairie (Conteneur)

Commande de base docker : 

```docker ps``` ou ```docker container ls``` : Liste les conteneurs existants dans un dossier spécifique

```docker run <image>``` : Exécute les images existantes




```docker image ls``` : Liste les images existantes
```docker image rm <id>``` : Supprime l'image via son id


```docker stop <conteneur>``` : Stoppe le conteneur mentionné

```docker rm <conteneur>``` : Supprime le conteneur mentionné 
Il est possible de supprimer plusieurs containeur en faisant ceci ```docker rm <container> <container> <container>```

```<configuration> up``` : Permet de lancer le conteneur en installant les composants nécessaire
```<configuration> down``` : Permet de stopper le conteneur actuel

Les différents choix possible en terminal : 

```-a``` : Selectionne tous
```-d``` : Détacher
```-p``` : Ports
```-name```: Selectionne le nom

:warning: Docker fonctionne avec un serveur Linux.