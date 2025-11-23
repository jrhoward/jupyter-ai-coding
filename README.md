# jupyter-ai-coding

Lightweight Jupyter Lab image and compose setup for local development.

## Files
- containers/Dockerfile.juypter — Dockerfile used to build the image (parameterized with build args).
- docker-compose.yml — Compose service to build and run the container, mounts a workspace volume.
- .env — Optional environment file for configuration (see example below).

## .env example
Create `code/.local/.env` next to `docker-compose.yml` (keep secrets out of VCS):
