# Adria – Test Environment

This repository contains the Docker-based test environment for the Adria project.
It allows running the complete Adria solution locally without any IDE or source code,
and simulates a production environment as closely as possible.

## Prerequisites
- Docker Desktop

## Start the environment

From the root of this repository, run:

```bash
docker compose -f docker-compose.yml up -d
