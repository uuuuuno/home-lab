# Proxy Server

In this proxy server, I used [Cloudflare tunnels](https://www.cloudflare.com/products/tunnel/) to provide secure access to my services. The repository also includes [uptime-kuma](https://github.com/louislam/uptime-kuma) for monitoring the availability of services.

- **cloudflared**: https://hub.docker.com/r/cloudflare/cloudflared
- **uptime-kuma**: https://hub.docker.com/r/louislam/uptime-kuma

## Launch

Docker Compose is used to launch containers. If there is a `.env.example` file in the project folder, it should be renamed to `.env` and your variables should be specified in it.

```shell
# Launch
docker compose up -d
```