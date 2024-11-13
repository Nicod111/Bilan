# Installation de WordPress et Zabbix avec Docker

## Description

Ce projet permet de déployer facilement WordPress et Zabbix à l'aide de Docker et Docker Compose. Il contient un script d'installation pour Docker et Docker Compose, ainsi qu'un fichier `docker-compose.yml` pour lancer les containers.

## Prérequis

- Proxmox installé et configuré.
- Une VM avec une distribution minimale (Ubuntu, Debian, etc.).
- Docker et Docker Compose installés.

## Installation

1.Cloner le repository :
   git clone https://github.com/Nicod111/Bilan.git
   cd Bilan.git

2.Exécuter le script d'installation de Docker :
   chmod +x install_docker.sh
   ./install_docker.sh

3.Lancer les containers Docker :
   docker-compose up -d

4.Accès aux services
Accédez à WordPress sur http://<votre_ip>:8080 et à Zabbix sur http://<votre_ip>:8081.


#Structure des fichiers :
install_docker.sh : Script pour installer Docker et Docker Compose.
docker-compose.yml : Fichier de configuration Docker pour déployer WordPress et Zabbix.
