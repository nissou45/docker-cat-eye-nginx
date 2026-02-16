# Docker CatEye NGINX

Simple projet Docker qui sert une page web avec Nginx.

## Structure

- `index.html` → page HTML
- `Dockerfile` → construction de l’image
- `.dockerignore` → fichiers ignorés

## Commandes

### Build

```bash
docker build -t cat-eye-nginx .


docker run -p 8080:80 cat-eye-nginx[

