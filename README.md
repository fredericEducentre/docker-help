# Tuto-docker

Commandes docker avec explication et exemples :

## docker `network`

Permet de créer et de démarrer un conteneur à partir d'une image.

**Exemple :**
```bash
docker run -d --name mycontainer nginx
```
*Démarre un conteneur en arrière-plan avec l'image `nginx` et le nomme `mycontainer`.*

## docker `network`

Permet de gérer les réseaux Docker.

**Exemple :**
```bash
docker network create mynetwork
```
*Crée un réseau Docker nommé `mynetwork`.*

## docker `start`

Démarre un conteneur existant.

**Exemple :**
```bash
docker start mycontainer
```
*Démarre le conteneur nommé `mycontainer`.*

## docker `stop`

Arrête un conteneur en cours d'exécution.

**Exemple :**
```bash
docker stop mycontainer
```
*Arrête le conteneur nommé `mycontainer`.*

## docker `pull`

Télécharge une image depuis un registre Docker.

**Exemple :**
```bash
docker pull nginx
```
*Télécharge l'image `nginx` depuis Docker Hub.*

## docker `login`

Authentifie l'utilisateur auprès d'un registre Docker.

**Exemple :**
```bash
docker login -u user -p password
```
*Se connecte au registre Docker avec l'utilisateur `user` et le mot de passe `password`.*

## docker `push`

Envoye une image vers un registre Docker.

**Exemple :**
```bash
docker push myuser/myimage:latest
```
*Envoie l'image `myuser/myimage` vers le registre Docker.*

## docker `ps`

Liste les conteneurs en cours d'exécution.

**Exemple :**
```bash
docker ps
```
*Affiche la liste des conteneurs en cours d'exécution.*

## docker `build`

Construit une image Docker à partir d'un Dockerfile.

**Exemple :**
```bash
docker build -t myimage .
```
*Construit une image nommée `myimage` à partir du Dockerfile du répertoire courant.*

## docker `tag`

Ajoute un tag à une image existante.

**Exemple :**
```bash
docker tag myimage:latest myuser/myimage:1.0
```
*Ajoute le tag `1.0` à l'image `myimage` sous le nom `myuser/myimage`.*
```
