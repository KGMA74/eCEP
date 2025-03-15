Here's an improved version of your README in English and French:

___

# eCEP

## English

### Commands to run:

```sh
git clone https://github.com/KGMA74/eCEP.git
git submodule init
git submodule update
```

### Configuration

The `.env` file represents the global configuration file. In it, you'll find the `DOMAIN` variable, which should be replaced by the IP address (e.g., 192.168.x.x) if you are on a local network, or the public domain name (e.g., domain.com) if you are on the internet.

The website will be available at the URL specified in the `DOMAIN` variable in the `.env` file.

### Prerequisites

- Docker
- Docker Compose

### Build

To build the project for the first time:

```sh
docker-compose build --up
```

For subsequent runs:

```sh
docker-compose up
```

## Français

### Commandes à exécuter :

```sh
git clone https://github.com/KGMA74/eCEP.git
git submodule init
git submodule update
```

### Configuration

Le fichier `.env` représente le fichier de configuration global. Vous y trouverez notamment la variable `DOMAIN`, qui devrait être remplacée par l'adresse IP (par exemple, 192.168.x.x) si vous êtes dans un réseau local, ou par le nom de domaine public (par exemple, domain.com).

Le site web sera disponible à l'URL précisée dans la variable `DOMAIN` du fichier `.env`.

### Prérequis

- Docker
- Docker Compose

### Build

Pour construire le projet pour la première fois :

```sh
docker-compose build --up
```

Pour les exécutions suivantes :

```sh
docker-compose up
```

``` MEMBRE DU GROUPE
KARAMBIRI ARNOLD
KAMBOU ARMMEL
```
