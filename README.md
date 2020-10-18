# caddy2-cloudflare

[![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/exuanbo/caddy2-cloudflare)](https://hub.docker.com/r/exuanbo/caddy2-cloudflare)

Caddy v2.2.1 docker image with Cloudflare module [caddy-dns/cloudflare](https://github.com/caddy-dns/cloudflare).

```sh
docker run -d \
  -v $(pwd)/Caddyfile:/etc/Caddyfile \
  -p 80:80 -p 443:443 \
  exuanbo/caddy2-cloudflare
```
