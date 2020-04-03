# Traefik

https://docs.traefik.io

Thanks to @cbirkenbeul for maintaining that great git repo: [docker-homelab](https://github.com/cbirkenbeul/docker-homelab)

## Requirements

### Create a network
```
docker network create traefik_proxy
```

### ACME Directory
```
cd config/ACME
chmod 600 acme.json
```
