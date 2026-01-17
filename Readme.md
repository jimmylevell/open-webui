# About Open WebUI
Open WebUI self-hosted container definition.

## Frameworks used
- Open WebUI

# Docker image details
## Application
Base image: ghcr.io/open-webui/open-webui:main

# Deployment
## General
Service: open-webui
Data Path: /srv/docker/openwebui/
Access URL: openwebui.app.levell.ch

## Attached Networks
- traefik-public - access to reverse proxy

## Attached volumes
openwebuiuiata: storing the Open WebUI application data

## Environment variables
Optional:
- QDRANT_API_KEY: API key for Qdrant vector database
- QDRANT_URI: URI for Qdrant instance

# Authentication
Configured through Open WebUI application
