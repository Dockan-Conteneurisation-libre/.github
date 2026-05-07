# Dockan - Free Containerization, Without a Daemon, Without Cloud Lock-In

<p align="center">
  <img src="https://raw.githubusercontent.com/Dockan-Conteneurisation-libre/Dockan/main/docs/dockan-logo.svg" alt="Dockan logo" width="120">
</p>

Dockan is a free and open containerization ecosystem designed for self-hosting, experimentation, education, and simplicity.

The goal is clear: provide a modern alternative to Docker, without a required daemon, without imposed cloud services, and with images that are easy to understand, share, back up, and install.

## Main Projects

### Dockan

The main engine and CLI.

- containers without a permanent daemon
- open image format
- `run`, `build`, `compose`, `images`, `volume`, `network`, `deps`, and `update` commands
- lightweight isolation with auto-detection
- volume, network, healthcheck, and stack management

Repo: https://github.com/Dockan-Conteneurisation-libre/Dockan

### Dockan Panel

A web administration interface to manage Dockan from a browser.

- local dashboard
- container, image, volume, and network management
- live terminal inside containers
- `dockan.yml` stack management
- system dependency installation
- Dockan and panel updates
- Dockan Store integration
- installable PWA

Repo: https://github.com/Dockan-Conteneurisation-libre/Dockan-Panel

### Dockan Store

A catalog of ready-to-install applications for Dockan.

- ready-to-use self-hosted apps
- prebuilt images
- complete packs or per-app downloads
- simple installation from the CLI or Panel
- examples: WordPress, Nextcloud, Gitea, Matomo, Grafana, Vaultwarden, Static Site, and more

Repo: https://github.com/Dockan-Conteneurisation-libre/Dockan-store  
Site: https://dockan-conteneurisation-libre.github.io/Dockan-store/


### Dockan Windows

Dockan Windows is the native Windows port of Dockan.

This repository is copied from the Linux Dockan codebase, then adapted to use Windows container APIs and Windows packaging. The target is the same Dockan CLI workflow on Windows, backed by HCS, HNS, mapped directories, scheduled tasks, and Windows container image metadata.

Repo : https://github.com/Dockan-Conteneurisation-libre/Dockan-Windows


## Main Features

- **Daemonless**: no heavy background service required
- **No cloud lock-in**: images can be shared freely
- **Open format**: a Dockan image is a folder or a `.tar.gz` archive
- **Easy to inspect**: readable files and a clear structure
- **Self-hosting**: designed for personal servers, homelabs, and small infrastructure
- **Web panel**: simple administration from a browser
- **App store**: install applications in a few clicks
- **Multi-distribution Linux**: progressive dependency handling depending on the system
- **Education**: understand containerization without a black box

## Vision

Dockan aims to make containerization more accessible, more transparent, and more free.

The project does not try to hide the system behind a large closed platform. Instead, it aims to make images, files, volumes, networks, and commands understandable.

Dockan is made for people who want to host, learn, share, and stay in control.

## Quick Install

```bash
curl -fsSL https://raw.githubusercontent.com/Dockan-Conteneurisation-libre/Dockan/main/scripts/install.sh | sh
dockan version
```
