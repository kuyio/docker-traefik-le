# Docker-Traefik-LE
Example of a Docker host with Traefik as reverse proxy and Let's Encrypt support

# Usage

1. Customize `traefik/traefik.toml`: change `DOMAIN` to your TLD.
2. Customize `traefik/docker-compose.yml`: change `DOMAIN` to your TLD.
3. Customize `traefik/docker-compose.yml`: set `username` and `password` for the dashboard
4. Use `app-template/docker-compose.yml` as a template for your application.

Any application deployed with the appropriate Traefik labels on the `containers` network will be exposed automatically in traefik.