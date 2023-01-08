# Projet NF19

## Installation de docker

__Prérequis__ : Avoir installé docker et docker compose  
  
Si vous ne les avez pas installés :  
  
Install docker : https://docs.docker.com/engine/install/  
Install docker compose : https://docs.docker.com/compose/install/

Version minimale de docker compose : 1.13.0

## Démarrer l'infrastructure  

1. Démarrer docker sur votre machine

```bash
sudo systemctl start docker
```

2. Copier le repo sur votre machine

```bash
git clone https://github.com/TheoM769/projetNF19
```
3. Aller dans le répertoire

```bash
cd projetNF19
```
4. Utiliser docker compose

```bash
sudo docker compose up -d
```

## Visiter le site

Ouvrir votre navigateur web et copier coller le lien ci-dessous

```bash
http://localhost:8080
```

## Modifier le site

1. Ouvrir votre navigateur web et copier coller le lien ci-dessous

```bash
http://localhost:8080/wp-admin
```

2. Entrer les identifiants (id : root, mot de passe: root) pour se connecter à l'interface de gestion wordpress
