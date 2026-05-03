# Dockan — Conteneurisation libre, sans daemon, sans cloud

<p align="center">
  <img src="https://raw.githubusercontent.com/Dockan-Conteneurisation-libre/Dockan/main/docs/dockan-logo.svg" alt="Dockan logo" width="120">
</p>

Dockan est un écosystème libre de conteneurisation pensé pour l’auto-hébergement, l’expérimentation, l’éducation et la simplicité.

L’objectif est clair : proposer une alternative moderne à Docker, sans daemon obligatoire, sans cloud imposé, avec des images faciles à comprendre, partager, sauvegarder et installer.

## Projets principaux

### Dockan

Le moteur principal et la CLI.

- conteneurs sans daemon permanent
- images au format ouvert
- commandes `run`, `build`, `compose`, `images`, `volume`, `network`, `deps`, `update`
- isolation légère avec auto-détection
- gestion des volumes, réseaux, healthchecks et stacks

Repo : https://github.com/Dockan-Conteneurisation-libre/Dockan

### Dockan Panel

Interface web d’administration pour gérer Dockan depuis un navigateur.

- dashboard local
- gestion des conteneurs, images, volumes et réseaux
- terminal live dans les conteneurs
- gestion des stacks `dockan.yml`
- installation de dépendances système
- mise à jour de Dockan et du panel
- intégration Dockan Store
- PWA installable

Repo : https://github.com/Dockan-Conteneurisation-libre/Dockan-Panel

### Dockan Store

Catalogue d’applications prêtes à installer avec Dockan.

- apps auto-hébergées prêtes à l’emploi
- images prébuildées
- packs complets ou par application
- installation simple depuis CLI ou Panel
- exemples : WordPress, Nextcloud, Gitea, Matomo, Grafana, Vaultwarden, Static Site, etc.

Repo : https://github.com/Dockan-Conteneurisation-libre/Dockan-store  
Site : https://dockan-conteneurisation-libre.github.io/Dockan-store/

## Fonctionnalités principales

- **Sans daemon** : pas de service lourd obligatoire en arrière-plan
- **Sans cloud imposé** : les images se partagent librement
- **Format ouvert** : une image Dockan est un dossier ou une archive `.tar.gz`
- **Simple à inspecter** : fichiers lisibles, structure claire
- **Auto-hébergement** : pensé pour serveurs personnels, homelabs et petites infrastructures
- **Panel web** : administration simple depuis navigateur
- **Store d’apps** : installation d’applications en quelques clics
- **Multi-distribution Linux** : gestion progressive des dépendances selon le système
- **Éducation** : comprendre la conteneurisation sans boîte noire

## Vision

Dockan veut rendre la conteneurisation plus accessible, plus transparente et plus libre.

Le projet ne cherche pas à cacher le système derrière une grosse plateforme fermée. Il cherche au contraire à rendre les images, les fichiers, les volumes, les réseaux et les commandes compréhensibles.

Dockan est fait pour celles et ceux qui veulent héberger, apprendre, partager et garder le contrôle.

## Installation rapide

```bash
curl -fsSL https://raw.githubusercontent.com/Dockan-Conteneurisation-libre/Dockan/main/scripts/install.sh | sh
dockan version
